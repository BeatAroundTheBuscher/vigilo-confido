Vigilo Confido
--------------

Survive. Adapt. Win.

A vanilla expansion for OXCE featuring content from EU2012 and others.

Mod.io page: https://openxcom.mod.io/vigilo-confido
Audio & Video Add-on: https://archive.org/details/vigilo-confido-audio-video-1.0.1

The mod is feature complete and playable but has only seen testing by me.
So it will probably still contain bugs.

=== Features ===

 - 5 soldier classes (Ranger, Grenadier, Specialist, Sniper, Psi Operative)
 - ~50 scripted abilities with unique skills for each class
 - 500+ callsigns for each soldier class
 - 20+ cutscenes from the remakes (removed due to licensing reasons)
 - 200+ voice files (Unit responsonse sounds)
 - 8 new alien units (Cyber Floater, Thin Man, Berserker, Armored Muton, Sectopod Drone, Muton Elite, Andromedon, Outsider)
 - 3 new weapon types in T1, T2 & T3 versions (Swords, Shotguns, Sniper Rifles)
 - Complete new graphics for all T2 & T3 weapons and armors
 - Complete rebalancing of all weapons, armors, units and deployments
 - Status, day & night and hit indicators
 - Laser weapons not reasearchable from the start
 - Laser weapons need recharging and can implode in the field
 - Limited Explosives
 - No Tanks (But the Gremlin drone instead)
 - Bring home alien weapons and research them for progress
 - Ground deployment added with a small research tree for squad size
 - "Killing Aliens destroys their Weapons" option is fixed
 - Additional status effects & Visualisations
 - Weapons can be disabled in combat
 - A buttload of maps (thanks to C.M.P)
 - Training rooms
 - Integrated the Commendations mod
 - Passive bonus items (S.C.O.P.E., etc.)

=== Requirements ===

OpenXcom Extended (OXCE) 8.0

Download release versions of OXCE here:
https://openxcom.org/oxce/release/

NOTE: For the intended experience, make sure you have sound turned on and the intro animation enabled.
At least on your first start.

=== Quickstart (via Ufopedia) ===

You can find information about the classes and their skills in the Ufopedia
under the "MILITARY MOLDING" category.

The changes on weapons and armors can be found under the "WEAPONS AND EQUIPMENT" section.

The category "MISSION OBJECTIVES" will always contain an entry with your current objectives.

=== Goals and influences ===

This started out as some experiments with Yankes scripts and soon got out of hand.
I wanted to have skills, like in the remakes and wanted to see which ones I could do.
Turns out I can do most of them.

So this then turned into a more complex mod with a class and skill system at its core and
with mechanical influences from the remakes (EU2012/XCOM2 and Phoenix Point).

My goal is to extend the vanilla X-Com experience with some
mechanics, items, units & lore references from the newer X-Com titles.

While my focus is on the class & skill system, I also completely rebalanced the
weapons and armors and some other gameplay elements.

I also want to try to add only graphics which keep the X-Com style and which harmonize
with the existing graphics. Each tier of items should be visually distinguishable.

Many thanks to XOps and his Xeno Operations for most of the graphical enhancements.
When looking through his modification of the game, I realized we shared many common goals
and it felt like his work was made with the same visual vision as my mod.

=== Concepts ===

Soldiers of each class can be hired directly by X-COM.
Soldiers can choose to undergo the military molding process, gaining access to their class skills in the process.
Classed soldiers receive additional active and passive skills for each level of training.
The active ones are activated with the special icon and the passive ones are always active.

There are three training phases. The initial molding process is awarded to soldiers when they are
hired by X-Com. The Second Phase (or Advanced Training) and Third Phase (or Elite Training)
add additional skills respectively.

Advanced level training requires: The second "Combat Experience" decoration,
which is awarded for 4 kills and 8 missions.

Elite level training requires: The fourth "Combat Experience" decoration,
which is awarded for 10 kills and 16 missions.

=== Skills ===

For a list of the currently implemented skills per class please refer to the file
Rulesets/classSkills.rul line 10, heading "Class Skill list".

