**TASK #1**
A basic HANGMAN GAME based on WORD PUZZLE. The word you are gussing will be either wrong or correct and on that basis a hangman structure will be formed (if you guessed wrong) else you will WIN!

----------------------------------------------------------------------------------------------------------------------------------------------------------------

**TASK #2**
a stock portfolio tracking tool that allows users
to add, remove, and track the performance of their
stock investments.

----------------------------------------------------------------------------------------------------------------------------------------------------------------

**TASK #3**
Duplicate Finder Script
This script scans a given directory for duplicate files based on their MD5 hash. It provides options to delete or move the duplicate files to another directory.

**Features:**
Scan a directory recursively for duplicate files.
Filter files by minimum size.
Display a list of duplicate files.
Option to delete or move the duplicate files.
Usage
Run the script.
Enter the directory you want to scan for duplicates.
Specify the minimum file size to consider (in bytes). By default, it's set to 0, which means all files will be considered.
The script will display a list of duplicate files, if any.
_Choose an action:_
(D)elete: Deletes all but one of each set of duplicate files.
(M)ove: Moves all but one of each set of duplicate files to another directory.
(N)o action: Exits the script without making any changes.

**KEY MODIFICATIONS**
_File Type Filtering:_
Added an input prompt to specify file extensions for filtering. Modified the find_duplicates function to only consider files with the specified extensions.

_Generate Report:_
Added a new generate_report function that creates a JSON report of duplicate files. Added the option for the user to choose to generate a report instead of deleting or moving files.
