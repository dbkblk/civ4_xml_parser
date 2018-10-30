# HOW TO MERGE A NEW TEXT FILE:

## Usage:
As of 2015-09, text files are divided into categories (ACTIONS, BUILDINGS, etc.). If a new mod is merged into RAND, it might comes with new text files. To easily merge those into the categorized RAND mod files, just use the merger.

## Requirements:
Nothing

## How to:
- Put the new text files into "../Rise of Mankind - A New Dawn/Assets/XML/Text".
- Execute ""erger.exe" and wait. All files will be exported to the merge/ subdirectory. At the end, the console will print the number of input tags and of output tags. If this is identical, then you could be confident that it worked. If the file "_duplicates_list.txt" is empty, then no duplicated tags have been found.
- Then, remove all original text files and replace with the newly created ones. The new tags will be automatically detected by Transifex once you'll have comitted your change (a delay might occurs sometimes).

Note: For more customization, open "merger.config". However, I highly recommend not to change the categories, as you should also manually modify those on Transifex.
