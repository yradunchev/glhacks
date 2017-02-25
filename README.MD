SUMMARY

  Saves or loads glhack save state.

DESCRIPTION

  You must save before in glhack for this to work.

  You cannot use this script while glhack is running: glhack must be off for saving and loading!!!

  Output save dir is created automatically each time the script is run.

INSTALLATION

  Nethack dir, output save dir must and save separtor must be specified by
  modifying the variables sep, glhack_save_dir and glhack_state_dir at the beginning
  of the source code of this script.

  If you do this after saving, old saves will be lost.

SAMPLE CALLS

  #first save glhack with S command.
  #while the game is quit use:

  glhckcht s 1; glhack    #saves state 1, and comes back to the game
  glhckckt s "hard part"; glhack   #saves state "hard part"

  #to load a state, quit with #quit
  #while the game is quit do:

  glhckcht l 1; glhack    # loads state 1, and comes back to the game
  glhckcht l "hard part"; glhack    # loads state "hard part"

  #when you start the game it should be back at last place.
  #TIP: hit up on the terminal to access terminal history after loading and saving to quickly load and save.

AUTHORS

  Yordan Radunchev
  based on original work of Ciro D. Santilli (https://github.com/cirosantilli/bash-cheat)

