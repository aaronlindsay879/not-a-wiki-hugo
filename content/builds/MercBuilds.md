---
title: "MercBuilds"
url: "/MercBuilds"
type: builds
builds:
  - name: Assisted Advancement
    author: Cyden
    type: Production
    uses:
      - R3+
    gem_range: 1e35 - 1e75
    requirements:
      - "Coin Pillage trophy"
    alignment: Neutral
    faction: Merc
    bloodline: Fairy <b>(Ignore if you don't have Bloodlines)</b>
    builds:
      - build: "FR2,FR7,EL5,GB1,TT1,TT7,DD1,DD6,DD7,FC4,DN4,DW7,SP:Fairy Chanting,SP:God's Hand"
      - build: "FR2,EL5,GB1,TT7,DD1,DD6,DD7,FC3,FC4,DN4,DN8,DW7,SP:Fairy Chanting,SP:God's Hand"
        note: "FC3 is 120%"
      - build: "FR2,GB1,UD7,TT1,TT7,DD1,DD6,DD7,FC4,DN4,DW5,DW7,SP:Fairy Chanting,SP:God's Hand"
        note: "DW5 is buffed"
      - build: "FR2,GB1,UD7,TT7,DD1,DD6,DD7,FC3,FC4,DN4,DW5,DW7,SP:Fairy Chanting,SP:God's Hand"
        note: "FC3 is 120%, DW5 is buffed"
    notes:
      - "Remember to get the Know Your Enemy Part I Artifact in R12."
      - "Swap TT1->FC3 if FC3 is 120% or higher (requires 1.5 hours longest session this R)."
    slowdown:
      - "Max your excavations (get your excavation count to as high as possible): Swap FR7 (or UD7)->DN8."
      - "Excavations count of 1600-1700 is recommended for R15 & R16."
      - "Buff DW5 (Blood Sacrifices) with Versatile Builder (see below), then swap EL5->DW5 and FR7->UD7."

  - name: Harley Quinn
    author: Cyden
    type: Trophy
    uses:
      - R3 Harlequin
      - R12 Know Your Enemy Part I
    alignment: Neutral
    faction: Merc
    bloodline: Fairy <b>(Ignore if you don't have Bloodlines)</b>
    builds:
      - build: "FR2,EL5,AN6,GB1,UD7,DM3,TT7,DD1,FC4,FC7,DN4,DW7,SP:Fairy Chanting,SP:God's Hand"
      - build: "FR2,EL5,AN2,GB1,UD7,DM3,TT7,DD6,FC4,DN4,DN8,DW7,SP:Fairy Chanting,SP:God's Hand"
        note: "Excavation cost is too high"
    notes:
      - "This build is for getting Harlequin in R3 and Know Your Enemy Lore Artifact in R12+"
      - "If excavation cost is too high, swap AN6->AN2, DD1->DD6, and FC7->DN8."

  - name: Lucifer
    author: Cyden
    type: Trophy
    uses:
      - R3+
    alignment: Evil
    faction: Merc
    bloodline: Elf <b>(Ignore if you don't have Bloodlines)</b>
    builds:
      - build: "FR2,FR4,FR7,FR9,EL9,AN1,AN5,AN6,DN2,DN3,DN4,DN7,SP:Goblin's Greed,SP:Fairy Chanting"
    notes:
      - "This build is only for getting the Lucifer Trophy."

  - name: Mana Mania
    author: Cyden
    type: Trophy
    uses:
      - R3+ Coin pillage
      - Mana Waste & Power Orb
      - R7+ Autocasting series
    alignment: Neutral
    faction: Merc
    bloodline: Faceless <b>(Ignore if you don't have Bloodlines)</b>
    builds:
      - build: "AN1,GB1,GB5,UD7,TT2,TT7,DD4,DD6,FC7,DN2,DN4,DW7,SP:Fairy Chanting,SP:Moon Blessing"
    notes:
      - "This build is for getting the Coin Pillage trophy, Mana Waste trophy & excavating Power Orb in R3 and getting Autocasting upgrades in R7+."
      - "Buff DD4 with Versatile Builder (see below) before running this build is recommended."
      - "If going for Mana Waste, don't buy anything that increases max mana aside from Helden Sterben Nicht. This includes DD4, Druid Heritage, Mana Matrix, Premeditation and Ruby Power or Reincarnation power if they increase max mana."

  - name: Versatile Builder
    author: Cyden
    type: Buff
    uses:
      - Building count buff
    alignment: Any
    faction: Merc
    bloodline: Goblin <b>(Ignore if you don't have Bloodlines)</b>
    builds:
      - build: "FR2,FR7,EL5,GB1,TT7,DD1,DD6,DD7,FC4,DN2,DN4,DW7,SP:Fairy Chanting,SP:God's Hand"
    notes:
      - "This build is for buffing upgrades that base on 'highest amount of x building built in this reincarnation' (like DD4: Earthly Bond or DW5: Blood Sacrifices)."
      - "Choose the alignment that has the building you want to build (for example: Evil for DW5, Neutral for DD4)."
---

<h6><img src="/Factions/picks/MercenaryTopPage.png" alt="Spellcraft" align="middle"></h6>
<p><b>Important</b>: For <font color=DarkRed><b>R12</b> and above get the <b>Know Your Enemy Part I</b> Artifact, using the Harley Quinn build.</font>

With version 2 comes the ability to load and save mercenary builds. The Faction Upgrades and Spells are saved in templates.

**Note**: You will need to manually select the alignment and bloodline.

**Templates** can be found at the top of each build table (if available).

**Note**: Most Templates are in order that the game save them in. Also when loading Templates the game will buy the upgrades you can afford first and you may need to load Templates several times to buy all upgrades.
