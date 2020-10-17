# The Sleep of Death - A Fallout 3 Modlist for Wabbajack

# THIS IS IMPORTANT! 

# IF YOU DO NOT READ AND DO ALL OF THIS YOUR GAME WILL NOT WORK

- [The Sleep of Death - A Fallout 3 Modlist for Wabbajack](#the-sleep-of-death---a-fallout-3-modlist-for-wabbajack)
- [THIS IS IMPORTANT!](#this-is-important)
- [IF YOU DO NOT READ AND DO ALL OF THIS YOUR GAME WILL NOT WORK](#if-you-do-not-read-and-do-all-of-this-your-game-will-not-work)
  - [Can't launch the game](#cant-launch-the-game)
  - [Known Issues](#known-issues)
    - [Albino Faces, aka Black and White People](#albino-faces-aka-black-and-white-people)
    - [Adaptive Combat Rifle Bugs](#adaptive-combat-rifle-bugs)
    - [This is two guides](#this-is-two-guides)
  - [Gameplay Questions](#gameplay-questions)
    - [Why is my VATS accuracy so high?](#why-is-my-vats-accuracy-so-high)
    - [Why is power armor _reducing_ my carry weight?](#why-is-power-armor-reducing-my-carry-weight)
    - [Arefu Expanded](#arefu-expanded)
      - [Where the fuck is Mary?](#where-the-fuck-is-mary)
      - [Where the fuck are Harry's tools?](#where-the-fuck-are-harrys-tools)

So you just installed _Fallout 3_. I bet you never expected to do that ever again. But you did! That's great.

Please remember that this modlist will not work if _Fallout 3_ is in C:\Program Files, C:\Program Files (x86), on the Desktop (you madman), in the Downloads directory, Documents, maybe even C:\ itself -- anywhere that Windows 10 thinks is "protected." So _move your Fallout 3_ if this is the case. 

First launch the _Fallout 3 Launcher._ This will generate required files for **Wabbajack.** 

Next set your resolution, click the "High" preset ("Ultra" slows stuff down a lot for unnoticeable crap), then click "Advanced" and uncheck "Shadows." 

Fallout 3 shadows are fake. They don't do anything and they make the game slower. Turn them on anyway if you want to stick it to the man.

Then run **Wabbajack.**

Inside the folder where you installed _The Sleep of Death_, you will find a "game folder files" folder. 

All of files inside this folder need to be copied to your Fallout 3 directory, wherever that might be. 

Backup your vorbis file(s) before doing so and allow all overwrites.

If it's the Steam version, they are in /steamapps/common/fallout 3 goty/ inside your Steam folder. Yes, you must have the goty version. No, it will not work otherwise.

If its the GOG version, it will be whatever folder you picked. 

Next you need to launch FO3 _via the official launcher and **NOT** from within MO2._ This finalizes the necessary initializaation of files.

If you have the GOG version, ignore the paragraph below.

If you have the Steam version, you need to run some files inside the Fallout 3 directory (described above). First double-click the _Games For Windows Live Disabler._ It's self-explanatory but I'll explain it anyway. Launch it and click Disable GFWL. You can also turn off the GFWL menu in FO3 if you want. Next launch the _4GB Patch._ A little thingie will pop up asking you which file you want, double click _Fallout3.exe_. A message will say "Executable Patched!" now close the 4GB Patch.exe

You should be okay to play now, but keep in mind once you get out of _Vault 101_ and watch the little newly-added [SPOILER] scene there, you will need to **CHANGE FALLOUT WANDERER'S TERRIBLE TIMESCALE.**

Fallout 3 is weird, it didn't even have a mod configuration menu. So you have to do everything with little items scattered all around your PIPBOY. Annoying, right?

Open your _PIPBOY_ and select apparel. My memory is fuzzy but click something that says _Configure FWE_, then _Immersion Settings_, then Set the _Timescale_ to **10:1 - VANILLA**. _Everything will break if you don't do this!_

There are now a couple of changes to make with power armor. **Keep in mind, _Powered Power Armor_ makes it so that the armor must be powered up now or otherwise you will suffer severe debuffs from fighting the weight of it!** (Imagine driving a car without power steering.) Check that mod's description if you have questions. For now, open the _PA Config_ menu, once again in apparel, and configure the power draw and temperature change to their minimum values of **0.05**. This is so you don't run out of power every three seconds on the vanilla timescale. Next, go into general settings and disable power armor scaling. This is so you don't get a bug preventing you from activating certain objects because the game still thinks you're a baby.

Lastly, I'm not gonna tell you what to do with the rest of your life. Play around with all those bullcrap items and get your game the way you think you'll like it. You'll probably want to leave fast travel on, but hey, to each their own.

I will say that a lot of people like adding _ENB_. Don't. FO3 ENB was never finished by the author. You'll see transparent stuff and giant lakes of water in random spots. It's not worth it.

If you must, pick a _ReShade_ preset instead, but I haven't found a good one for this modlist, so if you manage to do so let me know!

Now get out there in the hell of the wastes and have yourself a ball!

Drop a line in [#unofficial-modlist-support] on the **Wabbajack Discord Server** if you need help. The list is only available there, so you should be there already. I can't guarantee I can fix your problem but I can damn well try.

## Can't launch the game

_Application Load Error X_

Some users are unable to launch the Steam version FO3 from MO2 but fine from the main directory, and get an error like this. It seems Win10 still hates FO3 in some cases. 

Bear in mind that you will save yourself a lot of potential headache and troubleshooting by simply buying a copy of _FO3_ from GOG and using that version. It is already ready to go, it's a great game, and you'll be supporting a great company that puts consumer rights near the top of its priorities.

If that's not in the cards for you for whatever reason, I have two confirmed reports of this Steam error's resolution using the steps below _exactly as written_.

1. Uninstall _Fallout 3_ completely (if you have it installed), including all directories in Documents/My Games, AppData/Local, and ProgramData. If you don't know where these directories are, Google them.

2. Install _Fallout 3_ and launch it _from within Steam._ Configure all settings as specified above and click **PLAY**. Exit as soon as you reach the main menu.

3. Copy over all the game folder files as specified above.

4. This is going to seem a bit weird. Choose the option to _Manage game..._ within Steam and _verify local game files._ If you need assistance with this part, refer to Google.

5. Launch _Fallout 3_ or the _Fallout 3_ Launcher from _within MO2 **not** Steam. If the launcher does not appear, copy the _fallout.ini_ and _falloutprefs.ini_ from My Documents/My Games/Fallout 3 to Sleep of Death/profiles/Sleep of Death.

6. Close MO2 and perform the relevant steps above regarding the _GFWL Disabler_ and the _4GB Patch_ for both executables.

7. Finally launch MO2 and then the game with **FOSE [AKA THE GAME]**

8. If you are _still_ having issues after all this, try setting _MO2_ to run in Administrator mode.

9. Finally, as a last resort, copy the _INI files_ from _Documents_/My Games/Fallout 3 to _tSoD_/profiles/The Sleep of Death. _This is not an ideal solution_ but at this point I am at a loss.

## Known Issues

### Albino Faces, aka Black and White People

If you get an issue where every third black person has a pasty white face, try adding _bLoadFaceGenHeadEGTFiles=1_ under the [General] section of **all** Fallout related INIs on your system, including _Fallout_default.ini_ in your game's folder, all fallout inis in _Documents/My Games/Fallout3/_ and all fallout inis in _tSoD/profiles/The Sleep of Death_. This is a weird fix but it sometimes solves the issue. If it does not, I'm afraid I can't help you with this problem further.

### Adaptive Combat Rifle Bugs

Potential spoiler regarding equipment! Later in the game you have access to the _Adaptive Combat Rifle_. This is an amazing weapons platform that lets you swap out barrels, scopes, magazines, and attachments on the fly to create your own custom rifle based on how you need to use it. Unfortunately based on my research and testing, the mod is horribly broken. Certain combinations of components will render the first person model invisible -- for example, do not attach either the laser pointer or the tripod mount or you will hold an invisible gun. If you build an invisible weapons platform you'll just have to swap things out until you get something visible. Finally, the iron sights mod does *not* take this weapon into account as it was never designed for it. Iron sights will NOT work... you will either have to hip fire or use one of the scopes. (I am particularly fond of the ACOG.)

### This is two guides

I began with the Fallout 3 STEP guide "Clear and Present Danger" from [Kelmych] available [here](https://wiki.step-project.com/User:Kelmych/Fallout3). I removed mods I found to be problematic, such as "20th century weapons" with its nightmare of patches and "RobCo Certified" with compatibility problems. I also took out a couple things not to my taste. Can't remember what, sorry. There were a few remaining items that were left untextured, so for those I filled in details and highlights from the "Fallout 3 Overhaul Guide" available [here](https://www.nexusmods.com/fallout3/mods/23468). All credit goes to those authors, all I did was create an automated installation blending those two approaches. Please don't bother anyone on STEP or the Nexus about this abortion, I'll handle any and all questions because it's my responsibility.

## Gameplay Questions

### Why is my VATS accuracy so high?

Feature of _Fallout Wanderer's Edition_. Customize the combat-related settings if you don't like the default, you can change it so your guns skills affect accuracy, damage, both, or neither, in varying amounts. The default, I think, is balanced for an accurate marksman fighting overwhelming odds which are brought about by _Martigen's Mutant Mod_ and its "Increased Spawns" feature (which is also on by default, seriously, there will be about 30 - 50 raiders in Super Duper Mart)

### Why is power armor _reducing_ my carry weight?

This is a "feature" of _Fallout Wanderer's Edition,_ which I think mainly exists to prevent you from rushing through _Operation Anchorage_ at level 5 and grabbing the Winterized T51b set for smooth sailing through the rest of the game. Basically there are now two levels to power armor training... "Basic" and "Advanced"... and you need both not to gain stat buffs, but to avoid debuffs. Without these perks, your carry weight and agility will be significantly reduced while wearing Power Armor. The only way to get Advanced Power Armor training is to select it at level 18. There are no other requirements. I would prefer not to patch 32 power armor variants to remove a core feature of one of the central mods, so if you don't like these debuffs please just console yourself the advanced training perk.

### Arefu Expanded

This mod is kinda a little bit of a nightmare. Not only were there about a dozen deleted navmeshes that I had to manually replace, which would have caused crash after crash if left untouched, the quest descriptions are just bad, the markers are non-existent, and the McGuffins you are tasked to find are almost indistinguishable from the landscape. So I added this section to help.

#### Where the fuck is Mary?

Go to the quest marker that Mediah directs you to, then search for a pile of bones. You'll see a trail of blood leading to a "door" labeled Abandoned Construction Site. She's in there somewhere.

#### Where the fuck are Harry's tools?

This was perhaps the most infuriating of all to me. Head east of Arefu and look up at the bridge. Harry's house is the second shack from the right. (The far right one is the northern barricade). Somewhat east-north-east of Harry's house, on the ground below of course, you'll find a small smoking campfire. A note there tells you where one of the tools can be found. 
The other two are nearby: the hammer on top of a bullshit rock slightly south, and the wrench wedged nearly entirely inside a tree near the rock. I can't get much more specific than that, sorry.

