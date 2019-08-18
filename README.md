# xACARS
**This is still in early development, expect issues!**

ACARS system for phpVMS, powered by Python®.

**There is a critical X-Plane only bug where only ground speed and vertical speed are being loaded by the XPUIPC bridge.**

## What are the requirements?
Moved to [the wiki](https://github.com/slimit75/xACARS/wiki)

## Todo
Moved to [this GitHub project](https://github.com/slimit75/xACARS/projects/1)

## What do all of the files do?
Here is a list of what they do:

```
config.py - Handles reading the .ini files, and creates them if they do not exist
getBid.pyw - Gets a bid from the user
listAirlines.pyw - Lists airlines, and manages the creation and editing of them
login.pyw - Runs the login window
main.pyw - Runs the main window
posUpdateLoop.pyw - Bugs the program to refresh data in the input folder for fresh data from FSUIPC/XPUIPC
settings.pyw - Runs the settings window
track.pyw - Tracks the flight and updates its position.
web.py - Interfaces between the web and the program. Basically the requests module, except sends the headers without an extra field.
```
