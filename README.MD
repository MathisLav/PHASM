#PHASM

###Features:
* Works on the TI-84+CE and TI-83 Premium CE
* Executes archived (sub-)programs
* Executes assembly (sub-)programs (without the `Asm(` prefix)
* Allows you to jump to any Lbl you want by pressing `[Alpha]`+`[X,T,O,n]` in the program editor
* Allows you to edit archived programs
* Built-in Memory Editor: just press `[Alpha]`+`[VARS]` to edit an AppVar or the raw memory (PLEASE READ THE MEMEDIT-README)
* Languages available: English and French. Feel free to ask if you want another one!

###Setup:
To use PHASM, send PHASM.8XG and PHASM.8XP. You don't need to ungroup PHASM.8XG. Then, run `Asm(prgmPHASM)` and that's all there is to it! To uninstall PHASM, just run prgmPHASM.  
_/!\\ Do not delete or archive the AppVar created during the installation. It will trigger an error each time you will need it /!\\_

##New:
* You'll not see anymore some weird programs like `prgmTTEMP` in your Program List!
* If you choose to set your calculator to French, PHASM will detect it and display French texts
* Several bugs fixed (TXTLIB bug, memory leaks, vars corruption)
* Added a Memory Editor
* ERRORS: You can now choose "GoTo" at an error screen even if the program you want to edit is archived
* Optimizations...

Have fun!


------------------

#MEMORY EDITOR
The Memory Editor allows you to edit the memory of your calculator easily. To display the menu which will enable you to edit AppVars (archived or not) or to begin the edition wherever you want, you just have to press `[Alpha]`+`[VARS]`.

###Keys (in the editor) :
* Up/Down/Left/Right : moves the cursor
* Alpha + up/down : scrolls faster
* 1/2/6/3/4/5/6/7/8/9/0/A/B/C/D/E/F : inserts a number in the cursor location

  
BE AWARE THAT THE AUTHOR IS NOT RESPONSIBLE IN CASE OF LOSS OF MEMORY DUE TO THE WAY YOU USE THIS PROGRAM. So be careful when editing Flags, VAT or Memory-Mapped ports.  

This program is under the WTFPL licence.
