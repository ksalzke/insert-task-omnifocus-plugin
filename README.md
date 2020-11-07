# About

This is an Omni Automation solitary plug-in for OmniFocus that allows the user to insert a task to be completed before or after the currently selected task.

_Please note that all scripts on my GitHub account (or shared elsewhere) are works in progress. If you encounter any issues or have any suggestions please let me know--and do please make sure you backup your database before running scripts from an amateur on the internet!_

## Known issues

None so far! 🤞

# Installation & Set-Up

**Important note: for this plug-in bundle to work correctly, my [Function Library for OmniFocus](https://github.com/ksalzke/function-library-for-omnifocus) is also required and needs to be added to the plug-in folder separately.**

1. Click on the green `Clone or download` button above to download a `.zip` file of the file in this GitHub repository.
2. Unzip the downloaded file.
3. Move the `.omnijs` file to your OmniFocus plug-in library folder.

# Actions

## Insert Task

This action can be run on a single selected task. It:

1. Shows a form prompting the user for:
    * the name of the new task, and 
    * whether the new task should appear _before_ the selected task. (If this is not selected/checked, the new task will be created _after_ the selected task.)

2. If the task is not contained within a sequential action group or project, creates a sequential action group and moves the selected task within this group. (This is to ensure that the 'order' of tasks is maintained within parallel action groups/projects.)

3. Creates a new task with the entered name either before or after the original task, depending on the user's selection at #1.