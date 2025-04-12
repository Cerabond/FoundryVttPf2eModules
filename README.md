# Cerabond's Module Suite for Foundry VTT and PF2e
A collection of various quality of life modules for PF2e in Foundry Vtt

## Installation Instructions:
For **modules**, copy simply copy the folder itself containing the module you want (for example, "cerabonds-hide-the-magic") into your local appdata folder for Foundry.
**Example of Foundry Local appdata folder on Windows:** 
C:\Users\\{yourUsername}\AppData\Local\FoundryVTT\Data\modules

For **macros**, simply copy the contents of the text file into the "Command" text box when creating a new macro from your tray, making sure to set the "Type" to "Script"

---

### List of Modules:

#### Cerabond's Current Combatant Sheet
For the GM, upon selecting "Next Turn" on the initiative tracker, the appropriate character sheet for the current combatant will appear on the screen.

#### Cerabond's Degrees of Success
When a combatatant makes a saving throw using the spell or effect saving throw dialogue option from the chat, the character will be color coded based on the result. 

 | Degree of Success   | Color         |
|---------------------|---------------|
| Critical Failure     | Dark Red      |
| Failure              | Burnt Orange  |
| Success              | Green         |
| Critical Success     | Blue          |


This is meant to be paired with the macro "RemoveAllTokenColors" which simply removes all tints active on macros in the current scene, so as to clean up the colors after each saving throw.

#### Cerabond's Hidden By Default
Normally, when adding a token/actor to initiative for combat, they immediately appear in the initiative tracker. This can be problematic for multi-room encounters with lots of enemies you don't want players to be aware of until they see them.

This module automatically hides NPC combatants from player view when they are added to initiative, allowing the GM to add mass NPCs without worry.

That said, especially on slower machines, there can be a slight delay before the combatant is removed, giving players already looking at the initiative tab a brief instant of seeing the enemy combatants. This module is meant to be used in combination with "Cerabond's Hide the Magic", which forces all players' views back to the chat tab upon the adding of any combatant to initiative. This workaround proves to be quite effective at keeping the combatants secret to the players.

#### Cerabond's Hide the Magic
This simple module isn't very helpful on its own, and is intended to be used to support the experiences with other modules, like **Cerabond's Hidden By Default** and **Cerabond's Unknown Creature Name**

#### Cerabond's Unknown Creature Name
By default, a combatant in Foundry will display whatever name is configured for the token/actor combination. 

This module, when adding an NPC to initiative, immediately changes the name for that NPC in initiave and chat to "Unknown Creature", so as not to allow players to accidentally metagame upon seeing the actual name of the creature. Notably, the name on the character sheet for each NPC combatant remains its original name, so that the GM can still keep track of what is what.

That said, especially on slower machines, there can be a slight delay before the combatant name is updated when initially added to initiative and shown in the initiative tab, giving players already looking at the initiative tab a brief instant of seeing real the enemy combatants. This module is meant to be used in combination with "Cerabond's Hide the Magic", which forces all players' views back to the chat tab upon the adding of any combatant to initiative. This workaround proves to be quite effective at keeping the combatants secret to the players.
