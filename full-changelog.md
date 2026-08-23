# Full changelog
## Version 5.0 release (23/8/26): Restructuration part 1
This update is the fist one of the restructuration updates, updates made for an ecosystem with other macros, standards, and systems (BES, BMM, BNM, BUI).
So, after months of development (BDND 5.0: silksong) here's the list of changes:

### Features
- Added QS tile modes.
- Added "restore to" (restore to custom value).
- Added main menu you will probably never use.
- Added VolMap support (Udu, Udd).
- Added a (proper) plugin store (BMM based).
- Added new splash texts.
- Reworked self repair and UpdChk.

### UI changes
- Added info button to show/hide info.
- Changed background color to FF0C0C0C.
- Secret menu now tells you the remaining clicks.
- Added bigger separators to settings.
- Titles now dynamically change size based on the screen size.

### Internal changes (stability)
- Improved state management to avoid null state or doble activation.
- Changed name to follow the new naming standard (we will miss you [], you looked nice but BMM, GitHub, and Google Drive hate you).
- Improved QS tile synchronization to avoid fake states errors.
- Added version conflict detector (BES better 531).
- Settings now closes the scene before opening it to avoid scene conflicts.
- Standardized (almost) all errors to use BES.
- Updated BUI to version 2.0.
- Blockified (most of the) setup.
- UpdChk version is no longer hardcoded
- Time window to break state is now smaller.
- Organized triggers.
- Added separators to the macro.
- Enable will no longer enable twice.

### Bug fixes
- Fixed QS tile not showing state correctly.
- Fixed BES better 614 showing even with latest macrodroid version.
- Fixed scene conflicts.
- Fixed timeline error for time travelers.
- Fixed some menus not working in argentinian language.
- Setup finally works on all devices (i hope).

Thanks Oktalion and Mateo for testing this version

## Version 4.1.0a hotfix:
- Fixed language errors in modes section.
## Versión 4.1 small update (30/3/26):
- Fixed splash error.
- Added time to run update check and self-repair.
- Improved self-repair.
## Versión 4.0.1 hotfix:
- Fixed language error
- Fixed secret settings error
## Version 4.0 release, "THE update":
### New features
- Added language auto detection.
- Added custom volume value.
- Added config files convertor.
- Translated setup to Spanish.
- Added auto activation/deactivation at a selected time.
- Added custom volume value.
- Added comments into macro.
- Macro works when phone is locked.
- Added API (reusable action blocks) for external macros.
- Added secret menu.
### Stability
- Added restart when load profile/config files.
- Even if you don't have a language, the macro will still work in english.
- Config files are now more stable.
- Config files now auto load to detect errors easily.
- Added options to ensure compatibility with al devices.
### Bug correction
- Fixed duplicated toast message in English and no message in Spanish.
- Fixed tons of bugs in beta, including:
  - Bool=55
  - Hour=true
  - Macro is lazy and doesn't works on weekends
  - Things using BluetoothVoiceCalls when they shouldn't
## Version 3.0:
- Added setup.
- Added profiles/settings files.
- Translated most of the macro to Spanish.
- Added toast message and vibration when activated/deactivated.
## Version 2.0:
- Fixed don't disturb still being activated bug.
- Added don't disturb modes.
- Added options to manually block every volume.
- Added action groups to help organize.
- Added long press qs tile to open settings.
## Version 1.1.1:
(this version never had a proper changelog and i don't remember exactly what changed)
- fixed a bug or something.
- adapted the macro for being published.
## Version 1.1:
(this version was never released or archived and i don't remember exactly what changed)
- Added blockAlarms.
## Version 1.0:
(this version was never released or archived and i don't remember exactly what i added)
- Added saveVol.
