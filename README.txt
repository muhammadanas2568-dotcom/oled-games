OLED Arcade OGS Game Pack
========================

All games in this pack are OGS scripts for the OGS interpreter in the user's ESP8266 OLED Arcade firmware.
They are not CHIP-8 ROMs.

Input conventions:
- jx < 0 / jx > 0: joystick horizontal movement (VRx)
- btn: SW button press
- Some games use SW as action/jump/fire or vertical step.

Files:
- index.txt: title|filename list
- 12 .ogs game scripts

Hosting:
Upload index.txt and every .ogs file to the same folder on a web host.
Set GAME_BASE_URL in the firmware to that folder URL ending in /.
The firmware's index parser expects lines in the format title|filename.ogs.

Compatibility note:
Scripts use only commands and expressions present in the OGS interpreter found in oled_arcade_esp8266_no_search.ino.
They have not been executed on the physical ESP8266 board; test one game first.
