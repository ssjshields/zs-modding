![zsimage](https://github.com/ssjshields/zs-modding/assets/88489119/4fd30cc1-915a-4e9f-aa67-34725afd8235)

[ZS Official Discord](https://discord.gg/sievert)

[ZS Nexus Mods](https://www.nexusmods.com/zerosievert)

[ZS Modding Wiki](https://zero-sievert.fandom.com/wiki/Modding)

&nbsp;

## Mod managers

**Recommended:** [ModOrganizer2](https://github.com/ModOrganizer2/modorganizer) & [MO2 ZS plugin](https://www.nexusmods.com/site/mods/617?tab=description)

**Alternative:** [Vortex](https://www.nexusmods.com/about/vortex/)

> Always follow mod author's installation instructions

&nbsp;

## Editing resources
**Audio:** [Audacity](https://www.audacityteam.org/) & [Foobar](https://www.foobar2000.org/)

**Coding:** [Notepad++](https://notepad-plus-plus.org/) & [Visual Studio Code](https://code.visualstudio.com/)

**Fonts:** [FontForge](https://fontforge.org/en-US/) & [Google Fonts](https://fonts.google.com/)
> ZERO Sievert uses [Munro](https://www.fontspace.com/munro-font-f14903)

**Sprites:** [Photopea](https://www.photopea.com/), [Gimp](https://www.gimp.org/) or [Aseprite](https://www.aseprite.org)

&nbsp;

## Directories
**Assets**: `ZERO Sievert\data.win`
> Fonts, scripts, sounds, sprites and strings

**Gamedata**: `ZERO Sievert\ZS_vanilla`
> Load order, values and descriptions for weapons, items, npcs

**Savedata:** `%localappdata%\ZERO_Sievert`
> Save slots, game settings and backups

&nbsp;

## Creating data.win mods
**Required:** [UndertaleModTool](https://github.com/krzys-h/UndertaleModTool)

**Recommended:** [Custom Sprite Framework](https://www.nexusmods.com/zerosievert/mods/16)

**1.** Open `data.win` with UMT

> Associate UMT with the `.win` filetype for ease of access

![image](https://github.com/ssjshields/zs-modding/assets/88489119/23ac2745-d6b6-4147-992b-25479d6e88a0)

**2.** Modify, import or export desired content

**3.** Save as new `data.win`, add to zip archive

> Do not redistribute `data.win` files, instead create xdelta patches

&nbsp;

## Creating XDelta patches
**Required:** [DeltaPatcher](https://github.com/marco-calautti/DeltaPatcher)

**1.** Set the "Original file" path to a clean `data.win`

**2.** Set the "Modified file" path to the modded `data.win` 

**3.** Set the "XDelta patch" path to the desired output location

> It is recommended to add comments to the patch description

![image](https://github.com/ssjshields/zs-modding/assets/88489119/afd07b1b-b683-4fa0-ac5c-f3d1d11ac6b6)

&nbsp;

## Applying XDelta patches
**Required:** [DeltaPatcher](https://github.com/marco-calautti/DeltaPatcher)

**1.** Set the "Original file:" path to a clean `data.win`

**2.** Set the "XDelta patch:" path as the `.xdelta` (mod)

**3.** Click "Apply patch"

![applying_patch](https://github.com/ssjshields/zs-modding/assets/88489119/5c0553f5-b883-4e34-890e-fa5c43d78cd3)

&nbsp;

## Creating JSON mods
**1.** Modify `.json` files using desired text editor

**2.** Create a new folder with your mod name as the title `ModName\ZS_vanilla\gamedata`

**3.** Add modified `.json` files to the mod's `gamedata` folder

[Packaged folder structure example](https://github.com/ssjshields/zs-modding/blob/main/example_json_mod.zip)

&nbsp;

## Merging JSON mods
**Required:** [WinMerge](https://winmerge.org/?lang=en) or similar difference check software

**1.** Compare up to three `.json` files (left, middle and right view.)

![image](https://github.com/ssjshields/zs-modding/assets/88489119/cc9311f2-f755-4472-94ae-1825df1c0501)

**2.** Right click the highlighted difference and copy the code into the desired file

> Repeat this process for each desired difference, merging all desired changes into a single file

> Due to current limitations, ZERO Siervert can only load one of each `.json` at a time

![image](https://github.com/ssjshields/zs-modding/assets/88489119/dec67afc-b4cd-4b01-b624-8ed98610b8f2)

![image](https://github.com/ssjshields/zs-modding/assets/88489119/d4149992-81d1-4f0d-be76-7518cb51f48f)

![image](https://github.com/ssjshields/zs-modding/assets/88489119/2e86bbb9-8c27-4762-8601-ff77dfb5b05e)

**3.** Save and overwrite original files in desired mod

