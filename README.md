OldDays, NBXlite and SpawnHuman return numerous things from the old days of Minecraft Java Edition that were removed.
NBXlite is a fork of InsanityBringer's NoBiomesX
(Also known as the Nostalgia Project, feel free to check out the original post here: https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/1275124-1-0-0-no-biomes-x-very-dead-use-exalms-stuff)

SSPC is a fork of simo_415's Single Player Commands 3.2.2.
Everything in src/client/spc, bin/spc-* and bin-old/spc-* is licenced under GNU LGPLv3.

I'm just a random individual who wanted to archive these mods so they wouldn't be lost. If you want to set this up for whatever reason, then here's how ya' do it:

1. Download MCP. But may not worry my dear lad! Because somebody archived every official release of MCP here: https://archive.org/details/minecraftcoderpack

2. Decompile client using MCP.

3. Clone this repository to src-mods directory.

4. Go to src-mods/build and run deploy.sh script. (Or deploy.bat if you use Windows)

5. It is ready. You may now recompile client and start it.

To build a release, run make.sh script in the MCP directory. Not from src-mods/build! Resulting zips will be in reobf/result2.

build/ln.exe source code can be found here: https://github.com/neosmart/ln-win

Some clever lad supposedly fixed this source code. So if you're a Java developer, please use his source code instead: https://github.com/Spyro201/Minecraft-mods
