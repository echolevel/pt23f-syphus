# ProTracker 2.3F
Continuation of the ProTracker 2 series for Amiga 68k, based on a disassembly and re-source of ProTracker 2.3D. \
Download: https://16-bits.org/PT23F.LHA \
Bootable ADF: https://16-bits.org/PT23F.ADF \
\
Some new changes worthy of a mention:
1) It has been fully bugfixed to work as expected on really fast Amigas (a ton of CPU-wait-routines have been replaced with scanline-wait and other safe delay routines)
2) It has been modified to fully support 128kB samples (all the old >64kB (>$FFFE) limits/bugs are gone, both in the player and GUI)
3) A ton of other bugs have been fixed

The asm syntax is AsmOne/AsmPro, and it may not be compatible with other assemblers.


## Syphus' fork notes:

This fork is so I can maintain a few customisations of my own.

They are:
* Custom UI and About screen
* Automatically displaying the About screen on startup, and allowing it to be shown again later (just a vanity feature!)
* Force default editskip to 0, rather than 1

They might soon include:
* Some MIDI tweaks/improvements
