###IMPORTANT: If you are upgrading from an old version of Project Oracle, you WILL have to reinstall dota 2 first. To do this right-click "Dota 2" in your steam library and click delete local content. Then delete this entire folder "steam\steamapps\common\dota 2 beta" manually.

##Where did you get the name "Project Oracle"?
Oracle is the only hero for which every ability benefits from all three cast types.



#Mission:

1. To implement two modifiers for Windows users.

   SteamOS users can already use the super key as a modifier by default and other linux users can disable ALL of their super key shortcuts inorder to use two modifiers in DotA 2.

   By using a very small ahk script (14 lines of code), the Windows key can be sent to dota2.exe but not to the Windows OS when LAlt is pressed.

   This allows Windows users to enjoy two modifiers aswell. The best part about it is you can still use your Windows Key shortcuts outside of DotA!

   If you prefer to disable your Windows Key everywhere, you can do that too by following a tutorial from a quick Google search.



#To Install:
####Make sure you start at least one bot match on your dota 2 installation before you install Project Oracle or you will break your in-game guides.

1. Place either the 32-bit or the 64-bit .exe, depending upon your system, in your StartUp folder (I have provided a shortcut).
   You can use the .ahk instead if you have installed AutoHotKey. https://autohotkey.com/

2. Place the "Game" folder inside of "Steam\steamapps\common\dota 2 beta" and overwrite.

4. Place the "570" folder inside of "Steam\userdata\ [Your 9 digit Steam ID here] " and overwrite.

5. Reboot your computer or run the .exe you chose from step 1 manually.

##Optional:

1. launch DotA 2 and customize to your liking
####Note: LAlt binds the LAlt modifier but it will read "WINDOWS" in-game. RAlt binds the SPACE modifier but it will read "ALT" in-game.

2. Enable some Project Oracle mods such as the dark minimap. To do this, edit the gameinfo.gi in the "dota 2 beta\game\dota" folder and scroll down to the Project Oracle mods section and follow the instructions there. 
####IMPORTANT: Then open the "dota 2 beta\game" folder and double-click the "CreateSymbolicLinks.bat" file to run it. If you skp this step, in-game build guides will NOT work.

3. ####renable all WinKey shortcuts you have previously disabled by running the .reg file (If upgrading from an old version)


#Customization:
Project Oracle makes use of smart ordering of hotkeys for some heroes which have more than four abilities.
You can easily get rid of the ones you don't like in game by clicking the clear button for a particular hero.
The affected heroes are listed below:

1. Earth Spirit

2. IO

3. Lifestealer

4. Phoenix

5. Timbersaw

6. Lone Druid

7. Morphling

8. Spectre

9. Templar Assasin

10. Chen

11. Keeper of the Light

12. Ogre Magi

13. Puck

14. Rubick

15. Shadow Demon

16. Techies

##If you don't like the dark colored minimap replacer:

1. delete this entire folder

   "game\mod_ProjectOracleMinimap"



#Known Issues:

1. Self-cast abilities which are auto-castable are self-casted when the auto-cast hotkey is pressed.
Only affects Ogre Magi, Lich, and neutral troll priest. This is a valve bug and out of my control.



#Work-arounds:

1. You have to Alt-Tab out of dota using LCtrl-Tab. This may better anyway as you won't accidentally press Alt-Tab when you are trying to Alt-Q.
