# OctoPrint PSU Control With Autoconnect feature

This is just an old working version of Octoprint PSU Control that implemented the requested autoconnect feature. Once it turns on the PSU it connects to the printer automatically.
It is entirely based on the code by Shawn Bruce at https://github.com/kantlivelong/OctoPrint-PSUControl with just this difference in the code provided by chriswal on this feature request: https://github.com/kantlivelong/OctoPrint-PSUControl/pull/101

I basically wanted that feature but Shawn did not want to add it (respectable personal preferences) so I added it myself, still all credit to Shawn and chriswal for their wonderful work :)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

This OctoPrint plugin controls an ATX/AUX power supply to help reduce power consumption and noise when the printer is not in use.

Power supply can be automatically switched on when user specified commands are sent to the printer and/or switched off when idle.

Supports Commands (G-Code or System) or GPIO to switch power supply on/off.

![PSUControl](psucontrol_navbar_settings.png?raw=true)
 
![PSUControl](psucontrol_power_on_options.png?raw=true)
 
## Setup
Install the plugin using Plugin Manager from Settings
 
## Settings
See the [Wiki](https://github.com/kantlivelong/OctoPrint-PSUControl/wiki/Settings)
 
## Troubleshooting
See the [Wiki](https://github.com/kantlivelong/OctoPrint-PSUControl/wiki/Troubleshooting)

## API
See the [Wiki](https://github.com/kantlivelong/OctoPrint-PSUControl/wiki/API)

## Support
Help can be found at the [OctoPrint Community Forums](https://community.octoprint.org)

## Feature Requests
[![Feature Requests](https://feathub.com/kantlivelong/OctoPrint-PSUControl?format=svg)](https://feathub.com/kantlivelong/OctoPrint-PSUControl)
