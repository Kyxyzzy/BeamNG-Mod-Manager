# BeamNG-Mod-Manager
BeamNG Mod Manager by Kyxyzzy

The BeamNG Mod Manager is a simple tool to help you manage your BeamNG.drive mods. It allows you to enable and disable mods by moving them between a download folder and a mod folder. The program remembers your settings between sessions, so you don’t have to reconfigure it every time and it saves the time/date of when you enabled a mod so that if the new mods cause issues you can pinpoint which caused the error. The program only tracks newly added mods, meaning if you already have mods in your beamNG folder it will not see them. So you must first assure the game already is working fine for this mod manager to work best.

Features

    Enable/Disable Mods: Move mods between the download folder and the mod folder.

    Search Functionality: Quickly find mods by typing in the search box.

    Persistent Configuration: The program remembers your selected folders and enabled mods.
    
    Selecting multiple mods at once just by normal clicking.

How to Use
1. Download and Extract

    Download the BeamNGModManager.zip file.

    Extract the contents to a folder of your choice.
   

2. Run the Program

    Open the folder where you extracted the files.

    Double-click ModManager.exe to launch the program.(You may right click > Send to > Send to desktop, to make a shortcut for the program.

3. Set Up Folders

    When you first run the program, you’ll be prompted to select two folders:

        Download Folder: This is where you store your downloaded mods (.zip files). THIS FOLDER SHOULD ONLY BE USED FOR WHERE YOU DOWNLOAD YOUR NEW BEAMNG MODS.

        Mod Folder: This is your BeamNG.drive mod folder. To find the location open your BeamNG game launcher, select Manage user folder > Open in explorer. This is where the mod folder is.

    Click Select Download Folder and Select Mod Folder to choose the appropriate directories.

At this time the mods that aren't currently enabled(in your download folder) should appear, if not select refresh. You may select refresh anytime you download more mods.


4. Enable/Disable Mods

    Enable Mods:

        Select one or more mods from the Disabled Mods list.

        Click Enable Mod to move them to the mod folder.

    Disable Mods:

        Select one or more mods from the Enabled Mods list.

        Click Disable Mod to move them back to the download folder.

5. Search for Mods

    Use the search boxes above the Disabled Mods and Enabled Mods lists to filter mods by name.

6. Refresh the Lists

    If you add or remove mods manually, click Refresh to update the lists.

Requirements

    Windows: The program is built for Windows and requires the following runtime libraries that are included:

        Qt6Core.dll

        Qt6Gui.dll

        Qt6Widgets.dll

        libgcc_s_seh-1.dll

        libstdc++-6.dll

        libwinpthread-1.dll

        platforms/qwindows.dll

	Plus the exe launcher.

These files are included in the distribution folder, so no additional installation is required as long as you don't move them.


Troubleshooting


The Program Doesn’t Start

    Ensure all the required DLLs are in the same folder as ModManager.exe. You may wish to re-extract the exe if you happen to have deleted anything.

    If you see an error about a missing DLL, download the required runtime libraries and place them in the same folder as the executable.(Or re-extract)

Mods Don’t Appear in the Lists

    Ensure the mods are .zip files and are located in the correct folders.

    Click Refresh to update the lists.

The Program Crashes or Freezes

    Make sure the mod folders are correctly set and accessible.

    If the issue persists, delete the config.txt file (this will reset the program’s settings!!! So back it up).


This project is licensed under the MIT License. See the LICENSE file for details.

If you paid for this program, you've been scammed.
