OpenCollar is a set of scripts for a collar similar other collars common in SL.  Unlike those systems however, OpenCollar is open source.  You are free to copy and redistribute the OpenCollar scripts, provided that you leave them full perms.  Read the entire OpenCollar License in the notecard accompanying the scripts.

The OpenCollar architecture is plugin-based, allowing for many more features to be added in the future.  Features not found in other collars include:

- complete, menu-driven support for the Restrained Life Viewer.
- ability to automatically punish the sub for saying any word from a list you specify.
- optional Group control (in addition to owners and secowners)
- menu-driven color and texture setting
- automatic updates
- settings are stored to an online database so that they survive script resets and are automatically transferred when you wear a new version of the collar.
- and best of all, free and open source!


Please report any bugs you find or feature requests to the OpenCollar bug tracker at http://code.google.com/p/opencollar/issues.


**Important**  OpenCollar automatically sets the command prefix to the wearer's initials.  Use the wearer's initials before all the commands below.  For example, if Greta Grumpsalot were wearing the collar, she would prefix all commands with her initials "gg", such as saying "ggowner" instead of "owner".  Use the "prefix" command to change the prefix if you want one other than the default initials.

To give a command to two subs at once, use a * in place of the prefix.  For example, *kiss would make all the subs near you give you a kiss, if you have some degree ownership in their collars (owner, secowner, or group).

•.¸.✰.¸.•✰•.¸.✰.¸.•✰•.¸.✰.¸.•✰•.¸.✰.¸.•✰•.¸.✰.¸.•✰•.¸.✰.¸.•✰•.¸.✰.¸.•✰•.¸.✰.¸.•✰•.¸.✰.¸.•

