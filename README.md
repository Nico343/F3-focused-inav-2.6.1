# P.S.A
This repo is maintained solely to use all the old and deprecated fc's that I obtained at a liquidation site. It will be archived as soon as the mcu on the last fc gives up the ghost. I plan on replacing the rest of the parts until that happens, after which I'll harvest the board for parts.

# INAV - navigation capable flight controller

## F3 based flight controllers

> STM32 F3 flight controllers like Omnibus F3 or SP Racing F3 are deprecated and soon they will reach the end of support in INAV. If you are still using F3 boards, please migrate to F4 or F7.

![INAV](http://static.rcgroups.net/forums/attachments/6/1/0/3/7/6/a9088858-102-inav.png)

## Features (that I care abt)

* Position Hold, Altitude Hold, Return To Home and (Basic) Missions
* Pixel style OSD as well as the default character based
* Telemetry: SmartPort, FPort, MAVlink, LTM
* Multiple sensor support: GPS, Pitot tube, sonar, lidar, temperature, ESC with BlHeli_32 telemetry
* SmartAudio and IRC Tramp VTX support
* DSHOT and Multishot ESCs
* Blackbox flight recorder logging
* Multi-color RGB LED Strip support
* Advanced gyro filtering: Matrix Filter and RPM filter
* Logic Conditions, Global Functions and Global Variables: you can program INAV with a GUI

For a list of features, changes and some discussion please review consult the releases [page](https://github.com/iNavFlight/inav/releases) and the documentation.

## Tools

### INAV Configurator compatible with [insert version]

Official tool for INAV can be downloaded [here](https://github.com/iNavFlight/inav-configurator/releases). It can be run on Windows, MacOS and Linux machines and standalone application.  

### INAV Blackbox Explorer

Tool for Blackbox logs analysis is available [here](https://github.com/iNavFlight/blackbox-log-viewer/releases)

### Telemetry screen for OpenTX

Users of FrSky Taranis X9 and Q X7 can use INAV Lua Telemetry screen created by @teckel12 . Software and installation instruction are available here: [https://github.com/iNavFlight/LuaTelemetry](https://github.com/iNavFlight/LuaTelemetry)

## Installation

See: https://github.com/iNavFlight/inav/blob/master/docs/Installation.md

## Documentation, support and learning resources
* [Fixed Wing Guide](docs/INAV_Fixed_Wing_Setup_Guide.pdf)
* [Autolaunch Guide](docs/INAV_Autolaunch.pdf)
* [Modes Guide](docs/INAV_Modes.pdf)
* [Wing Tuning Masterclass](docs/INAV_Wing_Tuning_Masterclass.pdf)
* [Official documentation](https://github.com/iNavFlight/inav/tree/master/docs)
* [Official Wiki](https://github.com/iNavFlight/inav/wiki)
* [INAV Official on Telegram](https://t.me/INAVFlight)
* [INAV Official on Facebook](https://www.facebook.com/groups/INAVOfficial)
* [RC Groups Support](https://www.rcgroups.com/forums/showthread.php?2495732-Cleanflight-iNav-(navigation-rewrite)-project)
* [Video series by Painless360](https://www.youtube.com/playlist?list=PLYsWjANuAm4qdXEGFSeUhOZ10-H8YTSnH)
* [Video series by Paweł Spychalski](https://www.youtube.com/playlist?list=PLOUQ8o2_nCLloACrA6f1_daCjhqY2x0fB)

## Contributing

Contributions are welcome and encouraged.


## INAV Releases
https://github.com/iNavFlight/inav/releases
