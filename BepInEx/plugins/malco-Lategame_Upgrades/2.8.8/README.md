# LateGameUpgrades
***INSTALL THE DEPENDENCIES***  
***ALL CLIENTS NEED THIS MOD INSTALLED***  
to install just put the MoreShipUpgrades folder in your BepInEx plugins folder.

### *Everything about this mod can be changed via the extremely extensive config "com.malco.lethalcompany.moreshipupgrades.config"*  
The config is automatically synced from host to clients excluding changes to equipment (peeper, night vision goggles, portable teles)


Type `lategame` in the terminal to see mod info!  
Type `lategame store` or `lgu` to view current upgrade status and cost.  
Type `info <upgrade>` for dynamic info.

This adds 24 powerful ship upgrades to make lategame last longer and remedy having a bunch of money and nothing to spend it on.

If using V40 - downgrade to V2.1.0  
If using v45 - downgrade to v2.8.6

## V 2.8.8
Just hotfixes of reported 2.8.7 bugs.

## V 2.8.7
*Small changes for full compatibility with v47*

- additions
    - compatability: movement speed, jump height, and stamina safely uses += & -= instead of = for better mod compatability.
    - New Upgrade / purchasable: Extend deadline. Pay x amount of money to buy another working day.
    - The config for hunter is much more complex, sample values and what enemies you can gather samples from on each tier.
    - Added LGU info to help command.
    - More logging for easier debugging.

#### **V 3.0.0 is right around the corner and will have a lot of new content.**

## V 2.8.3
- additions
    - Bigger lungs new behaviours (increased stamina regen decreased jump cost final upgrade reduced fall damage)
    - Light Footed has been merged into running shoes (activates on final upgrade)
    - Beekeeper final upgrade increases hive price
    - Discombobulator does damage final upgrade
- fixes
    - Peeper fix
    - Night vision alternate behaviour fixes
    - portable tele drop items fix
    - Protein powder spider fix
    - more

## V 2.8.0
- Hunter
    - Allows you to collect and sell samples from dead monsters
    - each tier unlocks more monsters
- Stimpack
    - Increase max health
    - completely configurable of course
- Medkit
    - Item - left click to heal
    - Limited uses (configurable)
    - Heals for 20 (configurable)
- Diving Kit
    - Heavy, two handed, low visibility
    - Can breathe underwater
- Protein Powder crits
    - Final upgrade of protein powder unlocks the chance to deal a critical hit
- Quite a few Fixes
- [LC Better Saves](https://thunderstore.io/c/lethal-company/p/Pooble/LCBetterSaves/) Compatibility!

## Compatibility

### This mod changes and patches a lot so problems may arise.  
- Bigger Lobby and More Company are more or less compatible but credit desync can arise  
- Door fix causes an issue with locksmith  
- Use common sense, EX: if you download a mod that changes the movement speed of the player every frame and the movement speed upgrade from my mod doesn't work that's why.


## Community

### Please post bugs, assets, or ideas [on this post](https://discord.com/channels/1168655651455639582/1178407269994594435) after joining [this modding discord.](https://discord.gg/hzEcKFSSDX)

Feel free to [create a pull request](https://github.com/Malcolm-Q/LC-LateGameUpgrades) and help with the mod.

Anyone who contributes in any way is greatly appreciated. People willing to contribute 3D models are needed.

## Credit
- GitHub Contributors
    - Dilly_The_Dillster
    - WhiteSpike - [git](https://github.com/WhiteSpike)
    - Croquetilla
- Graphics / Art / Models
    - Sad Amazon
    - Bobilka
    - Pixelated Engie - [twitter](https://twitter.com/PixelatedEngie)
- Beta Testers
    - Lann
    - Kapt
    - Rootbeer
    - Glitched
    - a glitched npc - [twitch](https://www.twitch.tv/a_glitched_npc)

## Upgrades & Items
***Everything is tweakable via the config***

* __Diving Kit - $650__
    * Breathe underwater.
    * Heavy, two handed, low visibility.

* __Stimpack - $600__
    * Increase health by 20 per level.

* __Hunter - $700__
    * Allows you to collect and sell samples from killed monsters
    * **Lvl 1**: Hoarding Bugs & Snare Fleas
    * **Lvl 2**: Spiders & Baboon Hawks
    * **Lvl 3**: Bracken, Thumper, & Eyeless Dog

* __Medkit - $300__
    * Allows you to heal (default 20 points).
    * Limited uses (default 3)

* __Protein Powder - $500__
    * Increase damage dealt with shovels and signs.

* __Lightning Rod - $1000__
    * Redirects lightning to the ship.
    * The closer you (and your metal object) are to the ship, the more likely the ship will attract the lightning.

* __Fast Encryption - $300__
    * Upgrades the signal transmitter.
    * Must have signal transmitter purchased.
    * Instantly sends an unrestricted message to all clients chat when using transmit.

* __Interns - $1000__
    * Replaces your dead friend with a fresh intern (revives your friend).
    * Teleports to a random location in the facility.
    * $1k per use

* __Walkie GPS - $450__
    * Upgrades the walkie talkie to show your position and time.
    * Must be holding it.
    * Useful for fog or finding home.

* __Peeper - $500__
    * Looks at coil heads for you.

* __Locksmith - $640__
    * Makes noise when picking, makes a lot of noise when failing.
    * Just run into a locked door to start the minigame.
    * Strike the pins in the order they flash to unlock the door.

* __Portable Teleporter - $300__
    * An item that when used teleports you back to the ship.
    * Keeps items.
    * 90% chance to get destroyed on use.

* __Advanced Portable Teleporter - $1750__
    * Same as above.
    * 20% chance to get destroyed on use.

* __Beekeeper - $450__
    * Circuit bees do significantly less damage to you.

* __Bigger Lungs - $600__
    * Increased sprint duration.

* __Running Shoes - $650__
    * Increased movement speed.

* __Strong Legs - $300__
    * Jump higher.

* __Malware Broadcaster - $550__
    * Instead of disabling turrets and landmines; Destroy them.
    * Can enable alternate behaviours - Exploding hazards (default), destroying, or disabling for a longer period.

* __Light Footed - $350__
    * Enemies have to be closer to hear your footsteps.
    * Applies to both walking and running.

* __Night Vision - $380__
    * Press Left Alt to toggle night vision.
    * Has self regenerating batery.
    * Pick up and lmb to equip.
    * Lose on death (by default).

* __NV Headset Batteries - 300__
    * increases regen speed and decreases depletion speed of NV
    * Can also increase range and intensity of night vision light for alternate behaviour (if enabled in the config).

* __Discombobulator - $450__
    * Enter `initattack` into the terminal to stun enemies around the ship.
    * Enter `cooldown` to view cooldown (120 seconds).
    * Attracts enemies in a larger radius than loud horn.

* __Better Scanner - $650__
    * Level 1
        * Increase distance of Ship and Entrance pings drastically.
        * Increase distance of all other pings.
    * Level 2
        * Unlocks 5 new scan commands - scan player, scan enemies, scan scrap, scan hives, scan doors.
        * Type `info better scanner` for information on each.
    * Level 3
        * Allows you to scan scrap through walls.
        * Change the config if you also want to scan enemies through walls.

* __Back Muscles - $715__
    * Carryweight is drastically reduced.
    * % reduced increases each upgrade.