(`'·.¸ table of contents ¸.·'´)
1.0 = List of Commands in the collars
    1.1 = menus and help
    1.2 = Collar Main menu/sub menus
        1.21 = main menu
        1.22 = animation menu
        1.23 = appearance menu
        1.24 = badwords menu
        1.25 = cuffs menu
        1.26 = help/debug menu
        1.27 = leash menu
        1.28 = owners menu
        1.29 = spy menu
2.0 = Ownership
3.0 = Appearance
4.0 = Control
    4.1 = Poses/animations/couples
    4.2 =  Adding Poses/animations
5.0 = Leash
6.0 = Badwords
7.0 = Cuffs
8.0 =Restrained Life Viewer
    8.1 = The main menu
    8.2 = Map/TP menu
    8.3 = Misc menu
    8.4 = Relay menu
    8.5 = Sit menu
    8.6 =Talk menu
    8.7 = Un/Dress menu
9.0 = RLV Shared Folders
10.0 = Relay control
11.0 = Updating Collar


•.¸.✰.¸.•✰•.¸.✰.¸.•✰•.¸.✰.¸.•✰•.¸.✰.¸.•✰•.¸.✰.¸.•✰•.¸.✰.¸.•✰•.¸.✰.¸.•✰•.¸.✰.¸.•✰•.¸.✰.¸.•



1.0 List of Commands in the collars
========== notes=============================
~~the <prefix> is explained above~~
~~  when using the chat commands, the only space comes after the command, see the following examples~~
~~  using the /1 before your <prefix> will keep what commands you say out of open chat, example; /1 <prefix>command.~~
~~ do not include the brackets <> when using the commands~~
===========================================



1.1 = menus and help

<prefix>menu -- gives you the menu from witch you can do all commands.

<prefix>help -- gives you this Note Card


1.2 = Collar Main menu/sub menus
====notes=====
menus change with different features and versions and if your using RLV or the cuffs. both of them are explained later. this is a defaulted menu layout
============

1.21 = main menu
*unlock* -- un/locks the collar, if owned only the owner can unlock
animation -- gives you the animation menu
appearance -- gives you the appearance menu
badwords -- gives you the badwords menu
cuffs -- gives you the cuffs menu( is only available if you have the cuffs script in the collar, and then only works if you have the cuffs on)
help/debug -- gives you the help/debug menu(where you can upgrade your collar)
leash -- gives you the leash menu
owners -- gives you the owners menu to set your owner
RLV -- gives you the RLV menu( refer to 8.0 for more information)
Spy -- gives you the spy menu
Un/dress -- gives you the un/dress( works only with RLV, refer to 8.0)


1.22 = animation menu

Animation menu gives you the following commands
()animlock -- locks the animation in place, can only be undone by the owner
AO -- gives you the Sub AO, and allows you to turn it off/on as well as give you the menu
couples -- gives you a listing of couples animations to select from, and then asks you to pick the person you want to do that pose with, you can also set the time as to how long the animation plays, as well as stop it.
pose -- gives you a listing of all available poses in the collars to select from, then plays that pose, you also can release yourself from the pose here

1.23 = appearance menu
appearance menu gives you the following commands
colors -- allows you to set the color to the float text, and any of the detailing on the collar(this changes for different collars)
font -- allows you to set the font to the collars label
pos -- allows you to set the position of the collar
rotation -- allows you to set the rotation of the collar, and the angle
textures -- allows you to set the texture of the different detaining of the collars, what detailing textures you can change depends on the collar, textures very from collar to collar

1.24 = badwords menu
badwords menu gives you the following options
list  words -- says the list of badwords in the open chat, though only the one that asked to see will be able to see it
clear all -- clears all the set badwords in the DB
say penance -- the phrase or words that you have set the sub to say 
off -- turns badwords off, if you delete all the badwords it will automatically turn off
quick help -- gives you a blue box with some directions on how to use badwords

1.25 = cuffs menu(only works if you have the cuffs script in the collar and are wearing the cuffs)
cuffs menu gives you the following commands
(un)lock cuffs -- locks or unlocks the cuffs
cuff menu -- gives you the cuff menu(only works if you have the cuff script and the cuffs on
sync off -- turns on or off the synchronization of the colors, as they wont synchronize them self from the collar
upd colors -- updates the colors on the cuffs, if they don’t change when you applies another color
upd textures -- dose the same as the colors, only for the textures

1.26 = help/debug menu
help/debug menu gives you the following options
(*)online --  turns on or off the db for your collar
dump cache --  clears the cache in the db
fix menus -- fixes the menus if they error or don’t show up properly
float text -- sets a floating text above your avatar
guide -- gives you this guide
label -- sets a label on the collar(available on select collars)
refresh DB -- refreshes the DB if acting slow
resetscript -- resets the scripts in the collar
sync<-DB -- links the collar to the DB, use this if your collar removes the owner when you take off the collar, or log in
update -- updates the collar, see 11.0

1.27 = leash menu
leash menu gives you the following options
grab -- grabs the sub
yank -- yanks the sub to you
length -- changes the length to a preset number, use the <prefix>length if you want to custom length
leashto -- leashes the sub to a near by object(if you want to leash them to an object you must first put in a script in the object you want them leashed to)
unleash --  releases the sub( if set by the sec/owner only the sec/owner can unleash
give holder -- gives a temporary leash to someone near by, dose not need to be secowner to use this
post -- gives you the post
rez post -- razzes the post near you avatar
give post -- gives the post to someone near you
stay -- keep the slave from moving, if sec/owner sets stay only the sec/owner can unset it
unstay -- allows the sub to move around

1.28 =  owners menu
owners menu gives you the following options
set owner -- gives you a list of persons around you to set as your owner(if the one you want to add is offline use the <prefix>owner <full name> to set it) only the owner can remove themselves, the secowner cant remove the owner.
add secowner -- adds a secowner to the collar, giving them power over the sub, only the owner or secowner can remove the secowner
add blacklist -- adds a name to the blacklist
set group -- sets the collar to a group(though you may have to rezz the collar on the ground for it to take effect, make sure that you in the group(ic have it selected in your groups) as it will set it to the group that is active)
setOpenacc -- set the collar to open access, witch allows anyone to control the sub
reset all -- resets the db and clears out all owner information(only the sub can do this)
rem secowner -- removes the secowner, secowner can remove themselves
rem blacklist -- removes the name from the black list
list owners -- gives you the list of sec/owners in open chat

1.29 = spy menu (***Important, ask your sub if its ok to use this feature, it will record all open chat(sub only) and sends it to the owner***)
spy menu gives you the following options
trace on -- allows you to see when and where the sub TP's to
radar on -- turns on the radar and let you see who is with in 20 meters, updates every few min
listen on -- lets the owner to hear what the sub is saying
radarsetting -- changes the radar settings



2.0 = Ownership

<prefix>owner <full name> -- will add the owner to the collar, owner does not need to be near or online for it to work

<prefix>secowner <full name> -- will add a second owner to the collar, second owner dose not need to be near or online for this to work.

<prefix>setgroup -- will set the group to your current group, you may need to remove the collar for this to take effect, just rezz it on the ground then pick it back up.

<prefix>runaway -- will remove your current owner, and set you as the owner, this is also defaulted when you first wear the collar. Will work if group set as well..

<prefix>setopenaccess -- sets open access to the collar

prefix>unsetopenaccess -- removes open access from the collar 

<prefix>blacklist <full name> -- blacklist this avatar (prevents group or open access)

<prefix>remblacklist <full name> -- removes this avatar from the black list

<prefix>reset -- resets the collar itself, but does not touch the database entries (in theory) 



3.0 = Appearance

<prefix>label <text> -- will set the text on the collar, only available in some collars..

<prefix>text <text> --  will set a floating text above your avatar, works with all collars

<prefix>textoff -- removes the text

<prefix>color -- brings up the color menu, you can set different parts of the collar

<prefix>hide -- hides the collar

<prefix>show -- shows the collar, only works if the collar was hidden first

<prefix>texture -- brings up a menu to select what texture you want on the collar, 


4.0 = Control

<prefix> <letters> -- when changing the prefix make sure you note the new settings, as all commands will need to be done in the prefix you chose, the prefix is defaulted to the initials of the sub wearing the collar

<prefix>channel <number> -- set the channel for the collar to listen to, default channel is /1, the number can only have a value of -2147483648 through 2147483647 only

<prefix>settings -- brings up the correct settings  of the collars, gives a listing of who is owner, second owner, what bad words are set, black list, ect

<prefix>lock -- locks the collar in place, will send a message to the owner if removed, even if owner is offline

<prefix>unlock -- unlocks the collar, once set can only be unset by the owner. when used with the RLV makes the collar undetectable

<prefix>remoteon --  turns the remote on

<prefix>remoteoff -- turns off the remote


4.1 = Poses/animations/couples
==========notes==========
*the poses can be activated thought the menu or in open chat
*included are instructions to add more poses
=======================

<prefix>pose -- brings up a list of poses currently in the collar
* list of poses*
beautystan, belly, bendover, bracelets, cutie, display, doggie, fall, kneel, nadu, naduw, open, pleat, shock, sleep, squirm, submit, subsit, tower, underground(many others, as each collar is different with what is included

<prefix><animation> -- use one of the above that was just listed and plays it. if set by the owner only the owner can unset it...

<prefix>release -- stops all currently playing animations, only the animations that are in the collar, wont stop any other playing animations outside of the collar

<prefix>kiss <name> -- makes the sub kiss that person, owners and secowners still need to use their names at the end. Can use just the first 4 letters(if long named) of the person you want them to kiss

<prefix>hug <name>  -- works the same as kiss, only as a hug..

4.2 =  Adding Poses/animations

Adding poses to the collar; just rez the collar on the ground and copy the pose/animation to the collar, put it back on and check in the animation button to see if its their


5.0 = Leash
=====notes===
the leash only works if the sub is in chat range, wont work with shouting
======================

<prefix>grab -- leashes you to the sub, if already leashed will unleash the sub

<prefix>yank -- yanks the sub to you

<prefix>unleash -- Releases the sub

<prefix>length <number>-- sets length of the leash, no brackets, default setting is 3 meters, but if sub is further than 18 meters from the owner, this wont work

<prefix>giveholder -- gives a temporary leash holder to someone of your choice



6.0 = Badwords

=====Notes=========
for bad words to work you need to add a word first, doing that will turn it on. you need to also set the penance phrase or word for the sub to say...
if owned and the owner turns it on, the sub can not remove the words or turn off badwords
you can also change the badword animation to one that you have just by adding it(explained above in adding poses/animations)
=========================

<prefix>badword <word>-- adds bad word to the collar, also turns on badwords

<prefix>rembadword <word> -- removes the word from the list

<prefix>badwordanim <animation> -- sets the animation when the sub says the badword

<prefix>penance <phrases or word> -- sets the phrase or the word that the sub has to say to stop being punished.



7.0 = Cuffs

===Notes=============
this only works if you have the cuffs attached and the cuff script in the collar..
===================
*cuffmenu ----- works only with the cuffs 1.027 or newer



8.0 = Restrained Life Viewer
=====notes======
visit, http://www.erestraint.com/realrestraint/ to get the restrained life viewer that fits your system best
this Note card will help you with the set up and installation of the RLV(windows only, works with windows Vista)􀀀.
To start using them the wearer of the collar has to be using the Restrained Life Viewer (RLV) and the features have to be enabled (if the collar did not manage to activate them during the log on which happens when logging in in a zone where running scripts is not allowed or due to huge lag).
To activate the features open the main menu and click on RLV.
If the collar did not manage to realize that the RLV is running on log-in then you will find a button called *Turn On*.
Press this one to activate the RLV features. You will receive a message if the collar was able to find the RLV or not. If the collar found the appropriate client the main RLV menu will be available from now on.
If the collar managed to find the RLV on log-in you will find the main RLV menu at this point. 
=====================

 8.1 = The main menu
 
*Turn Off* : Turns off the RLV features
*Clear All* : Clears all restrictions
Map/TP : Opens the Map and TP menu
Misc : Opens the Misc menu
Relay : Opens the Relay menu
Sit : Opens the Sit menu
Talk : Opens the Talk menu
Un/Dress : Opens the Undress and Dress menu (including attachments)

8.2 = Map/TP menu
Forbid/Allow LM : Prevent teleport to a Landmark
Forbid/Allow Loc : Prevent teleport to a location (i.e. by using the map)
Forbid/Allow Lure : Prevent others to offer a teleport to the collar wearer
Forbid/Allow Map : Prevent usage of the Map
Forbid/Allow Minimap : Hide the Minimap
Forbid/Allow ShowLoc? : Hide location in the status bar
Allow All : Remove all limitations of this menu
Forbid All : Apply all restrictions in this menu

8.3 = Misc menu
Forbid/Allow Names : Hide names of avatars around
Forbid/Allow Fly : Disallow flying
Forbid/Allow Touch : Disallows to touch objects away more than 1.5m (i.e. useful to prevent the escape from a cage)
Forbid/Allow Edit : Prevent editing of objects
Forbid/Allow Rez : Prevent rezing of objects
Forbid/Allow Inventory : Prevents using the inventory
Forbid/Allow Notecard : Prevents reading and opening notecards (some subs use notecards to get around IM/Speak limitations! Bad Bad sub!)
Allow All : Remove all limitations of this menu
Forbid All : Apply all restrictions in this menu

8.4 = Relay menu
Enable/Disable Landowner : Objects placed by the landowner can affect the relay on the collar wearer
Enable/Disable Anyone : Anyone can affect the relay on the collar wearer (the RLV options become accessible for the public). Be careful with this one.

8.5 = Sit menu
Forbid/Allow Stand : Hide the stand button. This prevents the wearer to stand up when sitting or using a poseball.
Forbid/Allow Sit : Prevent the ability to sit on objects further away than 1.5m (i.e. useful to prevent the escape from a cage)
SitNow? : Force the wearer to sit
StandNow? : Force the wearer to stand up
Allow All : Remove all limitations of this menu
Forbid All : Apply all restrictions in this menu

8.6 =Talk menu
Forbid/Allow Chat : Prevent sending messages to the local chat
Forbid/Allow IM : Prevent sending IMs
Forbid/Allow RcvChat? : Prevent receiving local chat messages
Forbid/Allow RcvIM : Prevent receiving IMs
Forbid/Allow Emote : Prevent the ability to use emotes (/me command)
Allow All : Remove all limitations of this menu
Forbid All : Apply all restrictions in this menu

8.7 = Un/Dress menu
Clothing : Opens the Clothing menu
Attachment : Opens the Attachment menu
+Folder : Lists the #RLV folders available and offers to add them to the outfit
-Folder : Lists the #RLV folders available and offers to remove them from the outfit

Clothing menu : Offers the ability to strip the appropriate item or all
 Attachment menu : Offers the ability to remove an item from the appropriate attachment point


9.0 = RLV Shared Folders

<prefix>save -- saves the list of folders currently worn by the sub 

<prefix>restore -- makes the sub wear the folders in the saved list 

<prefix>+<pattern>  -- searches for the first folder name in the sub's shared root whose name contains <pattern> and makes them wear it 

<prefix>-<pattern>  -- searches for the first folder name in the sub's shared root whose name contains <pattern> and makes them remove it 



10.0 = Relay control

<prefix>relay -- opens the relay menu 

<prefix>relay auto -- switches to auto mode, the relay will accept every command, except from banned sources 

<prefix>relay ask -- switches to ask mode, the relay will ask for every command from unknown source
 
<prefix>relay restricted -- switches to restricted mode, the relay will reject every command, except from trusted sources
 
<prefix>relay off -- disables the relay 

<prefix>relay playful on/off -- toggles playful submode, if enabled, the relay will accept every non-restraining command 

<prefix>relay land on/off -- toggles landowner submode, if enabled, the relay will accept every command from objects of the landowner 

<prefix>relay safeword on/off -- toggles safewordable submode, if enabled, the sub can safeword 

<prefix>relay safeword -- releases the sub from every object controlling the relay 

<prefix>relay pending -- displays the oldest unanswered relay authorization dialog if any 

<prefix>showrestrictions -- displays RLV restrictions the sub is subject to, and lists the objects which issued those (collar and devices controlling the relay) 



11.0 = Updating Collar
===Note========
 you will need to be in a sim that you can rez objects on the ground.
===============

when you receive the updater that the collar sends you

1) rez the updater on the ground

 2) remove your collar and then rez your collar next to the updater
 
 3) then click on the collar and in the menu find help/debug,  on the next menu find update
 
4) wait for the updater to update your collar, then take the collar back into your inventory, at this time you will have more than one collar of that type, so you can delete the old version

Note; you can repeat  steps 2 -4 for any other collars you may have