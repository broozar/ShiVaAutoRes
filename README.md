# ShiVaAutoRes
script that dynamically adjusts resolution based on fps

Do you want to maintain smooth framerates, but suffer from occasional fps dips? Let ShiVa take care of it by dynamically scaling the offscreen resolution, depending on how much resources are available. Simply drop the autores AI into your game's userAI stack!

This script comes in 2 versions for both ShiVa 1.9.2 and ShiVa 2.0. The _5x version has 5 coarsely grained resolution presets, the _x10 version has 10 finely grained ones. A demo game is included as well.

- You can customize the presets by editing the .setDetailLevel ( nLevel ) function.
- The thresholds are determined by this.nThresholdLower ( ) and this.nThresholdUpper ( ).
- Your target fps is set through this.nFPSTarget ( ).

The script is in an experimental stage, as ShiVa 1.9.2 does not support features like offscreen Anti Aliasing and ShiVa 2.0 beta currently has problems with its frame timing routines. Once exported, it should work well though.
