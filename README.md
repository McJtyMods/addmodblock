# addmodblock for Minecraft 1.14 (with Forge)
This simple python script helps with adding source code and json for minecraft blocks. Note! By default this script should never overwrite a file but if it does so I'm not responsible (although I will be sorry). Make backups!

Before using this script you will have to configure it. Edit the script and modify the first part of the script to suit your needs.

This script supports generating both java and json for: block, tile entity, gui, container, blockstate json, model json, item json, recipe json and loot table json.

To use this run this script from within your mod root folder. If you then want to add a block without tile entity and gui you can do this:

# python addblock.py MyFancyBlock

This will add the block class and all the needed jsons.

If you want a tile entity you can do:

# python addblock.py MyFanceBlock --tile

If you want a gui as well (and a container) you can do:

# python addblock.py MyFancyBlock --gui

Note that in this case a tile entity will also be generated.

There is also a --force commandline option but be careful with this! It will forcefully overwrite all generated files ignoring what was there before!


The resulting code is by no means finished. It is up to you to make this a nice modded block. Have fun!


