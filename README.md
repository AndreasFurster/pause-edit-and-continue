# Pause, edit and continue
## Download (NOT STABLE)
https://marketplace.visualstudio.com/items?itemName=AndreasFurster.pause-edit-and-continue

## Current implementation
It adds an menu item to the debug menu for pause, edit and continue. When pressed it breaks the current debug execution and keeps the same file opend. The addin crashes if the user is not debugging at this point.

## Concept
This should become a VS addon to automatically pause on edit. It relies heavely on edit and continue.

1. Begin typing (or use shortcut) while debugging
1. The application will automatically pause so you can change the code
1. Use Ctrl + S or F5 to get it running again...

