Neverwinter Nights Remove GUI
=============================

gui Dependent
-----------------------------

The hak pak in this branch contains all of the following files which remove GUI elements that must be removed using a .gui file.

Files
-----------------------------

* ingame_pvp.gui: Determines how the player list (p) will be drawn
  * Can set its Obj_ResRef to gui_empty
* inv_panel.gui: Determines where the inventory (i) menu will be drawn
  * pnl_inv.mdl: Need to change this to completely remove the inventory menu
* jnl_panel.gui: Determines where the outer part of the journal (j) menu will be drawn
  * pnl_jnl_panel.mdl: Need to change this to completely remove the outer part of the journal
* jnl_page_quest.gui: Is responsible for the inner part of the journal (ex: journal listings, as well as the buttons)
  * Can set its Obj_ResRef to gui_empty

