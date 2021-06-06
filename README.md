# Resource Pack Credits datapack

This Minecraft datapack was created as a simple way give credit to the authors of various resource packs distributed in a server resource pack, via an advancement page.

It is compliant with Minecraft Datapack conventions. That is, this data pack in its unmodified form is compatible with any datapacks and resource packs, and contains a set of advancements containing the author and title. If you do not want these advancements, simply delete the 'global' and 'resourcepackcredits' namespace folders.

<br>
To add a resourcepack to the advancements page, create a new folder with the resource pack's name. This is your namespace. Within that folder, create another called advancements. Within the advancements folder, create two json files, one with the name of the author or group that created it, and the other with the name of the resource pack. The content inside should be the same as the files found in the 'templates/advancements' folder, with content replacing the text enclosed by '< >' respectively.

If you want to add multiple resource pack listings, and they were made by one person or group, you can simplify the process by following the steps above, but with the following two modifications:
1. Name the namespace folder the same as the name of the person or group who made the resource packs.
2. Create one json file per resource pack, each following the template file the same way as described above.

<hr>

I, iijj22gg, claim all rights to this datapack, except those revoked by the "Creative Commons Zero v1.0 Universal" license as described in the LICENSE file. <br> That is, suggestions are welcome.