There is also in-game description available in the Ufopedia (if you don't want to read some spoilers..).

=== Tiers ===

Weapons and armors all follow the three Tier concept.

T1 is available from the start.

T2 depends on alien alloys.
 - You should aim at researching "Laser Weapons" and "Predator Armor" until April.

T3 depends on Elerium-115.
 - You should aim at researching "Plasma Weapons" and "Warden Armor" until August.

Armor & Weapon Tiers
T1 - Kevlar Armor   & Conventional Weapons
T2 - Predator Armor & Laser Weapons
T3 - Warden Armor   & Plasma Weapons

=== Known Issues / Backlog ===
 - Testing, Balancing
 - Sound effects (Gremlin, Drone)
 - Sprite of combat experience commendation
 - Test newTurnUnit before first turn with extremes: killing, panic, etc.
 - Add Abduction missions without UFOs
 - Longer research
 - Min Strength for Snipers should be higher
 - No UFOs, only terror missions in May?
 - Nanoscale Vest (More weight and nicer Sprite)
 - Weapon sounds
 - Predator accessible too early?
 - Poison working correctly? (With armor and vests?)
 - Nerf health of most aliens? Reduce TU costs?
 - Nerf Chryssalids and Zombies.
 - The stuff in open.errors.log
 - The ending still talks about Cydonia (on the button, etc.), so do the cutscenes

=== Nice to have ===
 - Integrate with https://openxcom.mod.io/extra-explosions
 - A Heads-up about research in Ufopedia
 - Make "Inventory Stats" a fixed user Option
 - Update to CMP 0.3 (or another mappack?)
 - Normalized music
 - Static smoke
 - More Units: Waspite?, Stun Lancer(?), Faceless(?), Turret(?), Exalt(?)
 - Crafts & Craft Weapons
 - New Mission Objectives
 - Gene Lab & MECs
 - FlagByKills for experience indicator
 - Battle Focus costs for flying
 - Enemy abilities (hardened ability: critical hit chance against this unit reduced by 60%)
 - Weapon fragments: https://openxcom.org/forum/index.php/topic,6868.0.html
 - Bleedout & Fatal Wounds
 - (You should also reduce the chance they go unconscious from normal shooting.)
 - Very easy to exhaust the one medi-kit activation on oneself 

=== Changelog ===

=== Cangess in v.0.9.9a ===
 - OXCE 8.0 compatibility
 - Turned the mod into a master mod. It still retrieves contents from xcom1
 - Alien Bases use the alienRace they were created with
 - Added normal Ethereal/Sectoid Commander to other alienRaces to compensate
 - For Adv/Elite Training there are only 2 Commendation Levels now
   - Advanced and Elite requirements were effectively the same (8 or more missions, some kills)
   - Advanced requires 8 Missions and 4 Kills (no change)
   - Elite requires 16 Missions and 10 Kills (new)
 - Extraction for normal Mutons now also give freeze grenades. The prox grenades are worthless/can be bought for $850 anyway
 - Halved initial costs for Scientists/Engineers
 - Firestorm required manufacture space reduced to 20 from 30. Same for some other projects
 - Fixed other small issues

=== Changes in v.0.9.9 ===
 - Armors now recover Battle Focus (No armor gets 3 points, all the rest 2 points per turn)
 - Delayed missionScripts for alien bases to 12 and 16 months (solving the July game breaking issue)
 - Increased Blademaster flat damage from 20 to 30
 - Decreased TU cost for T1, T2 and T3 Swords, Machine Guns and Pistols
 - Decreased Battle Focus cost for Slash (from 6 to 4)
 - Increased damage from 10 to 15 on T1 shotgun shells, added 15% spread
 - Enabled layered paperdolls (code by b1ackwolf, sprites by XCom Files devs)
 - Replaced vanilla Personal Armor sprites with custom Kevlar Vest (sprites by XOps)
 - Replaced Tier 1 sprites and sounds with XOps sprites
 - Replaced Sword, Fusion Blade, vanilla Plasmas sprite with Hans Woofington sprite 
 - Replaced vanilla (alien) laser weapons with sprites by Drages 
 - Added XROSS overhaul mod, modified and expanded by efrenespartano
 - Replaced vanilla interceptor sprites with EU2012 ones (Raven by MickTheMage, Firestom by Tyran_Nick)
 - Reworked Skyranger craft-less deployments and research topics with custom Skyrangers (maps by Aldorn), removed needItem dependency
 - Improved Thin Man assets, sprites  by efrenespartano, The Martian and NeoWorm
 - Improved Sectoid assets, sprites by efrenespartano, b1ackwolf and NeoWorm
 - Added XCOM Base Security NPCs to Base Defense

=== Changes in v.0.9.8.3 ===
 - OXCE 7.9.8 compatibility 
 - Various Bugfixes
 - Integrated CMP Extended v0.8
 - Updated Mechtoid sprites (by efrenespartano)

=== Changes in v.0.9.8.2 ===
 - OXCE 7.1 compatibility (thanks to Buscher)
 - Various Bugfixes & missing Strings
 - Outsider is now easier to find
 - Researching "Outsider Shard" no longer destroys it
 - Firestorm research tree changed
 - Fixed Overseer UFO not appearing, it will now always be detected
 - Some mission objectives have been slightly changed

=== Changes in v.0.9.8 ===
 - Fixed alien melee weapons not hitting
 - No more early game base defense
 - Added Mechtoid enemy
 - Skeleton Key is now researchable (Will Update the mission objectives)
 - Floaters not spawning as Terrorists anymore

=== Changes in v.0.9.7 ===
 - Fixed: Mission objectives not updating when interrogating first live alien
 - Recovery of the hyperwave beacon from a stunned Outsider should now work (nearly as intended)
 - Adjusted facility build costs
 - Fixed Berserker corpses
 - Corrected X-Com Heavy Laser Ufopedia entry
 - Integrated CMP Rice Farm patch
 - Added numeral suffixes to the Skyranger names, indicating deployment size
 - Added built-in medi-kit to Gremlin to match Ufopedia description
 - Fixed missing string

=== Changes in v.0.9.6 ===
 - Strength not applied anymore to laser and plasma swords
 - Fixed Skyranger not purchasable and Basic Deployment unavailable
 - Adjusted build costs for new bases

=== Changes in v0.9.5 ===
 - Fixed terror mission crash
 - Reduced skill use cost of Aid Protocol (Specialist)
 - Scoring andjustments
 - Restructured alien missions

=== Changes in v0.9.4 ===
 - Plot mission deployments re-defined
 - Fixed mission completion bugs
 - Changed workspace requirements of manufacturing projects
 - Fixed display of Battle Focus costs in Skill Menu
 - Adjusted recovery times for wounded soldiers
 - Adjusted research times for most research projects
 - Fixed plasma weapon damage to intended values
 - Added short intro
 - Adjusted Sectopod Armor 
 - Introduced elerium cores
 - Adjusted research & manufacturing costs

=== Changes in v0.9.3 ===
 - Restructured introductionary research and story arc
 - Nerfed specialist shooting skill max cap
 - Re-balanced throwing starting stats for all classes
 - Added 10 points armor damage to proximity grenades (same as standard grenade)
 - Added passive bonus stats to items in ufopedia entries
 - Medi-kit is now a manufacture project (So these engineers got sth. to do)
 - Fixed some units missing the MECHANICAL tag
 - Reduced power of blaster launcher and small launcher
 - Added poison spit to thin man
 - Fixed special ability on andromedon
 - Removed Avenger and Lightning

=== Changes in v0.9.2 ===
 - Increased throwing stats for specialist (To allow for field logistics)
 - Reset general store size to normal
 - Set proximity grenade to intended power
 - Nanoscale research now needed for experimental armor project
 - Medi-kit now avaiable from the start (So the specialist is more useful)
 - Fixed introduction research topic showing up as researchable
 - Fixed crashes on mission end
 - Various bugfixes

=== Notes to self - HERE BE SPOILERS ===

DON'T READ IF YOU WANT TO EXPERIENCE THE STORY LINE FOR THE FIRST TIME:

EU2012 Story: https://www.ufopaedia.org/index.php/Storyline_(EU2012)
A list of cutscene names for special events. More info: https://openxcom.org/forum/index.php/topic,7476.msg117830.html#msg117830

"Bellator in Machina" - "Warrior in the machine"
"Mutare ad custodiam" - "We Change to Protect"

hook wishlist
missionBeginUnit -> Init unit before first turn
missionEndGame   -> End Conditions
dropItemUnit & pickUpItemUnit?
endMovementUnit?
weaponFiredUnit

Cutscene triggers:
 - On Construction finished
 - On manufacturing finished
 - Alien Base detected

Feature Wishlist:
requiredSoldierType for startingCondition
itemFlag: canNotSell
Ability to trigger skills for aliens, or at least let them choose between two weapons.
