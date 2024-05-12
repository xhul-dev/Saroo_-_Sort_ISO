# Saroo - Sort ISO
version 6\
xhul - 2024\
download: https://github.com/xhul-dev/Saroo_-_Sort_ISO/releases
\
reports: https://github.com/xhul-dev/Saroo_-_Sort_ISO/issues

## description

Allows the content of the "ISO" directory to be sorted alphabetically in the Saroo menu.\
Useful if the used Saroo software version doesn't do that automatically.

## requirements

Windows.\
Pre-xp versions weren't tested and are not exactly recommended.

## instructions

Simply put the "Saroo - Sort ISO" directory on the micro SD card and execute "Saroo - Sort ISO.bat".\
The location doesn't matter, as long as it's not "\SAROO\ISO\\" or below, but don't worry, the script detects if it is.\
Note that you have to re-execute the script each time you've added some stuff in "\SAROO\ISO\\".

## history

### version 6

- It's now required to have the whole "Saroo - Sort ISO" directory on the micro SD card, not just "Saroo - Sort ISO.bat".
- The script now closes all existing Explorer windows automatically to try to unlock "\SAROO\ISO\\", though it shows a warning before doing so.
- The script now checks if command extensions are either unavailable or obsolete.
- Some optimisation here and there.

### version 5

- Added a new user choice input upon success, allowing to view the sort order before exiting.
- Fixed a compatibility issue caused by "if [not] exist object" and "if [not] exist object\\" being interpreted identically on some systems.
- Added compatibility with the "windir" environment variable, in case "SystemRoot" isn't defined.

### version 4

- The execution now pauses when a lock is detected, allowing to manually close Explorer instances and retry.
- The performances have been increased significantly.
- Continued to improve error catching accuracy.
- The script no longer uses any temporary file.

### version 3

- Exclamation marks in file|directory names no longer cause errors.
- Personalised error messages are now displayed on all allocation table modification failures, unlikely scenarios included.

### version 2

- The script can now be executed from anywhere on the micro SD card, as long as it's not "\SAROO\ISO\\" or below.
- Added a recommendation to close all Explorer instances before starting.
- The script now detects locked files and directories.
- Files|directories with the H|S attribute no longer cause errors.
- The script is now more coherent, the execution faster, and the error messages more explicit.

### version 1

- The script must be executed from the root of the micro SD card.

## credits

- Nico_Kamui from https://darius-saturn.com/forum/ - bug reports
- Nir Sofer - nircmd
- czapa86 from https://github.com/ - bug report
- everybody who contributed to the knowledge found on https://ss64.com/nt/
- everybody who contributed to the knowledge found on https://stackoverflow.com/
