# BreakBuddy Changelog
All notable changes to BreakBuddy will be documented in this file.

### *Planned Future Developments*
* Support for ends of breaks.
* Pull shift details from Replicon or somewhere else, so that users shift is selected automatically.
  * This might be trickier than I initially thought. If you have any ideas, I'm open to hearing them.

----------------------------------------
## UNRELEASED <!--- [1.x.x] Up & Go -->
#### Added
-
### Fixed
-
#### Deprecated
-
#### Removed
-
----------------------------------------
## Current version 
## [1.1.0] Vegemite on Toast 2020-03-09
#### Added
- Link to Replicon on Setup dialog.
- Custom Shift option.
- Version Details option in right-click tray menu.
  - Clicking the version or patch number on the Setup dialog opens Version Details window.

----------------------------------------
## Previous Versions
### [1.0.0] Wagon Wheels - 2019-07-17
#### Added
- Patch numbers now show on main screen.
  - Patch number refers to the roster data - the file from which BreakBuddy pulls its information. When break times are changed, new patches will be released.
- BreakBuddy now remembers your settings!
  - Reset to Default button has also been added
- Added a number of new messages to the random draw pool.
- Tooltip for the Tray Icon now displays the version and patch details
- Right-Click menu for Tray Icon now displays the selected shiftcode
- Minor cosmetic changes

### [0.9.3] XO Sauce - 2019-07-11 (Beta v3)
#### Added
- Messages from BreakBuddy are now randomised - upwards of 300 possible messages!
#### Fixed
- Installer now allows options to install to Start Menu, and run on startup.

### [0.9.2] Yoplait Petit Miam - 2019-07-09 (Beta v2)
Second Beta version.
#### Added 
- Installer now automatically adds BreakBuddy to the Start Menu.
- BreakBuddy now refers to you by name.
- Toast notification now has a friendly message when BreakBuddy Starts Running.
- BreakBuddy now re-loads after notifying you of the end of your shift in order to select breaks for the next day.
#### Deprecated
- Test Shift no longer shows in the dropdown - this debug code should be hidden from all future versions.

### [0.9.1] Zooper Dooper - 2019-07-09 (Beta v1)
#### Added
- Option to select current shift from drop down menu.
- Option to remind prior to breaks (anywhere from 1 minute to 60 minutes - default is 10.)
- Option to use Message Box instead of Toast Notifications.
- Independant option to use Message Box for pre-break warnings.
