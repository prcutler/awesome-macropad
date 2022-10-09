[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

> A curated list of awesome applications, macros, 3D printed cases, guides, and more for the [Adafruit CircuitPython rp2040 MacroPad](https://www.adafruit.com/product/5100).

## Contents

- [Contents](#contents)
- [MacroPad Hardware](#macropad-hardware)
- [MacroPad Guides](#macropad-guides)
- [Applications](#applications)
- [Games](#games)
- [Macros](#macros)
- [Other](#other)
- [3D Printed Cases](#3d-printed-cases)
- [Keycaps, Switches, and Plates](#keycaps-switches-and-plates)
- [Contributing](#contributing)
  - [Contribution Workflow Overview](#contribution-workflow-overview)
- [License & Trademarks](#license--trademarks)

## MacroPad Hardware

- [MacroPad Hardware on Adafruit.com](https://www.adafruit.com/?q=MacroPad&sort=BestMatch)
- [PCB files](https://github.com/adafruit/Adafruit-MacroPad-RP2040-PCB) in EagleCAD schematic format.
- [Stemma QT add-on boards from Adafruit](https://www.adafruit.com/?q=stemma+qt&sort=BestMatch)
- [Keycaps from Adafruit](https://www.adafruit.com/?q=keycaps&sort=BestMatch)

## MacroPad Guides

- [Getting Started with the Adafruit MacroPad](https://learn.adafruit.com/adafruit-MacroPad-rp2040) by Kattni Rembor
- [Programming MacroPad Hotkeys](https://learn.adafruit.com/MacroPad-hotkeys) by Phillip Burgess
- [Using the MacroPad for 2 Factor Authentication](https://learn.adafruit.com/MacroPad-2fa-totp-authentication-friend) by Carter Nelson
- [Dragon Drop: a CircuitPython Game for the MacroPad](https://learn.adafruit.com/dragon-drop-a-circuitpython-game-for-MacroPad) by Phillip Burgess
- [Control Home Assistant with the MacroPad](https://learn.adafruit.com/MacroPad-remote-procedure-calls-over-usb-to-control-home-assistant) by Melissa Leblanc-Williams
- [Ableton Live MacroPad Launcher](https://learn.adafruit.com/ableton-live-MacroPad-launcher) - by John Park
- [Minecraft Turbopad](https://learn.adafruit.com/minecraft-turbopad) by John Park
- [Scrambled Number Doorlock Security Keypad](https://learn.adafruit.com/scrambled-number-security-keypad) by Anne Barela
- [Install QMK on an Adafruit rp2040 MacroPad](https://learn.adafruit.com/using-qmk-on-rp2040-microcontrollers/adafruit-macropad-with-qmk) by Jeff Epler

## Applications

- [METAR Display and airport status](https://github.com/flyinactor91/metarpad) by flyinactor91
- [HP35 Calculator](https://github.com/funkfinger/adafruit-MacroPad-hp-35-calc) by funkfinger
- [MIDI Launchgrid](https://github.com/zoul0813/adafruit-launchgrid) by zoul0813
- [Open Broadcaster Software (OBS](https://github.com/djotaku/MacroPad_rp2040_hotkeys)) by djotaku
- [BeePad](https://github.com/trickeydan/beepad) by trickeydan
- [MacroPad-Sequencer](https://github.com/analogsketchbook/MacroPad-Sequencer) by analogsketchbook, an 8-step MIDI sequencer.
- [Multiple Timers](https://github.com/alpiepho/MacroPad-timers) by alpiepho, a timer application that implements a set of 12 independent timers.
- [BuildPad](https://github.com/willgorman/buildpad) by willgorman, a build automation tool for viewing and launching Jenkins jobs.
- [The Macropad 4chord MIDI](https://github.com/deckerego/Macropad_4chord_MIDI) is built to play simple chord progressions as a MIDI device on a rp2040 MacroPad by deckerego.
- [App Pad](https://github.com/kbaskett248/adafruit_macropad) An advanced port of Adafruit's Macropad application that adds switching macros by keys, OS-specific variants, double-tap support, and callback timers by kbaskett248.
- [MacroPad Automation and Application Detector](https://github.com/xhargh/MacropadApplicationDetector) is a Windows application that detects the currently active window and automatically switches to the appropriate set of macros for that application by xhargh.
- [PyCurrentWindow](https://github.com/astridos2go/PyCurrentWindow) automatically detects the focused application and automatically changes to the correct macros by astridos2go. (Windows only)

## Games

- [Macro Whack](https://github.com/coryflucas/macro-whack), a whack-a-mole style game for the MacroPad) by Cory Flucas
- [Tic-Tac-Toe](https://github.com/robotastic/MacroPad-tic-tac-toe) by robotastic
- [Game of Life](https://github.com/stelly-dev/game_of_life_adafruit_MacroPad) by stelly-dev
- [BrainMAX](https://github.com/omixen/MacroPad-math-game) by omixen, a math game.

## Macros

- [Macros for Blender, Safari, MIDI drum kit, generic number pad and Zoom](https://github.com/deckerego/MacroPad_Hotkeys) by deckerego
- [Vim Macros](https://github.com/CristinaSolana/adafruit-MacroPad-vim-macros) by Cristina Solana
- [Microsoft Teams, YouTube, Number Pad and Zoom](https://github.com/de-mon/ADA-MacroPad) by de-mon (Tested on Windows)
- [Final Fantasy XIV](https://github.com/Radical-Dreamr/adafruit_MacroPad_ffxiv) by Radical Dreamr
- [Generic Windows commands and KiCad](https://github.com/AlpenglowIndustries/Adafruit_MacroPad_Hotkeys) by AlpenglowIndustries
- [A funny vulnerability demonstration](https://github.com/prcutler/awesome-macropad) for unlocked and unattended Windows workstations by nihilexmachina.
- Macros including a [universal numpad, macOS media control keys, Zoom, and Webex macros](https://github.com/armccoy/macropad-rp2040-hotkeys) by armccoy
- macOS macros for [Evernote, Illustrator, Photoshop, Safari, Slack, Twitter, Zoom, and more](https://github.com/andypiper/ada-macropad) by andypiper.
- [Fusion360 macros](https://github.com/schneik80/Macropad-fusion) by schneik80.
- A collection of macros for Windows and macOS that includes a [universal numpad, macOS media control keys, Zoom, Webex, Discord, Sea of Thieves, and more](https://github.com/armccoy/macropad-rp2040-hotkeys) by armccoy.
- [YouTube macros for Microsoft Windows](https://github.com/DJDevon3/CircuitPython/blob/main/Macropad/macros/win-youtube.py) by DJDevon3

## Other

- [MicroPython Board Support](https://github.com/mp-extras/ADAFRUIT_MacroPad) by mp-extras
- Put your MacroPad to [sleep after 5 minutes](https://github.com/M-Eldin/Adafruit-MacroPad-RP2040-Sleep) by m-eldin
- [A refactored implementation](https://github.com/rossmoody/macropad-hotkeys) of the [MacroPad helper library](https://github.com/adafruit/Adafruit_CircuitPython_MacroPad) by rossmoody

## 3D Printed Cases

- [MacroPad RP2040 Case](https://www.thingiverse.com/thing:4910369) by Adafruit
- [Adafruit MacroPad Case](https://www.thingiverse.com/thing:4910369) for square keys by nlapenn.
- [MacroPad Print-In-Place Stand](https://www.thingiverse.com/thing:4907946) by Adafruit
- [Adafruit MacroPad Case for square keycaps](https://www.thingiverse.com/thing:4922256) by nlapenn.
- [Adafruit MacroPad Stand](https://www.thingiverse.com/thing:4900504) by Nyghtpoison.
- [MacroPad Bumper](https://www.thingiverse.com/thing:4926336) by jepler.
- [MacroPad LCD Wedge](https://www.thingiverse.com/thing:4947602) by srtnate.
- [MacroPad CAD 3Dconnexion Space Mouse](https://www.thingiverse.com/thing:4928292) by nmsr1196.
- [Merlin Case](https://www.thingiverse.com/thing:5118991) by ktanner
- [MacroPad RP2040 Snap Together Case](https://www.thingiverse.com/thing:4935552) by obe
- [MacroPad Notched Stand with holder and rotary cover](https://www.thingiverse.com/thing:4907845)
- [Six degree angle Macropad case](https://www.thingiverse.com/thing:5180029) by toasto
- [45 degree stand](https://www.thingiverse.com/thing:5209578) for the six degree case above by simonbugler
- [Macropad Case and Stand](https://www.thingiverse.com/thing:5185595) by PaintBallGamer
- [Macropad Notched Stand, Holder and Rotary Cover](https://www.thingiverse.com/thing:4907845) by nmsr1196
- [High Angle Macropad Stand](https://www.thingiverse.com/thing:4911282) by nmsr1196
- [Modular Mounting Bracket](https://www.thingiverse.com/thing:5191519) by GloryFish
- [MacroPad case with two extra rotary encoders and second display](https://www.thingiverse.com/thing:5413512)
- [Hinged MacroPad Kickstand](https://learn.adafruit.com/3d-printed-stand-for-macropad-rp2040) by the Ruiz brothers at Adafruit

## Keycaps, Switches, and Plates

- [CNC Milling Keycaps](https://www.thingiverse.com/thing:4941235) by Adafruit
- [MacroPad Braille Keycaps](https://www.thingiverse.com/thing:4913712) by Adafruit
- [Adafruit MacroPad Keycaps](https://www.thingiverse.com/thing:4933949) by jepler, featuring a keycap made of a single piece that allows the LEDs to shine through.
- [MacroPad switch plate](https://www.thingiverse.com/thing:4944190) by NascentMaker
- [MacroPad Upright Stand](https://www.thingiverse.com/thing:4911282) by nms1196
- [Nine degree stand](https://www.thingiverse.com/thing:4943775) to match Keychron keyboard angle by IcanCwhatUsay

## Contributing

Contributions and suggestions are always welcome! Please make pull requests from your own fork to modify Awesome MacroPad.

Imposter syndrome disclaimer: I want your help. No really, I do.

There might be a little voice inside that tells you you're not ready; that you need to do one more tutorial, or learn another framework, or write a few more blog posts before you can help me with this project.

I assure you, that's not the case.

The contribution guidelines below outline the process that you'll need to follow to get a patch merged. By making expectations and process explicit, I hope it will make it easier for you to contribute.

Thank you for contributing!

The workflow is similar to the one explained in detail here for CircuitPython: [Adafruit : Contribute to CircuitPython with Git and GitHub](https://learn.adafruit.com/contribute-to-circuitpython-with-git-and-github/overview).

### Contribution Workflow Overview

You can either add a thread to our [GitHub Discussions](https://github.com/prcutler/awesome-macropad/discussions) or send a pull request to add your MacroPad creation to the awesome-list.

If you would like to submit a pull request:

1. Fork [this repository](https://github.com/prcutler/awesome-MacroPad) on GitHub.
1. Clone the forked repo to your drive.
1. Add a remote using owner adafruit and the original URL.
1. Fetch the remote.
1. Merge main.
1. Create a branch.
1. Make a change.
1. Commit and push to your repo.
1. Create a pull request on the official repo.
1. Once accepted, repeat by merging from the official repo to your fork's master, and re-branch.

It's easier than it looks!  Have questions or need help?  You can [find me on the Adafruit Discord](https://discord.com/invite/5FBsBHU) as *prcutler*.  You can also find me on Twitter as *@prcutler*  - feel free to ask me for help, I'm more than happy to help.

## License & Trademarks

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

Last Updated: October 9th, 2022