## SUMMARY

  Saves or loads glhack save state.

## DESCRIPTION
 
  You must save before in glhack for this to work.   
  You cannot use this script while glhack is running: glhack must be off for saving and loading!!!   
  Output save dir is created automatically first time the script is run.   

## INSTALLATION

  Nethack dir, output save dir must and save separtor must be specified by
  modifying the variables sep, glhack_save_dir and glhack_state_dir at the beginning
  of the source code of this script.

  If you do this after saving, old saves will be lost.

## SAMPLE CALLS

  First save glhack with S command.   
  While the game is quit use:   

  #saves state 1, and comes back to the game:   
  _glhckcht s 1; glhack_    

  #saves state "hard part":   
  _glhckckt s "hard part"; glhack_   

  To load a state, quit with #quit   
  While the game is quit do:   

   # loads state 1, and comes back to the game:      
  _glhckcht l 1; glhack_  

  # loads state "hard part":   
  _glhckcht l "hard part"; glhack_   

  When you start the game it should be back at last place.   
  TIP: hit up on the terminal to access terminal history after loading and saving to quickly load and save.


  Based on original work of Ciro D. Santilli (https://github.com/cirosantilli/bash-cheat)

