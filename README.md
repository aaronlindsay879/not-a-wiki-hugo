Proof of concept rewrite of [Not a Wiki](http://musicfamily.org/realm/) using hugo.

#### Pages are generated in three main ways at the moment:

##### Static rip from original sit

At the moment, this is the bulk of the pages - simply taken from not a wiki and reuploaded to [not-a-wiki-static](/not-a-wiki-static/)

##### Generated from a template and data in the front matter

An example of this is [MercBuilds.md](/content/builds/MercBuilds.md) using the template [layouts/builds/single.html](/layouts/builds/single.html).

`MercBuilds.md` includes the data for the builds (in `builds`), as well as information to display (at the bottom of the file) which can be a mix of HTML and markdown.
`layouts/builds/single.html` tells hugo how to convert the data stored in `builds` to HTML.

##### Generated from a template and a data file, with an almost empty content file

An example of this is the content file [ResearchList.md](/content/research/ResearchList.md), using the template [layouts/research/ResearchList.html](/layouts/research/ResearchList.html) and the data file [research.yaml](/data/research.yaml).

`ResearchList.md` is an almost empty file, which only exists to tell hugo to create a page at that url with the right template file.
`layouts/research/ResearchList.html` tells hugo how to convert the data from the data file into html.
`research.yaml` contains research data.

This is used for when data needs to be used in more than one place - builds will only ever be displayed on the build page, but researches are displayed in both the tree and list, for example.

#### Other important things:

##### Partial files

Partial files are essentially snippets of HTML (with embedded code, like shown before) that can be included in templates.
They are being used in two main ways in this project:

- Partials such as [head.html](/layouts/partials/head.html), [header.html](/layouts/partials/header.html) and [footer.html](/layouts/partials/footer.html) which are used to generate static parts of the site and split it up. `head.html` is the head tag, `header.html` is header content within the body
- Partials such as [effect.html](/layouts/partials/effect.html) which are used to abstract away logic and make templates simpler - in this case, `effect.html` converts a single research effect into html while handling every edge case.
