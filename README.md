# How To Use
The program should find your steam library and find the eldenring.exe path. If the program does not: shift + right click your elden ring executable, select "Copy as path", Paste into the path text box, and remove the quotation marks on either side.

Put the seed in that you want to use for randomization, and then hit the Randomize button. When it is done randomizing, the `Bingo!` button will be activated, and clicking it will launch the game with the randomized regulation bin. If a seed is not input one will be randomly created.

# Equipment Randomizer
This application has a simple UI to ensure that all players use the same randomized seed without worry about having the same settings.
* Weapons in general are categorized by type. For example Greatswords are their own pool as are Halberds.
* Staves and seals are not randomized. This includes the Confessor and Prisoner starting classes, merchant shops, etc.
* The Smithscript weapons, Nanaya's Torch, Lamenting Visage, Rabbath's Cannon, and the Velvet Sword of St. Trina are not randomized.
* General Sorceries are randomized with sorceries and Incantations are randomized with incantations (Dragon Communion is seperated).
* Weapon allocations are unique amongst starting classes and merchants.
* As a reminder, shields are treated as weapons by the game. 

# Weapon Type Pooling
* Great Katanas are pooled with Katanas
* Hand to Hand Arts are pooled with Fists
* Backhand Blades are pooled with Daggers
* Axes and Hammers are pooled for more weapon parity
* Thrusting and Heavy Thrusting are pooled for more weapon parity
* Ranged weapons are in a pooled category (bows, and light bows are all in the same pool). 

# Starting Classes
Starting classes are randomized: weapons, armor, stats, and spells. Class levels are fixed to 9, with stats totaling 88.
* The Prisoner starts with its unrandomized staff and one sorcery. 
* The Confessor starts with its unrandomized seal and one incantation.
* Every character is fixed in the DLC to have the benefit of lvl 14 scadu for damage and lvl 18 for damage reduction.

# Powers of Remembrance
Powers of Remembrance are randomized within the remembrance shop. 
Rennala's Remembrance gifts a randomized weapon, to keep an incentive to check each remembrance for weapons.

# Dragon Communion
Dragon communion incantations are only randomized within dragon communion locations.

# Swarm of Flies Bugfix
This mod also patches the AtkParamPC to fix a bug with SpEffectAtkPowerCorrectRate that caused swarm of flies damage to be incorrectly calculated in some circumstances. 

# Smithing Stone Cost
Smithing stone cost is also patched to be 2x stones per level for stones [1, 2, 3, 4, 5], and 1x per level for each level after. (Before Smithing Stone 6 the player needs 6, then they only need 3 for each)

# Unlocked Maps
All maps are unlocked at the start of the game.

# Grouped Sites of Grace
Thoughout the game, graces can be obtained in groups to speed up the run of play. 
The player just needs to touch on of the graces to unlock the whole group.

## Base Game
* Group A: Agheel Lake North, Gatefront, Fort Gaol North, Lake-Facing Cliffs, 
	Siofra River Well Depths, Beside the Crater-Pocked Glade.
* Group B: South Raya Lucaria Gate, Bellum Church, Ainsel River Downstream.
* Group C: Church of the Plague, Cathedral of Dragon Communion.
* Group D: Altus Plateau, Abandoned Coffin, Seethewater River, Bower of Bounty.
* Group E: Schoolhouse Classroom, Prison Town Church.
* Group F: Starscourge Radahn, Ancestral Woods, Palace Approach Ledge-Road.
* Group G: Capital Rampart, Giants' Gravepost, Ordina, Liturgical Town, Freezing Lake, Avenue Balcony.
* Group H: Haligtree Canopy, Prayer Room, Drainage Channel.
* Group P: Morne Moangrave, Ninth Mt. Gelmir Campsite
* Group Q: Audience Pathway, Ancient Snow Valley Ruins, Hidden Path to the Haligtree.

## DLC Game
* Group I: Three-Path Cross, Highroad Cross, Pillar Path Cross.
* Group J: Cathedral of Manus Metry, Fingerstone Hill, Finger Ruins of Rhia.
* Group K: Forsaken Graveyard, Manse Hall.
* Group L: Church District Entrance, Main Gate Plaza, "Storehouse, Loft", "Rauh Ancient Ruins, West"
* Group M: Dragon's Pit Terminus, Jagged Peak Mountainside.
* Group N: Church of the Bud, Spiral Rise, Divine Gate Front Staircase.
* Group O: Castle Watering Hole, Recluses' River Downstream, Cerulean Coast.

TLDR Draconic Tree Sentinel gets each player into capital (do not need two remembrances) and mountaintops,
Romina gets each player to Consort Radahn, Academy gets each player into Volcano Manor, killing Leonine Misbegotten Gives Gelmir Access (by grace), and the grace before Rykard gives Mountaintops access.

# Acknowledgements
* Big thank you to Nordgaren for being the original developer for the randomizer and helping with bug-fixing class messages post-DLC.
* All current changes to SoulsFormats in the project are SoulsFormatsNext.

# Libraries
* [Andre](https://github.com/soulsmods/DSMapStudio/blob/master/src/Andre/Andre.Formats/Param.cs) Formerly FSParam and StudioUtils, a library for parsing FromSoft param formats. These libraries are under the MIT license.  
* [SoulsFormats](https://github.com/soulsmods/DSMapStudio/tree/master/src/Andre/SoulsFormats) from the `souldmods/DSMapStudio` repo. This is a version of [SoulsFormats](https://github.com/JKAnderson/SoulsFormats) updated for .Net 6.
[SoulsFormatsNext](https://github.com/soulsmods/SoulsFormatsNEXT/)
