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
- [Black Relegendable Plastic Keycaps for MX Compatible Switches](https://www.adafruit.com/product/5662)
- [MacroPadSynthPlug](https://github.com/todbot/macropadsynthplug) is a small board that plugs into the StemmaQT port and gives you TRS-A MIDI In and Audio line out and allows it to be a stand-alone MIDI synth by todbot.

## MacroPad Guides

- [Getting Started with the Adafruit MacroPad](https://learn.adafruit.com/adafruit-MacroPad-rp2040) by Kattni Rembor
- [Programming MacroPad Hotkeys](https://learn.adafruit.com/MacroPad-hotkeys) by Phillip Burgess
- [Disable Mass Storage so the MacroPad doesn't show up as a CIRCUITPY Drive](https://learn.adafruit.com/customizing-usb-devices-in-circuitpython/circuitpy-midi-serial#circuitpy-mass-storage-device-3096583)
- [Using the MacroPad for 2 Factor Authentication](https://learn.adafruit.com/MacroPad-2fa-totp-authentication-friend) by Carter Nelson
- [Dragon Drop: a CircuitPython Game for the MacroPad](https://learn.adafruit.com/dragon-drop-a-circuitpython-game-for-MacroPad) by Phillip Burgess
- [Control Home Assistant with the MacroPad](https://learn.adafruit.com/MacroPad-remote-procedure-calls-over-usb-to-control-home-assistant) by Melissa Leblanc-Williams
- [Ableton Live MacroPad Launcher](https://learn.adafruit.com/ableton-live-MacroPad-launcher) - by John Park
- [Minecraft Turbopad](https://learn.adafruit.com/minecraft-turbopad) by John Park
- [Scrambled Number Doorlock Security Keypad](https://learn.adafruit.com/scrambled-number-security-keypad) by Anne Barela
- [Install QMK on an Adafruit rp2040 MacroPad](https://learn.adafruit.com/using-qmk-on-rp2040-microcontrollers/adafruit-macropad-with-qmk) by Jeff Epler
- [Create a MIDI Controller using Arduino](https://www.hackster.io/Code_and_Make/arduino-powered-adafruit-macropad-rp2040-midi-controller-33f437) by Code_and_Make

## Applications

- [METAR Display and airport status](https://github.com/flyinactor91/metarpad) by flyinactor91
- [HP35 Calculator](https://github.com/funkfinger/adafruit-MacroPad-hp-35-calc) by funkfinger
- [MIDI Launchgrid](https://github.com/zoul0813/adafruit-launchgrid) by zoul0813
- [Open Broadcaster Software (OBS](https://github.com/djotaku/MacroPad_rp2040_hotkeys)) by djotaku
- [BeePad](https://github.com/trickeydan/beepad) by trickeydan
- [MacroPad-Sequencer](https://github.com/analogsketchbook/MacroPad-Sequencer) by analogsketchbook, an 8-step MIDI sequencer.
- [Multiple Timers](https://github.com/alpiepho/MacroPad-timers) by alpiepho, a timer application that implements a set of 12 independent timers.
- [BuildPad](https://github.com/willgorman/buildpad) by willgorman, a build automation tool for viewing and launching Jenkins jobs.
- [The MacroPad 4chord MIDI](https://github.com/deckerego/Macropad_4chord_MIDI) is built to play simple chord progressions as a MIDI device on a rp2040 MacroPad by deckerego. [Demonstration Video](https://www.youtube.com/watch?v=Ifc-n-RV3Ag)
- [App Pad](https://github.com/kbaskett248/adafruit_macropad) An advanced port of Adafruit's Macropad application that adds switching macros by keys, OS-specific variants, double-tap support, and callback timers by kbaskett248.
- [MacroPad Automation and Application Detector](https://github.com/xhargh/MacropadApplicationDetector) is a Windows application that detects the currently active window and automatically switches to the appropriate set of macros for that application by xhargh.
- [PyCurrentWindow](https://github.com/astridos2go/PyCurrentWindow) automatically detects the focused application and automatically changes to the correct macros by astridos2go. (Windows only)
- [Macro Hotkeys + Extensions](https://github.com/notnavindu/adafruit-macropad-hotkeys-with-extensions) Modified version of Adafruit's [Hotkeys](https://learn.adafruit.com/macropad-hotkeys) script. Includes a Pomodoro timer, Bongo Cat and support to write your own extensions. By notnavindu
- [Bongo Cat](https://github.com/christanaka/circuitpython-bongo) by christanaka
- [The MacroPad Jukebox](https://www.hackster.io/iotitlan/the-macropad-jukebox-3d2c99) by Carlos Olmos
- [MacroPad](https://github.com/mchilli/macropad) by MCHilli, manage your macros via a [WebUI](https://mchilli.github.io/macropad/).
- [Multiple Macropad Apps](https://github.com/ondras/macropad) by Ondřej Žára. Hotkey mappings for git, MIDI tones and/or chords, Elite:Dangerous game, DaVinci Resolve Color grading and more.
- [Manage your MacroPad via a WebUI](https://github.com/mchilli/macropad) by MCHilli
- [The MacropadPyDemo is a rewrite of the Arduino demo in CircuitPython](https://github.com/haugenmitch/MacropadPyDemo) by haugenmitch
- [MacroSynth](https://github.com/obtusecanadiangoose/macrosynth), a basic osc synthesizer using Todbot's [MacroPadSynthPlug](https://github.com/todbot/macropadsynthplug) by obtusecanadiangoose
- A [CHIP-8 emulator](https://github.com/cubbagesj/macropad_CHIP8) for the Adafruit MacroPad by cubbagesj
- The [T9 Predictive MacroPad](https://github.com/dupontgu/t9-macropad-circuitpython/tree/main) is available for a number of boards, [including the Adafruit MacroPad](https://github.com/dupontgu/t9-macropad-circuitpython/tree/main/fw) by Guy Dupont.
- Send MIDI commands to a loop pedal using the Adafruit MacroPad with [MIDILooper](https://github.com/dxinteractive/macropad-midilooper) by dxinteractive.

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
- [YouTube macros for Microsoft Windows](https://github.com/DJDevon3/My_Circuit_Python_Projects/blob/main/Boards/raspberrypi/Adafruit%20Macropad%20RP2040/Jons%20Macropad/macros/win-youtube.py) by DJDevon3
- [bettermacrosforadafruitmacropad](https://github.com/couchpotatochip21/bettermacrosforadafruitmacropad) adds the ability to show an image when changing macros by couchpotatochip21.
- [Simple macro profile for Kicad](https://github.com/corndog2000/RP2040-MACROPAD-KICAD) designed to keep one hand on the macropad and your other hand on your mouse when in the PCB editor.
- [Helldivers 2 Stratagem macros](https://adafruit-playground.com/u/squid_jpg/pages/easy-helldivers-ii-stratagem-macros-for-rp2040-macropad) by squid_jpg
- A [collection of macros for Windows and Linux by nylar357](https://github.com/nylar357/macropad_custom) including GitHub, Firefox, Sleep, Twitter, Vim, and more.

## Other

- [MicroPython Board Support](https://github.com/mp-extras/ADAFRUIT_MacroPad) by mp-extras
- Put your MacroPad to [sleep after 5 minutes](https://github.com/M-Eldin/Adafruit-MacroPad-RP2040-Sleep) by m-eldin
- [A refactored implementation](https://github.com/rossmoody/macropad-hotkeys) of the [MacroPad helper library](https://github.com/adafruit/Adafruit_CircuitPython_MacroPad) by rossmoody
- [Fruity Menu](https://github.com/greatest-gatsby/fruity_menu) is a library for building simple UI menus for CircuitPython powered devices, including the rp2040 MacroPad.
- [Mgogo](https://github.com/calbert1209/mgogo) is a library to convert Adafruit Macropad RP4020 settings to and from binary for read and write to the microcontroller's non-volatile memory.

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
- [Six degree angle MacroPad case](https://www.thingiverse.com/thing:5180029) by toasto
- [45 degree stand](https://www.thingiverse.com/thing:5209578) for the six degree case above by simonbugler
- [MacroPad Case and Stand](https://www.thingiverse.com/thing:5185595) by PaintBallGamer
- [MacroPad Notched Stand, Holder and Rotary Cover](https://www.thingiverse.com/thing:4907845) by nmsr1196
- [High Angle Macropad Stand](https://www.thingiverse.com/thing:4911282) by nmsr1196
- [Modular Mounting Bracket](https://www.thingiverse.com/thing:5191519) by GloryFish
- [MacroPad case with two extra rotary encoders and second display](https://www.thingiverse.com/thing:5413512)
- [Hinged MacroPad Kickstand](https://learn.adafruit.com/3d-printed-stand-for-macropad-rp2040) by the Ruiz brothers at Adafruit
- [MacroPad rp2040 Stand](https://www.thingiverse.com/thing:5460682) by miekush
- [MacroPad switch plate](https://www.printables.com/model/91048-adafruit-macropad-rs2040-switch-plate) by NascentMaker
- The [Key Tickler](https://www.printables.com/model/578085-key-tickler-adafruit-macropad) adds two 1x4 Stemma QT Neokeys and 3 Stemma QT rotary encoders, all enclosed in one case by jdireen
- [MacroPad Dock](https://www.printables.com/model/588896-macropad-dock) that also pairs with a [Stream Deck](https://www.printables.com/model/588891) by Spacejocks
- [Custom MacroPad Stand](https://www.printables.com/model/711899-adafruit-macropad-custom-stand) by carlos105420
- [MacroPad Travel Lid and Stand](https://www.printables.com/model/612936-adafruit-macropad-rp2040-travel-lid-and-stand) by LALAG
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

It's easier than it looks!  Have questions or need help?  You can [find me on the Adafruit Discord](https://discord.com/invite/5FBsBHU) as *Paul Cutler*.  You can also find me on Twitter as *@prcutler*  - feel free to ask me for help, I'm more than happy to help.

## License & Trademarks

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

Last Updated: November 22, 2024
