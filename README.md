# MakerBaseSGB

Welcome to MakerBaseSGB - this is a Smile Game Builder project that holds utilities in events that expand on the base functionality of SGB. 

# Using This Project

There are two ways to use MakerBaseSGB for your own projects. 

1. Open and rename MakerBaseSGB, and use the scripts as-is
2. Copy/Paste scripts from MakeBaseSGB into your own projects

Neither option is ideal, and usage will depend on what is needed for your own projects

## MakerBaseSGB as a Project Base

This is the easiest approach to using the MakerBaseSGB scripts. All the variables are properly named, and can be used and modified as needed. However, future updates to MakerBaseSGB will require using approach #2, as there is no facility in SGB for having external or "plugin" libraries.

To use this approach do the following:

1. Download or clone the project files from Git
2. Change the project folder name to your project name
3. Open the project from Smile Game Builder
4. Click "Edit Game Data"
5. Change the game title to your own

Once your project is setup, follow steps in the next section to import updates from MakerBaseSGB into your project as they become available.

## Copy / Paste scripts from your SGB 

SGB Allows for copying and pasting events and scripts between projects. However, there are a few caveats that makes this process a little challenging.

1. Pasted scripts do not retain variable names
2. If the existin project has the same variable numbers, this will cause conflicts and issues with the script running (scripts will work, but may overwite values if there are varaibles of the same number)
3. Scripts that rely on certain assets need those assets to also be moved into the new project, or the scripts will need to be fixed to point at alternate assets

While it's not possible to alleviate these issues completely, the steps below provide a repeatable (high level) method to importing scripts.

1. Have your new or existing project setup and ready
2. Open MakerBaseSGB in Smile Game Builder
3. Find the script or event you want to copy into your project
   4. Common Events and Battle Events (in Edit Game Data) can be copied fully from the respective menus
   2. If copying a portion of a script, choose the "text" display mode from the script editor (top right) - this allows you to select sections of the script to copy out
   3. Events on the map can be copied by clicking individually, or selecting a group, and using ctrl-c
4. Click the "Game File" menu to be taken back to the project select window
5. Open your project
6. If the scripts to be imported have associated assets, click "Add Assets" to find and add the appropriate assets from the MakerBaseSGB project
7. Navigate to the past location (Common Events / Battle Events / any map)
8. Paste in your script
9. Optional steps:
   1. After pasting you'll see variables that have numbers, but are all nameless
   2. Re-Open the MakerBaseSGB project and navigate to any script with Variables
   3. Double Click to see the variable editor, and click the drop down that has all the common variables on display
   4. Take a screenshot of the variable list and reopen your project
   5. Navigate to the newly pasted script, and use the screenshot as a reference to fix all the variable names.