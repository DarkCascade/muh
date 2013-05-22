muh
===

An Ouya action RPG in which attacks are launched and blocked using combinations of the Ouya's four controller buttons.

Abstract
--------
The player has attacks at their disposal that can be launched at any time by pressing the Ouya controller's buttons
in the right order. For example, a basic fireball may required "O U A" to be pressed in that order to launch. While
the player is engaged with an enemy, that enemy will also launch attacks that can be blocked with certain other
combinations. The required combinations will appear above the incoming attack to let the player know what to press
to defend. The game will need a mechanism to allow the player to save buttons that have already been pressed in order
to block an incoming attack and resume the attack afterward. Example: L1.

[Big attack requires "O U U A O Y" to be pressed. After entering "O U U" the enemy launches an attack that can
 be blocked with "A A". Entering "A A" immediately will break the player's input and fizzle their spell, so they
 can opt to save their input with L1, then enter "A A" to block the incoming attack, then L1 again to resume their
 input. End result: "O U U L1 A A L1 A O Y"]
