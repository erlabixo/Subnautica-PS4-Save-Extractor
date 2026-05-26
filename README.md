# Subnautica-PS4-Save-Extractor
QuickBMS script that extracts the files of a Subnautica PS4 savefile after it has been decrypted.

<img width="1920" height="1080" alt="Subnautica_lbN3fHUp88" src="https://github.com/user-attachments/assets/5664b2d3-d5e4-43bf-8c32-fd908d601dbf" />

## How to Use the Script
1. Download and extract [QuickBMS](https://github.com/LittleBigBug/QuickBMS)
2. Download Subnautica-PS4-Save-Extractor.bms to the same folder as QuickBMS
3. Place the PS4 save (after decrypted) in the same folder. It's usually called slot0000.blb or similar.
4. Open a command line in the folder and run "QuickBMS Subnautica-PS4-Save-Extractor.bms [savefile] [Output Directory]"

## What to do with the Output
The output directory will contain all the files of that save.  
You should rename the directory to something like slot0000 and then you can move it to where your PC saves are located.  
If you already have a slot0000 directory and you don't want to overwrite your existing PC save, call it slot0010 or similar.

## A couple of notes
* It's probably a good idea to update the game to the latest version in your PS4 and then save again, so the format of the saves is the latest. 
That being said, I tested it with a save I had from 2021 and it seemed to work fine.
* The files in the directory "CellsCache" are all extracted as hundreds or even thousands of *.bin files. In the PC saves, these files are grouped and compressed in several ZIP files.  
Once you start the game, it will detect the new save and it will group and compress these files. You will see a message that says "Updating save data" with a progress bar.
* I only had one save in my PS4 from 2021. I tested the script with that save and with the updated version (I loaded and saved again). These 2 are all the samples I had for testing, I can't guarantee the script will work in every case.
* I don't have Below Zero in PS4, so I don't know if this script would work for that game's saves.
* This script won't compress the PC saves to be able to encrypt them and use them in a PS4, it's one way only.

## How to decrypt the PS4 saves
I won't go into detail about this. There are a few methods, I tested a couple. The one I tested more recently which is the one I would recommend is using the garlicsaves website. Really easy and straight forward.
