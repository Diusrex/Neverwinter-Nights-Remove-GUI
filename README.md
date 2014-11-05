Neverwinter Nights Remove GUI
=============================

The hak pak in this branch contains all of the following files, and will completely remove the GUI, other than the current limiation of the popup map.

gui related files
-----------------------------
* ingame_pvp.gui: Determines how the player list (p) will be drawn
  * Can set its Obj_ResRef to gui_empty
* inv_panel.gui: Determines where the inventory (i) menu will be drawn
  * pnl_inv.mdl: Need to change this to completely remove the inventory menu
* jnl_panel.gui: Determines where the outer part of the journal (j) menu will be drawn
  * pnl_jnl_panel.mdl: Need to change this to completely remove the outer part of the journal
* jnl_page_quest.gui: Is responsible for the inner part of the journal (ex: journal listings, as well as the buttons)
  * Can set its Obj_ResRef to gui_empty


Pure Model Files
-----------------------------
* ctl_actionqueue.mdl: Queue of actions on the top right of the screen
* ctl_btn_chatmode.mdl: Chat mode button on the bottom right of the screen. (Talk, party etc.)
* ctl_btn_pb_pause.mdl: Character portrait that appears when the user pauses the game.
* gui_ra_menu.mdl: Responsible for drawing the buttons for the radial menu. 
    NOTE: The radial menu can still be used, but the buttons are just not displayed
* pnl_chat.mdl: The large chat box that can be minimized.
* pnl_chat_prompt.mdl: The box where the user types text 
    NOTE: The text the user is typing will still show up, and in a blue font...
* pnl_chrsht.mdl: The character sheet, appears on "c"
* pnl_compass.mdl: Displays the compass on the bottom right of the screen
* pnl_party_bar.mdl: Information on the right of screen: includes portrait, buttons, and party information
* pnl_quick_bar.mdl: Quick bar on the bottom of the screen
    NOTE: They can still use their abilities of course
* pnl_spellbook.mdl: Known spells list, appears on b
* pnl_spellmemoriz.mdl: Memorize spells list, appears on b
