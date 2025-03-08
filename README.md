# StarnsBetterCheats
This is intended to replace iseeu0's conversational cheat menu.
Common consensus is that the existing cheat menu for x4 touches too many things that it shouldn't so this is being made to replace that menu for one that effects only the bare minimum to make the cheat work.


# Functions & Todo
## Faction Cheats

### DONE:: Money Cheat

### DONE:: Faction Relations
- Build a list of all factions
- Loop through the list and dynamically build the menu
- Allow user to modify their relation with a faction
- Don't bother changing faction-faction relations as DA does it better.

## Player Cheats

###  Teleporting
- DONE:: Ship to Space
-  Auto Dock Ship to Station

###  Player God
- Ignore `onHit` events
  **OR**
- Statically set health to 100%

###  Add Upgrade Wares to Player
- Build list of all upgrade wares and just add them to the user in the requested amount.

###  Add All Blueprints
- Build a list of all blueprints, then add them to the player.
- Break down into blueprint sizes and station modules.

## Debug Cheats

###  Plot Debug Stuff (Calling Plots & Resetting Progress, etc.)
- Not sure if even possible.
- Ideally, we can repeat actions that were in a queue that has already been completed to 'reset' a bugged plot step.
- Maybe cancel the bugged queue and call it again. Need to look into what options are available.

###  Map Discovery
- Don't need vision, just reveal what sector is where on the map.
- Loop through and add to player known info.

###  Set Faction of Selected Ship

## Fleet Cheats

###  Spawn Ships/Fleets
- Select ship from dropdown, select loadout from saved loadouts.

###  God Mode on Ships
- Ignore `onHit` events
  **OR**
- Statically set health to 100%

###  Select Crew Level for Certain Ships

## Station Cheats

###  Fill Station Storages (Build, etc.)
- Populate menu with required wares, allow user to drag slider to select how full storage of ware is.

###  God Mode on Stations
- Ignore `onHit` events
  **OR**
- Statically set health to 100%
