# **WowStartScriptBC**

Start script to automate switching between different private servers. This will handle the mundane tasks that are often involved when swapping servers, especially from different hosts, including the following:
- Clearing the WDB folder - prevents item stat issues when switching servers
- Setting logon server - automatically connect to the correct server to find the realm you want
- Setting account name - automatically populate your logon account name to save typing and make it easier to randomize names for security
- Launching the game - why change these settings if we aren't playing

Just run this script from the desktop shortcut, and you will log on to the correct realm without all of the hassle.

## Usage
1. Save the Startscript.bat file in your TBC directory or somewhere easy to remember.
2. Copy the StartScript.bat file and rename it to the realm while keeping the .bat extension (Stonetalon.bat, Medivh.bat, Outland.bat, etc).
2. Open the file in your text editor of choice (default to using notepad)
3. Locate the *User defined settings* section and fill in the correct information
    - Wow.exe file path - location of your executable for the version of the game you are launching
    - Account name - the name you enter at the login screen
    - Realm name - the realm you wish to connect to
    - Logon server - the server the host has you set in your realmlist.wtf file
4. Save your changes.
5. In explorer right click the file, then choose Send to > Desktop (create shortcut).
6. Repeat steps 2-5 for all of the realms you want to set up.

## Optional Step - Change the shortcut icon to WoW icon
1. Right click on your shortcut on the desktop and open the properties.
2. On the *shortcut* tab click the *Change Icon* button.
3. Click *OK* if you get a warning about your file containing no icons.
4. Click *Browse* on the window that pops up.
5. Navigate to your folder you entered for the Wow.exe file path.
6. Select the Wow.exe file and *OK* the WoW icon that shows up in the list.
7. *OK* again to close the properties.
