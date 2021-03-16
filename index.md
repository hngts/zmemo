# zmemo
Zenity based memo/notes

Simple and basic, yet very usable and non-bloated memos for Your every day life.

## Requirements: 

1. Linux operating system
2. **zenity** and **libnotify** (*libnotify: notify-send* command) packages installed

## Installation instructions:

1. Copy and paste all the contents of the zmemo file into your `~/bin` directory.
2. Make script executable `chmod +x ~/bin/zmemo`
3. Run `zmemo new` from Your command line or Your favorite search applet (eg: ALT+F2) capable of executing shell scripts

## Usage:

- *zmemo* reckognizes two arguments: **new** or **list**
- `zmemo new` will create new memo file
- `zmemo list` will show a list of already created memo's

## Good to know:

- *zmemo* allows only one working, launched instance 
- *zmemo* files are ordinary plain text files stored inside `~/.local/share/zmemo`.
- When You add new *zmemo file*, blank spaces in file name will be replaced with underscore `_`. 

## Configuration:

In order to change ...

- Default *width* and *height* of dialog box window, see lines **24** and **25** 
- Default *zmemo* directory for Your *zmemo's*, line **23**

... inside `~/bin/zmemo` it self. 

### Application launcher item

If You want (KDE users for example) to *click* and open (instead of typing command) memo's, create new desktop file (eg:`/usr/share/applications/zmemo.desktop`) and paste contents from `zmemo.desktop`. You may want to uncomment `#Icon=` line and provide some. 
