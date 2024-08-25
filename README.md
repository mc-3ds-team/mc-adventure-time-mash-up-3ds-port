# Minecraft Adventure Time Mash-Up - Minecraft: New Nintendo 3DS Edition Port
Adventure Time Mash-Up port to Minecraft: New Nintendo 3DS Edition.

![Promo image](https://github.com/susbaconhairman/mc-adventure-time-mash-up-3ds-port/blob/main/images/promo.png?raw=true)

This is a work in progress.

## Progress

- **Terrain** - Almost done
- **Items** - Almost done
- **Skins** - Will not do due to current limitations.
- **Audio** - Not done
- **World** - Will not do until a world conversion tool comes out.
- **GUI** - Half-way done
- **Panorama** - Done
- **Entities** - Done
- **Environment** - Done
- **Colormap** - Done
- **Misc - Models, Painting, Particles, Flame Atlas** - Done

## Screenshots
![Menu](https://github.com/susbaconhairman/mc-adventure-time-mash-up-3ds-port/blob/main/images/menu.png?raw=true)

## Limitations/Changes

There are a lot of limitations, because the way Minecraft 3DS renders things and has stuff set up is different than anything else (sucks).

- Boss progress bar is cut off at the top because the atlas for it dosesn't have enough space for the full thing. I have also stretched it out to span the entire length of the bar in the atlas.
- Bubbles in spritesheet.3dst were too big, so the individual bubbles were moved around a bit to fit the space, and some had pixels added/removed. Nothing was resized.
- Mechanism sprite in spritesheet.3dst had to be modified and resized to fit the space specified for it in the sheet.
- Hotbar selection in spritesheet.3dst was modified to properly display in game.
- Eyes, mouth, and keyhole in achievement lock icon were shifted because the lock was resized to 48x48.
- Most images in achievements.3dst came from the Wii U Edition's achievements.
- Some of the images in achievements.3dst are resized older images of themselves in the 3DS's achievements as they didnt exist anywhere else.
- Hotbar and inventory backgrounds are the same sprite in spritesheets.3dst, so the Adventure Time Mash-Up hotbar can't be in the game.
- Scrollbar has to be a rectangle in the spritesheet, so it can't be round, like in Legacy.
- For some reason, the slider button and bottom screen inventory, crafting, and pasue buttons have the same sprite in the sprietsheet. So the slider button is not the one from the pack, it is darker, so those menu buttons can be darker.

## Credits

**Tools used:**
- [Ohana 3DS](https://gbatemp.net/attachments/ohana3ds-zip.99223/) - Converting images to 3DST
- [MC 3DS Texture Maker](https://github.com/STBrian/MC3DS-Texture-Maker) - Bulk conversions for making Blocks and Items (atlases)
- [Pinetools Bulk Image Flipper](https://pinetools.com/bulk-batch-flip-image) - Vertically flipping images for converting to 3DST
- [Paint.NET](https://www.getpaint.net/) - Converting TGA to PNG
- [The Pillager Bay Torrent](https://archive.org/details/minecraft-marketplace) - Torrent where I got the Adventure Time Mash-Up files from
- [HackingToolkit9DS](https://github.com/Asia81/HackingToolkit9DS) - For extracting CIAs
- [hShop](https://hshop.erista.me) - Wonderful place where I got Minecraft 3DS CIAs
- [Piskel](https://piskelapp.com) - Image manipulation
- [Pixlr](https://pixlr.com/x) - Image manipulation
- [Redketchup](https://redketchup.io) - (Bulk) Image compression, cropping, and resizing.
- ["How to Make Your Own Menu Panorama! (Bedrock Edition)" - YouTube](https://www.youtube.com/watch?v=fOLRL8HNHuA) - How to make panoramas (for the nether)
- [MC3DS-BJSON-Editor](https://github.com/STBrian/MC3DS-BJSON-Editor)
- [Cemu](https://cemu.info/) - Used for dumping textures and as a reference for the port
- [Citra](https://github.com/PabloMK7/citra) - 3DS emulator, used for testing
- [Wii U Downloader](https://github.com/Xpl0itU/WiiUDownloader) - Got Minecraft Wii U Edition from here

**Names**
- The Pillager Bay
- Cracko298
- Nawrek
- Watermelon
- ThorMode9
- STBrian
- DeadSkullzJr
- czx
- The Minecraft 3DS Community
- Minecraft Wiki
- Other Ocean
- 4J Studios
- Mojang
- TheRustico
