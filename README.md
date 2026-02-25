# LoveEternal
Easy Mode mod for Love Eternal

Simply unzip the "levels" folder and replace the existing folder within the game's directory.

If you wish to revert the changes, you can uninstall and reinstall the game and it will replace the modified directory upon reinstallation.

This mod simply removes all spikes and lasers from the game.

v1

Used Notepad++ to simply find/replace all danger elements.
Removed all instances of "spikes"
Changed all instances of "spiked=true" to false
Changed all instances of a laser's "isOn="true" to false

Tested through two sections (collections of levels interrupted by cutscenes), and appears to work without major issue.

The most notable minor issue is that spikes no longer line certain ceilings and floors, and in most instances this will still kill the player whenever there is an invisible wall from an adjoining level blocking the character's momentum; however, in places where there is no impeding wall, the player can slip through to levels and cause unintended issues -- e.g. I came to an in-level character interaction from an unintended path and caused an event to not trigger and then got stuck trying to exit the scene via the wrong path.

I believe in most instances, simply restarting the game and continuing from your last save point should allow you to course correct and prevent such minor issues.
