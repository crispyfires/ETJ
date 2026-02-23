<a id="top"></a>
# Valdacil's Recommendations for Players

## Table of Contents
< [Back to Readme](/README.md)<BR>
< [ETJ Gameplay Guide](/Gameplay%20Guide.md)<BR>
< [Valdacil's Guides](/ETJ%20Valdacil%20Guides/Readme.md)
1. [First Steps](#first-steps)
2. [Getting Support](#getting-support)
3. [Advanced: Saving Settings During Updates](#advanced-saving-settings-during-updates)

## First Steps

The nice thing about Wabbajack lists is that users don't have to figure out how to build a list or worry about mod conflict resolution.  But often there are so many mods in the list that users aren't familiar with all the mods affecting their game.  It is therefore the responsibility of the user to gain sufficient familiarity to play the curated version of Skyrim and to understand what is a modded experience vs. something that isn't working as intended.

### Review the ETJ Readme and GamePlay Guides

First step should be to fully read the [ETJ Readme](/README.md) and [Gamplay Guide](/Gameplay%20Guide.md).  These contain baseline information about important mods included in the list and tips on how to play some of those mods.  These are good items to peruse while Wabbajack is downloading the list.

### ETJ Discord

After reviewing the ETJ Readme and Gameplay Guide, further support can be found at the [ETJ Discord](https://discord.gg/EeKaKE4s).  We have cultivated a very chill and helpful community.  There you will find Announcements regarding list updates, a Support channel, and a place to share your screenshots and character stories.

### Valdacil's Guides

After checking out the Discord, you may find more information in the guides written or curated by me (Valdacil)... which is probably how you found this page.

### Review MO2 Mods

Once the list is fully downloaded via Wabbajack, it can be a good idea to look through MO2 to review the mods present.  Specifically, check mods under the Gameplay Changes section so you are familiar with things like Magic and Perk overhauls.  If you aren't familiar with a specific mod, Rt. Click that mod in MO2's list then select Visit on Nexus which will open the mod page in your browser.

### Review MCM Menus

After launching the game the first time and creating your character, you should wait until message stop processing.  Then you are free to open the MCM menu.  It is very useful to understand what gameplay effects are present and tweak those to your preferences if desired.

 ^ <a href="#top">Back to Top</a>
 <BR><BR>
## Getting Support

A good place for support for ETJ related issues is the Discord (see above).  However, it is helpful to do some due diligence:
1. Before asking for support, review the items above to see if you can answer the question based on included mods.
2. Check for Announcements or pinned posts in the Support channel to see if your issue has already been addressed.
3. Search the Discord to see if someone has previously asked the same question.
4. Is the issue specific to ETJ or an issue with an included mod?  While the ETJ team curates the modlist, we cannot provide support for the individual mods not written by members of the team.  We'll offer our best effort but, if the issue is with a specific mod, you may find better support on the specific mod's Nexus page.

 ^ <a href="#top">Back to Top</a>
 <BR><BR>
## Advanced: Saving Settings During Updates

With modlists, any modification to a modlist is refered to as Rule 11.  In this player's guide I'm not going to get into R11 specifics, but changing simple settings (for example via MCM) should not be considered R11.  However, any settings modifications will be lost during a list upgrade.  Therefore, the below guide explains how to make a personal configs 'mod' in MO2 that will persist through list upgrades.

### Why is this needed?

There are generally two types of configs:  .ini/.json and MCM.  MCM settings changed in the MCM interface usually write to a file.  Both types of files will either be stored in the original mod folder (if the file already exists and is just modified by changing a setting) or in Overwrite.  During a list update via Wabbajack, the Overwrite folder is completely dumped and all mods are replaced with the list version so any modified settings are lost during a list update.

### Create a Configs Mod

To prevent losing custom configurations as described above, you can create a mod to hold these settings files which will persist through upgrades.
1. In MO2, scroll all the way to the bottom of the mod list and Rt. Click on the last separator > Create a Separator Above
2. Name the new separator something like "[NoDelete] Custom".  The [NoDelete] tag is important because it tells Wabbajack to keep this separator when performing list updates.
3. Move the new separator to the bottom.
4. Rt. Click the new separator > Create Empty Mod Inside
5. Name the new mod something like "[NoDelete] Custom Configs".  Again [NoDelete] tells Wabbajack to retain this mod during updates.
6. The easiest way to find appropriate configs is to look at the Data tab on the right pane of MO2.  This shows a consolidated view of mod files across all mods.  Main folders to inspect: MCM\Settings and SKSE\Plugins.  NOTE:  MCM\Config contains files defining how the MCM looks, so these are unnecessary.
7. If you have (or want to) customized settings, the Data view will tell you what mod currently contains the associated file.  For example:  If you change the hotkey for Quicklight in the MCM, that is stored in MCM\Settings\QuickLight.ini which is contained in a mod named "ElderTeej - Overwrite Outputs".
8. Rt. Click your Custom Configs mod > Open in Explorer
9. Create the same folder structure from the Data view for any file you intend to include.
10. Rt. Click the file to include in the Data view > Reveal in Explorer
11. Copy the file from the mod (ElderTeej - Overwrite Output in the example above) into the correct folder in your Custom Configs mod folder.
12. Rt. Click your custom configs mod > All Mods > Refresh
13. You should now see in the Data view that the added file comes from your custom configs mod.
14. Repeat above for each configuration you change.

 ^ <a href="#top">Back to Top</a>
 <BR><BR>
