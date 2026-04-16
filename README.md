# HackSet
HackSet is a series of DAT files (only one at the moment) cataloging file hashes for ROM hacks.

### **Using DAT files**

These DAT files are used by ROM managers like [RomVault](https://romvault.com/) and [clrmamepro](https://mamedev.emulab.it/clrmamepro/) to verify, rename, and organize ROMs. RomVault is highly recommended.

### **What HackSet is:**

- A collection of metadata for ROM hacks focused on file validation and preservation.\
*HackSet DATs contain filesize and hash data that can be used to identify and verify patched ROM files.*

- A way to organize ROM hacks.\
*HackSet DATs can be used to rename matching ROM files using filenames that give the name of the game, the name of the hack, the version number (or date of release) if available, and the name of the hack author (attribution is important!)*


### **What HackSet isn't:**

- Exhaustive.\
*HackSet aims to catalog ROM hacks that are either complete or fulfill their main purpose. Many hacks are excluded due to being incomplete, low effort, or too slight. There are more specifics below.*

- Concerned with fan translations.\
*HackSet does not catalog translation ROM hacks. The T-En collection DATs already do this quite well. The one case where you will find translated ROMs listed in HackSet is when other hacks are designed to be patched over a fan translation.*

- A way to obtain ROMs.\
*HackSet only contains information about patched ROM files. It does NOT contain any ROMs or information on where to find them, and I will not help you find them.*

## **The current state of HackSet**

The first HackSet DAT file was released on 4/13/2026 and covers the Sony PlayStation.
I've started on the Sega Saturn DAT, and currently the plan is to create a Nintendo 64 DAT after the Saturn DAT is finished.
As of right now I am working on this project alone, but if the scope of the project expands to include more systems I will probably start looking for contributors.

**HackSet updates**

I plan to update HackSet once a week when there is something new to be added, with additional updates during the week depending on time and need.

**HackSet selection process**

HackSet is not an attempt to catalog every ROM hack. The goal is to select hacks that are complete, or that fulfill their primary purpose while still in active development. Quality is not largely not considered. This isn't a curated list of the "best" hacks; it is a collection of any hacks that meet the basic criteria.

Incomplete hacks are excluded unless there is a compelling reason for inclusion (historical relevance as an example).\
Low effort hacks are excluded - "Look it's Super Mario Bros. but I put in a slur." - No thanks.\
Trainers are excluded, as are most things that could be done with a simple code for a cheat device.\
PAL to NTSC / 60hz patches are only included if the game was a PAL exclusive or PAL and Japan exclusive.\
Translations are excluded unless the translation patch is used in combination with a compatible hack.\
Undubs are included as long as they don't cause any significant audio issues.\

You can find some real examples in examples.md

**Multiple compatible hacks**

When a game has multiple hacks that are compatible with each other, I create multiple dat entries for the game with different combinations of hacks. I don't create an entry for every permutation, but I try to choose combinations that make sense. All hacks will still have an entry with only that patch applied


More documentation coming soon