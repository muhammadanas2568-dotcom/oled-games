OLED Arcade CHIP-8 Homebrew Pack (v2)

These are original, tiny CHIP-8 homebrew prototypes created for the ESP8266 OLED Arcade emulator.
They are valid CHIP-8 bytecode programs, unlike the previous 45-byte placeholder files.
Each program draws a player sprite and target, supports horizontal movement using CHIP-8 keys 4/6,
and uses CHIP-8 key 5 as an action to relocate the target. Reaching the target's horizontal
position relocates it. The 12 entries have different sprites and starting positions; they are
simple prototypes sharing a basic catch-target mechanic, NOT 12 distinct full commercial games.

Controls for the supplied emulator:
- VRx left: key 4
- VRx right: key 6
- SW press: key 5 (action)
- Long-press SW may exit the emulator, as implemented in the supplied Arduino code.

Files:
- *.ch8: ROMs
- index.txt: title|filename|465 records for the downloader
- README.txt: this file

Note: ROMs were checked for valid bytecode structure and label/address assembly during generation,
but were not tested on physical ESP8266/OLED hardware. These prototypes intentionally avoid
requiring vertical keypad keys because the supplied emulator maps only left/right/action.
