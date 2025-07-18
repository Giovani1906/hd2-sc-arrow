# hd2-sc-arrow

![Thumbnail](thumbnail.png)

Helldivers 2 mod that puts arrows above Super Credit piles.

<a href="https://github.com/Giovani1906/hd2-sc-arrow/releases/latest"><img src="https://img.shields.io/badge/Download-Latest-purple?style=for-the-badge&logo=github&logoSize=auto" alt="Latest release"></a>

## FAQ
### How do I install the mod?
#### Using HD2ModManager
1. Download the latest `HD2ModManager` from [here](https://www.nexusmods.com/helldivers2/mods/109).
2. Download the latest mod from the icon above.
3. Unpack the mod manager in whatever location you like and launch it.
4. Press the `Add` button, select downloaded mod and you should have it pop up in the mod list with the name "Super Credit Arrows" and the thumbnail image being the one shown above.
5. Click on the box left to the trash can and make sure it's checked.
6. Press `Deploy`

Now the mod should work the next time you launch the game.

#### Doing it manually
1. Download the latest mod from the icon above.
2. Open the archive.
3. Pick whatever appearance you'd like from the folders inside the archive.  
   For example, I'm going to use `purple/glow`.
4. Drag the patch files to the `data` folder where the game is installed.

Now the mod should work the next time you launch the game.  
> [!NOTE]  
> This option assumes you're not using any other mods.  
> If you're using other mods, use the option above or manage them manually.

### How do I see the arrows from afar?
You have to do the following:
1. Press `Win+R`.
2. Go to `%appdata%/Arrowhead/Helldivers2`.
3. Open `user_settings.config` with your favourite text editor.
4. Search for `lod_selection_multiplier` variable and set it to `10.5`.
5. Save the file.
6. Right click `user_settings.config`, go to `Properties` and enable the **Read-only** attribute.  
Otherwise, the game will reset the variable to a lower value.

> [!WARNING]  
> **Doing this will tank your FPS.**  
> So after you're done farming you should revert the `lod_selection_multiplier` back to stock.  
> Or disable the `Read-only` attribute from the `user_settings.config` file.
