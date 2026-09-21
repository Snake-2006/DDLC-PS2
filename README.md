<div align="center">
  <h1>DDLC-PS2</h1>
</div>

- **DDLC-PS2** is a Doki Doki Literature Club port programmed in Javascript for the **PlayStation 2**
- **This port is unofficial and is not affiliated with Team Salvato. Please support the official game. You can download Doki Doki Literature Club at: https://ddlc.moe**
- **For the full experience of the game on the PC, Switch, and other consoles, please support Team Salvato and buy Doki Doki Literature Club Plus! Get the official console versions at: https://ddlc.plus**

## Usage:

### ELF Version
1. Download the `.zip`.
2. Extract all files to a USB drive in FAT32 format and insert it into the PlayStation 2 (modded with FreeMcBoot or Funtuna).
3. Use **uLaunchELF** (included in FreeMcBoot/Funtuna) to find the `DDLC.elf` file in the `mass:/` drive to start the game.

**Note for emulators:**
- In PCSX2, enable the **Enable Host Filesystem** option in Settings → Emulation, then open the `DDLC.elf` file.
- AetherSX2 does not allow loading ELF files.

## Script/Dialogue Modification

The script files can be modified using a Ren'Py-like way. These files are located in the `DDLC/src/scripts/{Language}/` folder.

## What is done?

- Language Selector
- On Screen Keyboard
- Dialog System
- Warning screen (mostly complete)
- Choice/Decision system
- First Chapter
- Start of Chapter 2 (only the first background and first dialogue for now)

## TODO:

- Complete the Title Screen
- Background and Scene Transitions
- Save System
- History System
- Poem Game
- The rest of the chapters

## Credits:

- [AthenaEnv](https://github.com/DanielSant0s/AthenaEnv) by Daniel Santos: A complete Javascript environment for creating homebrew applications and games on PlayStation 2.
- [DDLC-Love (PSP)](https://github.com/LukeZGD/DDLC-LOVE/) by LukeZGD: This port was the inspiration for the original PS2 version (dialogues were also extracted from here).
- [FontOutline](https://github.com/PauloDevv/Outline-in-Text-for-AthenaENV-PS2) by PauloDev: A class that adds an outline to texts in AthenaEnv.
- [d3vsaurio](https://github.com/d3vsaurio/DDLC-PS2-Source): Original author of the incomplete DDLC-PS2 base (v0.1.5). I started from that base. I tried to contact the original author but did not receive a response.
