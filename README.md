# The Sleep of Death - A Fallout 3 Modlist for Wabbajack

# THIS IS IMPORTANT! 

# IF YOU DO NOT READ AND DO ALL OF THIS YOUR GAME WILL NOT WORK

So you just installed _Fallout 3_. I bet you never expected to do that ever again. But you did! That's great.

Please remember that this modlist will not work if _Fallout 3_ is in C:\Program Files, C:\Program Files (x86), on the Desktop (you madman), in the Downloads directory, Documents, maybe even C:\ itself -- anywhere that Windows 10 thinks is "protected." So _move your Fallout 3_ if this is the case. 

First launch the _Fallout 3 Launcher._ This will generate required files for **Wabbajack.** 

Next set your resolution, click the "High" preset ("Ultra" slows stuff down a lot for unnoticeable crap), then click "Advanced" and uncheck "Shadows." 

Fallout 3 shadows are fake. They don't do anything and they make the game slower. Turn them on anyway if you want to stick it to the man.

Then run **Wabbajack.**

Inside the folder where you installed _The Sleep of Death_, you will find a "game folder files" folder. 

All of files inside this folder need to be copied to your Fallout 3 directory, wherever that might be. 

There are two _libvorbis_ files in there that will be overwritten. Back them up first.

If it's the Steam version, it's in /steamapps/common/fallout 3 goty/ inside your Steam folder. Yes, you must have the goty version. No, it will not work otherwise.

If its the GOG version, it will be whatever folder you picked. 

Next you need to launch FO3 _via the official launcher and **NOT** from within MO2._ This finalizes the necessary initializaation of files.

If you have the GOG version, ignore the paragraph below.

If you have the Steam version, you need to run some files inside the Fallout 3 directory (described above). First double-click the _Games For Windows Live Disabler._ It's self-explanatory but I'll explain it anyway. Launch it and click Disable GFWL. You can also turn off the GFWL menu in FO3 if you want. Next launch the _4GB Patch._ A little thingie will pop up asking you which file you want, double click _Fallout3.exe_. A message will say "Executable Patched!" click _Another File_ and double-click _Fallout 3 Launcher.exe_. A message will say "Executable Patched!" now close the 4GB Patch.exe

You should be okay to play now, but keep in mind once you get out of _Vault 101_ and watch the little newly-added [SPOILER] scene there, you will need to **CHANGE FALLOUT WANDERER'S TERRIBLE TIMESCALE.**

Fallout 3 is weird, it didn't even have a mod configuration menu. So you have to do everything with little items scattered all around your PIPBOY. Annoying, right?

Open your _PIPBOY_ and select apparel. My memory is fuzzy but click something that says _Configure FWE_, then _Immersion Settings_, then Set the _Timescale_ to **30:1 - VANILLA**. _Everything will break if you don't do this!_

Lastly, I'm not gonna tell you what to do with the rest of your life. Play around with all those bullcrap items and get your game the way you think you'll like it. You'll probably want to leave fast travel on, but hey, to each their own.

I will say that a lot of people like adding _ENB_. Don't. FO3 ENB was never finished by the author. You'll see transparent stuff and giant lakes of water in random spots. It's not worth it.

If you must, pick a _ReShade_ preset instead, but I haven't found a good one for this modlist, so if you manage to do so let me know!

Now get out there in the hell of the wastes and have yourself a ball!

Drop a line in [#unofficial-modlist-support] on the **Wabbajack Discord Server** if you need help. The list is only available there, so you should be there already. I can't guarantee I can fix your problem but I can damn well try.

## Can't launch the game

_Application Load Error X_

Some users are unable to launch the Steam version FO3 from MO2 but fine from the main directory, and get an error like this. It seems Win10 still hates FO3 in some cases. 

Bear in mind that you will save yourself a lot of potential headache and troubleshooting by simply buying a copy of _FO3_ from GOG and using that version. It is already ready to go, it's a great game, and you'll be supporting a great company that puts consumer rights near the top of its priorities.

If that's not in the card for you for whatever reason, I have two confirmed reports of this Steam error's resolution using the steps below _exactly as written_.

1. Uninstall _Fallout 3_ completely (if you have it installed), including all directories in Documents/My Games, AppData/Local, and ProgramData. If you don't know where these directories are, Google them.

2. Install _Fallout 3_ and launch it _from within Steam._ Configure all settings as specified above and click **PLAY**. Exit as soon as you reach the main menu.

3. Copy over all the game folder files as specified above.

4. This is going to seem a bit weird. Choose the option to _Manage game..._ within Steam and _verify local game files._ If you need assistance with this part, refer to Google.

5. Launch _Fallout 3_ or the _Fallout 3_ Launcher from _within MO2 **not** Steam. If the launcher does not appear, copy the _fallout.ini_ and _falloutprefs.ini_ from My Documents/My Games/Fallout 3 to Sleep of Death/profiles/Sleep of Death.

6. Close MO2 and perform the relevant steps above regarding the _GFWL Disabler_ and the _4GB Patch_ for both executables.

7. Finally launch MO2 and then the game with **FOSE [AKA THE GAME]**

8. If you are _still_ having issues after all this, try setting _MO2_ to run in Administrator mode.

### This is two guides

I began with the Fallout 3 STEP guide "Clear and Present Danger" from [Kelmych] available [here](https://wiki.step-project.com/User:Kelmych/Fallout3). I removed mods I found to be problematic, such as "20th century weapons" with its nightmare of patches and "RobCo Certified" with compatibility problems. I also took out a couple things not to my taste. Can't remember what, sorry. There were a few remaining items that were left untextured, so for those I filled in details and highlights from the "Fallout 3 Overhaul Guide" available [here](https://www.nexusmods.com/fallout3/mods/23468). All credit goes to those authors, all I did was create an automated installation blending those two approaches. Please don't bother anyone on STEP or the Nexus about this abortion, I'll handle any and all questions because it's my responsibility.

### Known problems

Experience gains are too high. You'll jump 40XP discovering Springvale just outside the Vault which will bump you halfway to level 3 since you'll already be level 2 from Vault 101's bullcrap. I know nothing about how to correct this yet. Also, Fallout Redesigned (Project Beauty) seems to be a rather inconsistent mod. Caucasian heads on African bodies, pasty white faces, the list goes on. I have tried all the solutions the crappy search engines will give me but have yet to find a satisfactory answer other than removing the mod. I decided not to do that since the NPCs that work look damn good. I thought to remove the body replacers too but all the armors fit those meshes and have the weird black bars on chests problem if you deactivate them. Another thing, don't message me about neck seams. Nobody ever solved neck seams in Fallout 3 or NV. The best solution was... equipping every NPC with a blingy neck chain to cover it up. Also the body replacers are nude, so don't play this in a sensitive environment.

