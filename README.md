# PS5SX2 test builds

Test builds of **PS5SX2**, a port of the PCSX2 PlayStation 2 emulator to jailbroken PS5 consoles, made by
Spyros (Discord **sword.pdf**, X **@sword_pdf**) as a passion project.

These are builds for the testers. Every build shows a **TESTING** watermark and keeps detailed logs, so
problems can be found and fixed. Each build is a [release](../../releases): the release's zip holds the
two folders below plus `SETUP.txt`, the full setup guide.

## What's here

| Folder | Copy it to |
|---|---|
| `PPSA99203/` | `/data/homebrew/PPSA99203/` (the app) |
| `PCSX2/` | `/data/PCSX2/` (its data: shaders, the game database, switches, tested games' settings and patches) |

You also need a jailbroken PS5 with kstuff, the PS5SX2 Helper payload (from Spyros on Discord), your own
PS2 BIOS dumped from your own PS2, and your own games. **No BIOS, games or keys are included.**

Follow `SETUP.txt` for the first install: the whitelist line, the restart, and where the BIOS and the games go.

## Updating from an earlier test build

Close PS5SX2, then replace only `/data/homebrew/PPSA99203/eboot.bin`. Keep your `/data/PCSX2` folder: your
settings, memory cards and save states are in it.

## Reporting a problem

On the settings page (scan the QR code on the shelf), write a short note under "Report a problem", then tap
"Download logs" and post the file in Discord with the game's name and what happened.

## Licence and credits

PS5SX2, like PCSX2, is free software under the GNU General Public License, version 3 or later
(`COPYING.GPLv3`). Credits are in `NOTICE.txt`, third-party licences in `THIRD-PARTY-LICENSES.txt`.

"PlayStation", "PS2" and "PS5" are trademarks of Sony Interactive Entertainment. PS5SX2 is an independent
project, not affiliated with or endorsed by Sony Interactive Entertainment or the PCSX2 team.
