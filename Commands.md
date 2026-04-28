# Neuro's abilities
findBrokenServer()
- vanilla kerfur ability, finds broken servers, navigates to them, and fixes them

meowAnim()
- vanilla kerfur ability
- `meow meow lol`
- replace kerfur meow with neuro meow?

jump()
- vanilla kerfur ability, jumps

movePawnTo(object)
- vanilla kerfur ability, takes an object as input and navigates to the object
- ABSOLUTELY CRITICAL FOR THE MOD
- list of objects that can be navigated to:
	- servers
	- coordinate radars
	- transformers
	- base
	- Vedal (player, can use follow() command)
	- waypoints (modded)
	- kerfurO parts?
- add ability to go to coordinates?

follow()
- vanilla kerfurO function, ported to the kerfur. follows the player.

getData()
- gets context, slightly modded

spin("String")
- modded kerfur ability, spins in given direction
- should it be a string or some other data type? could honestly be a boolean if Neuro can understand it, or a float for speed
- MANDATORY, MOD CANNOT SHIP WITHOUT THIS

console("String")
- runs a command on the in-game console (NOT the dev console)
- can do nearly anything a player can, aside from debug commands
- *runs on the base console*
- returns simplified output for Neuro to read
