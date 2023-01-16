All solved strings courtesy of Monkeypolice188

Installation:

Drag and drop the .nametable files (not the .txts!) in any Grand Theft Auto V .RPF (preferrably mods\update\update.rpf\x64\audio\config). I recommend using CodeWalker RPF Explorer (Grab CodeWalker from the #releases channel of their Discord server: https://discord.gg/codewalker) to do this, as you can also use RPF Explorer to view, browse and edit audio data files in GTA V.

Audio data files (.rel audio) in update.rpf\x64\audio\config should now have a large amount of hashes solved, and many .awc (audio wave containers) files will have solved .wav file names within them, making identifying specifics much easier.

The .nametable files are spread across several different files, one for each of the base game audio.dat.rel files, but there are also several unique nametables for your convenience:
- ivsounds.nametable - all of the audio strings from GTA IV and EFLC. Although these do not make much of a difference to V, there are many audio entries which have been copied over from IV to V during its development.
- filenames.nametable - all of the solved strings for .wav files within .awc files (audio containers). I update this with every DLC too, since every new DLC's audio files will be hashed, unlike DLC audio .rel files which have their own nametables.
- mlorooms.nametable - all of the room names for MLO interiors. MLO names are used in the audio data to identify the rooms where portals change sound behavior.
- scriptnames.nametable - all ScriptName entries for sounds.dat. These are the names used by script files to load specific sounds from a soundset.
- parameters.nametable - all variable/parameters/"rtpc"s (real time parameter controls) names which are used by a variety of sound types, including maths and parameter transform types, to manipulate sound behavior. These are often found in Parameter fields.
- synthpresets.nametable - all synth preset variables, used by synths in optamp.dat to assign input behavior to a synth, manipulating them on the fly.

Feel free to make a clone/fork of my repo and publish any new additions you find to a pull-request. I regularly update the main repository with any new additions I find, so don't be afraid to make a PR, even if it's just a couple of new strings!
