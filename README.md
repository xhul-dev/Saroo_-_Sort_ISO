# Saroo - Sort ISO
version 4\
xhul - 2024\
reports: https://github.com/xhul-dev/Saroo_-_Sort_ISO/issues

## description

Allows the content of the "ISO" directory to be sorted alphabetically in the Saroo menu.\
Useful if the used Saroo software version doesn't do that automatically.

## requirements

Windows, most probably all versions.

## instructions

Simply put "Saroo - Sort ISO.bat" on the micro SD card and execute it.\
The location doesn't matter, as long as it's not "\\SAROO\ISO\\" or below, but don't worry, the script detects if it is.\
Note that you have to re-execute the script each time you've added some stuff in "\\SAROO\ISO\\".

## known issues

- Windows Explorer can sometimes lock some directories, causing an error.\
More specifically, "\\SAROO\ISO\\" becomes locked for some commands, if any directory below it has been visible in the navigation pane.\
Anyway, if the script detects a lock, the execution pauses, allowing to close all open Explorer instances manually and retry.

## history

### version 4

- The execution now pauses when a lock is detected, allowing to manually close Explorer instances and retry.
- The performances have been increased significantly.
- Continued to improve error catching accuracy.
- The script no longer uses any temporary file.

### version 3

- Exclamation marks in file|directory names no longer cause errors.
- Personalised error messages are now displayed on all allocation table modification failures, unlikely scenarios included.

### version 2

- The script can now be executed from anywhere on the micro SD card, as long as it's not "\\SAROO\ISO\\" or below.
- Added a recommendation to close all Explorer instances before starting.
- The script now detects locked files and directories.
- Files|directories with the H|S attribute no longer cause errors.
- The script is now more coherent, the execution faster, and the error messages more explicit.

### version 1

- The script must be executed from the root of the micro SD card.
