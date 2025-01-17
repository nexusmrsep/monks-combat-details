# version 11.08

Fixed issue with players not being able to role initiative.

Added an alert when a combat is created

# version 11.07

Fixed issue where changing the font size for turn notifications to a very large number was wrapping text when it shouldn't be.

Fixed issue where GM changing to the next turn wasn't saving the players targets.

Fixed issue with removing a shadow when the shadow has already been removed.

Fixed issue with the reroll initiative setting was preventing the combat tracker from updating.

Updated the hide enemy function to include rolling initiative privately for creatures that should be hidden.

Fixed issue with defining the visible property of the Combatant.

Fixed issues with removing placeholder combatant when no combatant exists.

Fixed issue with trying to set re-roll initiative specific to a combat instead of using the global setting.

Fixed issue with getting the context menu for combatants.

Added the option to turn off remembering the last position fo the combat tracker

Fixed issue where targets between turns weren't resetting, but adding upon.

# version 11.04

Added the option to set the font size for the large print turn notification.

Fixed initial initiative for placeholder combatants if the previous and next combatants are 1 initiative away from each other

Added the option to remove placeholder combatants after a certain number of turns.

Added the option to record the last position and height of the combat tracker, so the next tiem it's opened it will open exactly where you want it.

Added the option to reroll initiative at the start of every round.

Updated the hide enemies until their turn, to allow GMs to hide and show the enemy if they want to reveal it before it's their turn.

Updated the combat CR function in Pathfinder 2e to use it's own methods to calculate it properly.

Fixed issue with pathfinder 2e where it wasn't registering when a combat starts, and therefore not opening the pop out.

Fixed issue with setting a combatant's token to invisible when dead, if the combatant doesn't have a token.

# version 11.03

Fixing issues with Combat Carrosel Tracker.

Fixing issues with showing shadows for every movement.

Fixed issues with the right click menu for Combatants.

# version 11.02

Added the option to right click and set a combatant to the current combatant.

Added the option to set your own up next and your turn message.

Fixed issue when a combatant doesn't link to an actor.

Fixed issues with start turn icon not showing properly, and causing issues with other modules.

Moving the start icon to the grid layer rather than the tile layer.

Added the option to add placeholder combatants.

Added the option to popout the combat tracker when a combat is created.

Popout the combat tracker on a reload if there's an active combat and it's set to popout.

Fixed issues with combatant disposition.

# version 11.01

Added support for v11

Fixed round message in sw5e

Fixed issue with combat bars not appearing and not resetting the height of the token configuration dialog.

Fixed issue when a shadow doesn't exist and you change turns.

Fixed issue with challenge ratings having an unknown challenge due to either no monsters or no players.

# version 10.2

Fixed code that got lost when migrating from Little Details.  Hiding enemies on the combat tracker until combat starts, and allowing players to right click to target a token on the combat tracker, and allowing the combat tracker to be resized.

# version 10.1

Initial Release, split from Monk's Little Details