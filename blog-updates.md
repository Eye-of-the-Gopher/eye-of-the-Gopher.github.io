### Project Inception - Aug 18, 2025
Initial focus on PAK file parsing and LCW compression algorithms.

Successfully implemented PAK file extraction.

### LCW decompression - Aug 19, 2025
Implemented basic harness and [Westwood LCW](https://moddingwiki.shikadi.net/wiki/Westwood_LCW) decoder. Commands 1 and 4

### LCW decompression done  - Aug 20, 2025
Remaining LCW commands. Example decoded file ![Dungeons&Dragons](images/DAND.CMP.png)

### Loading palettes done  - Aug 21, 2025
Added support to load palettes and use them while decoding CMP files. Example decoded file ![Dungeons&Dragons](images/dand-palette.png)

### Extracted sprite sheets and parsed out Audio files  - Aug 22, 2025
- Found one file (the title screen) is treated specially and doesn't decompress normally. Probably due to space being needed for the menu.
- Was able to extract the sprite sheets using the CMP decoder itself. Here's an example ![Chargen](images/CHARGENA.CPS.png)
- Able to play Adlib sounds from the extracted assets using [Adplay](https://github.com/adplug/adplay-unix)
- Probably going to work with the maps next

### Interpreted maps  - Aug 23, 2025
Was able to read out a map file and make sense of it. [This](https://www.oldgames.sk/dungeon-mapper/map.php?map=20) is the map of the first level. Here is my visualization ![Level One](images/level1map.png)

