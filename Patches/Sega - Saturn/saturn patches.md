# Saturn Hash Consistency Patches

Some Saturn patches are distributed using the Sega Saturn Patcher format.\
Unfortunately, Sega Saturn Patcher does not always output files with consistent hashes. Some SSP patches cause files inside the disc image to be timestamped, resulting in a different file hash every time the patch is applied, even with identical settings.

These alternative xdelta patches allow users to patch their disc images and get the same file hashes that are used in the DAT.


**Dezaemon 2 (Japan) - \[Special Edition v2025-05-06 by KoolFiller\]**

Original Patch: [Dezaemon 2 - Special Edition](https://segaxtreme.net/resources/dezaemon-2-special-edition.425/)\
Alternative Patch: [Dezaemon 2 (Japan) - [Special Edition v2025-05-06 by KoolFiller] (Track 1).xdelta](Dezaemon%202%20(Japan)%20-%20%5BSpecial%20Edition%20v2025-05-06%20by%20KoolFiller%5D%20(Track%201).xdelta?raw=true)

Instructions: Apply xdelta patch to a clean track 1 bin file.

**Doom (Japan) - \[Fix Patch v0.3.0 by fafling\]**

Original Patch: [Doom fix patch](https://segaxtreme.net/resources/doom-fix-patch.287/)\
Alternative Patch: [Doom (Japan) - [Fix Patch v0.3.0 by fafling] (Track 01).xdelta](Doom%20(Japan)%20-%20[Fix%20Patch%20v0.3.0%20by%20fafling]%20(Track%2001).xdelta?raw=true)

Instructions:\
Apply xdelta patch to a clean track 1 bin and set the patched bin file aside.\
Use the original SSP patch on a **clean** (not the patched bin file you just set aside) disc image.\
Use the xdelta patched track 1 bin in place of the track 1 bin created by SSP. So you should have tracks 2-18 from the SSP output and track 1 from the xdelta patch.

**NBA Jam - Tournament Edition (USA) - \[Walrus Edition v1.01 Public Beta by Malenko\]**

Original Patch: [NBA Jam TE Walrus Edition Hack](https://segaxtreme.net/resources/nba-jam-te-walrus-edition-hack.120/)\
Alternative Patch (track 1): [NBA Jam - Tournament Edition (USA) - [Walrus Edition v1.01 Public Beta by Malenko] (Track 1).xdelta](NBA%20Jam%20-%20Tournament%20Edition%20(USA)%20-%20%5BWalrus%20Edition%20v1.01%20Public%20Beta%20by%20Malenko%5D%20(Track%201).xdelta?raw=true)\
Alternative Patch (track 2): [NBA Jam - Tournament Edition (USA) - [Walrus Edition v1.01 Public Beta by Malenko] (Track 2).xdelta](NBA%20Jam%20-%20Tournament%20Edition%20(USA)%20-%20%5BWalrus%20Edition%20v1.01%20Public%20Beta%20by%20Malenko%5D%20(Track%202).xdelta?raw=true)

Instructions: Apply xdelta patches to clean track 1 and 2 bin files.
