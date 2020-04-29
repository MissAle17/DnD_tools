# DnD_tools
Creating a set of python based tools for Dungeons and Dragons

Dungeons and Dragons is a roleplaying game first and formost.  To make that work, however, there is an inderlying set of rules and mechanics. Some of these mechanics are cumbersome and I am aiming to create some tools to make this a little easier.

### Rolling for Stats

The first step in the role playing game is to make a chancter.  One of the first steps in amking a playable character is defining the six base stats:_Constitution, Strength, Dexterity, Charisma, Intellect, and Wisdom_.  I reated a rolling system that ensures level one characters start with no stats, before modifiers, higher than 16 and alllows for throwing out the lowest roll, hopfully, creating a character with minimal 'negative' stats. 

### Roll a die

The 20-sided die is the primary system for introducing a little randomness into the game.  I created a function to roll that d20.  If you need one of the other core dice, you can also ask the same function for a different sided die roll.  

### Character or NPC Name Generator

If you are running the game, or sometimes playing, creating a new name for a character can create a panic of writer's block.  This name generator takes some of the pain out of it.  All standard rule book conventions are followed for playable races.  Humans have the availability of using the subraces included in 5e. Tiefling have the ability to choose a virtue name as well as an infernal name. Currently, all core rule book playable races are supported.