# 1.2.0
+ Initial official release
# 1.2.1
+ Quick fix for assetbundle not loading.
# 1.2.2
+ Fixed bug preventing you from buying items in terminal.
# 1.2.3
+ Minor compatibility fixes
# 1.2.4
+ Added compatibility patch for MoreEmotes!
# 1.2.5
+ MoreEmotes compatibility patch did not upload with my last update. Should be fixed now.
# 1.3.0
+ Added an Emote Radial Menu!
+ Fixed the issue with start animations not transitioning properly to their loop animation. (as far as I can tell)
+ Potential fix for not loading the asset bundle when not using a mod loader.
+ Various other fixes. There are likely some that I missed.
# 1.3.1
+ Accidentally left out updated README.
# 1.3.2
+ Now automatically removes old config entries.
+ Forgot to re-place the preview animation render subject underneath the map again.
# 1.3.5
+ Added pages to emote radial menu.
+ Fixed issue with not seeing others emoting with More_Emotes mod installed.
+ Added config to start with all emotes unlocked. (Server only setting, and will sync with clients)
+ Added basic complementary emotes to start with.
+ Tweaked existing emote animations.
+ Emote selection rotates daily!
+ Now over 100 emotes!
# 1.3.6
+ Fixed issue with asset bundles
# 1.3.7
+ Fixed emotes not rotating daily.
+ Fixed local player arms sometimes appearing during emotes.
+ Potential fix for issue with terminal thinking players are trying to buy an emote when they're not.
+ Moved Asset Bundles in the Assets folder.
# 1.3.8
+ Forgot to move Asset Bundles into their folder.
# 1.3.9
+ Fixed bug where emotes weren't rotating until after the first round.
+ Fixed bug where free emote coupons weren't registering correctly.
# 1.4.0
+ Added compatibility with MoreCompany and MirrorDecor!
+ Now unlocks all emotes at the start of the game if host does not have the mod.
+ Added an emote rarity system. Each emote will have its own tier, which affects how often emotes of that rarity will appear in each store's rotation slot.<br>
If you're not a fan of the rarity system, you could set all the weights for each tier to the same number in the config.
+ Emotes are now priced based on their rarity. They are not all 100 anymore.
+ Emote store now shows 6 emotes by default instead of 3.
+ Because of this tier system, emote coupons have been removed, and have been replaced with emote credits.
+ Emote names in the terminal have been color coded based on their tier. (green, blue, purple, and red) The colors can be changed in the accessibility section in the config.
+ Weapon wheel not displaying the correct emote has been fixed.
+ The seed bug <i>should</i> be fixed now. It preventing the seed from updating after new games.
# 1.4.1
+ Forgot to normalize the prices if the rarity system was disabled in the config.
+ Added config entry for setting the base price for emotes when the rarity system is disabled.
# 1.4.2
+ Fixed an issue when disabling the rarity, where the likelyhood of an emote was based on the tier, regardless of how many emotes were in that tier.<br>
This made the emotes from the upper tiers appear more frequently than the ones from the ower tiers.
# 1.4.3
+ Fixed wrong asset bundle path.
# 1.4.4
+ Reverted MirrorDecor and MoreCompany compatibility patch for now.
# 1.4.5
+ Reduced the price of the tier 4 emotes to 300 (from 500)
+ Fixed compatibility with MoreCompany and MirrorDecor. Hopefully for good this time.
+ Animation preview now shows current skin, as well as any MoreCompany Cosmetics. (might work with custom models)
+ Changed the way the animation preview lighting works.
+ By default, the emote menu is not toggled anymore. Press to open, release to close. Releasing will play the currently hover emote. You can set this back to toggled in the config.
+ Can now change emote page by scrolling. You can reverse the scroll direction can be reversed in config.
+ Updated how syncing works between client/server. <i>Should</i> fix the issues with not syncing emotes and such with server.
# 1.4.6
+ Added the california girls dance meme from friday the 13th (I think)
# 1.4.7
+ Fixed issue with scrolling 4 pages at a time in the emote wheel.
+ Fixed syncing buffer overflow issue.
# 1.4.8
+ Fixed local player mesh disappearing in third person emotes after dying.
+ Fixed seed not updating and/or syncing properly.
# 1.4.9
+ Applied compatibility patch for BiggerLobby (Thanks <> Bobbie!)
+ Publicized most of my classes to help with compatibility.
+ Various minor fixes.