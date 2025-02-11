# 1. Umineko Mod Information - Please Read

--8<-- "umineko-project-recommendation.md"

This patch modifies the newest release of Umineko by MangaGamer, attempting to replicate the PS3 version of the game. It is compatible with both the [Steam](https://store.steampowered.com/bundle/5465/) and [DRM-free](https://www.mangagamer.com/product_list.php?opt=search&keyword=Umineko) versions of the game. It is **not** compatible with the old/original Japanese release of the game.

!!! tip "Just looking for the Downloads?"
    I **highly recommend** you read this wiki, so that you are prepared for any problems you may face. However if you wish to skip straight to the downloads, then use the [Cross Platform Installer](Umineko-Part-3a-Cross-Platform-Installer.md).

    Please continue reading below for the "full" instructions and information on the Umineko Mod.

!!! warning "This page contains important information you should read before installing. But here is the summary:"
    - If you have problems, check the [Troubleshooting](Umineko-Part-0-TroubleShooting-and-FAQ.md) page
    - If you have any existing save slots, and you **mod** or **upgrade** the game, your Save Slots WILL **randomly jump you somewhere in the game**. This can cause spoilers. Therefore, don't modify the game while you're in the middle of a chapter (read below for more details).
    - Computers with old or slow CPUs may have trouble running the game - [Poor Performance FAQ](Umineko-Part-0-TroubleShooting-and-FAQ.md#the-game-has-poor-performance-even-on-high-end-systems)
    - There is a mod settings menu in-game that you should look at at least once.
    - Updating the mod is only supported by re-installing (overwriting it)
    - Steam Sync is disabled by default. To enable it, run the `EnableSteamSync.bat` located in the game folder. See the 'Known Issues' section of this page for reasoning.
    - Please do not expect the same mod features as the Higurashi mod, as Umineko runs on an entirely different engine to Higurashi

You've read the page, right? Please proceed to [Part 2: Mod Options](Umineko-Mod-Options.md)

----

## Regarding Saves and Chapter Progress (Please Read)

Saves Slots are NOT compatible between the stock game and the patched game. Save slots between different versions of the patched game may not be compatible - they might skip you forwards / backwards in the script (the `0.u` file). For this reason,  **you should only update your script after completing an episode**.

Chapter Progress (whether you have completed a particular chapter or not) IS compatible between the stock and patched game. If you lose your chapter progress, use the 'Unlock' button next to each chapter to unlock it. Make sure not to miss out on the tea-parties or ???? if you use the unlock button.

## Updating from older versions

The installer now supports updating. To update a game:

- Select the game you want to update
- Select an existing installation
- The installer will show if any updates are available for that installation

As per the above, save files are not compatible when we update the game. Therefore, **you should only update your script after completing an episode**. If you update your game while in the middle of a chapter, you risk your save files to stop working, or your save files randomly jumping you forward in the game!

You can check for new updates on the Github releases page for each game:

- [Umineko Question Updates](https://github.com/07th-mod/umineko-question/releases)
- [Umineko Answer Updates](https://github.com/07th-mod/umineko-answer/releases)
- [Umineko Hane Updates](https://github.com/07th-mod/umineko-hane-ons/releases)
- [Umineko Tsubasa Updates](https://github.com/07th-mod/umineko-tsubasa-ons/releases)

## Mod Settings

You can change some settings from the in-game mod menu. While playing the game and the text is not animating, right click to bring up the menu. Click the right hand side options/menu button. This shows the options allowing you to change the music and voice volume.

<img src="https://07th-mod.com/wiki/Umineko/img/modmenu.webp">

## Known Issues

- Older computers and computers using integrated graphics may have problems with the mod:
  - The credits may not display at all (you will hear music, but only be shown a blank screen). We think this is because the 1080p credits images are too large for some computers to support, so the engine just does not display them at all. This usually affects users with (old) integrated graphics.
  - You may encounter performance issues with old/slow CPUs, as the engine does quite a bit of graphics rendering on the CPU.
- Steam Sync is disabled (See [the "Steam Sync doesn't work!" FAQ](Umineko-Part-0-TroubleShooting-and-FAQ.md#steam-sync-doesnt-work) if you wish to re-enable it)
- For the Question Arcs, the voice quality near the start of the game is poor for some characters (sounds like a phasing effect). The raw PS3 audio files have this problem as well, so I don't think we can fix this.

## Higurashi Mod Feature Comparison

You would be forgiven for assuming that Umineko runs on the same engine as Higurashi, and therefore our mods have the same features. However, the two games run entirely different engines, and as a result Umineko has less features.

Compared to Higurashi, the Umineko mod has far fewer features, such as:

- No support for Original/Ryukishi backgrounds (unless you play the Voice-only patch)
    - No support for Original/Ryukishi background stretching with the voice-only patch
- No support for lipsync
- You must select your sprite style during the install - you cannot switch it while the game is running like Higurashi
- For the Answer arcs only, you must select your ADV/NVL textbox style at install time - you cannot switch it while the game is running like Higurashi
- For the Question arcs, you *can* switch between ADV/NVL textbox style at runtime.

----

## **Please proceed to [Part 2: Mod Options](Umineko-Mod-Options.md)**
