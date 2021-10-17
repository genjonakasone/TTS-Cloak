## Changelog
Read below for complete changelog history.

### 17/10/2021
- Reverted to older 'Give Cloak' editor module for now since there still seems to be problems with the new module in multiplayer.

### 16/10/2021
- Fixed typo in newer 'Give Cloak' editor module which was preventing the cloak from being added in multiplayer.

### 15/10/2021
Applied changes from script version:  
- Added stringtable support to allow the script to be translated. If you are willing to help translate the script into another language, contact me in my Discord!
- Added 2 new functions, `fn_addCloakActions` and `fn_addVehicleCloakActions`. These are executed locally on players to allow localisation of the action text.

Mod version specific changes:
- Renamed 'Give Vehicle Cloak' editor module to 'Give Active Camouflage' for consistency.  

### 07/10/2021
- Updated 'Give Cloak' editor module to no longer require varnames of player units. Players can now simply be synced to the module. Old module included but hidden to avoid breaking any missions.
- Adjusted module descriptions.
- Added support for upcoming all in one mod.

### 13/08/2021
Applied changes from script version:
- Fixed bug that caused cloaked players to remain invisible to the host player after uncloaking in locally hosted multiplayer games.

### 02/08/2021
- Fixed missing icon for 'Cloak Unit(s)' module.

### 22/07/2021
Applied changes from script version:
- 'Cloak Unit' ZEN module has been renamed to 'Cloak Unit(s)' and now has a second parameter that will apply the cloak effect to the unit's group if enabled.

### 12/07/2021
- Added custom icons for ZEN modules.
- Initial upload.
