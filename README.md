# Game Design Document - REACTION TIME
*A Dead Zone Games Top Fuel Drag Racing Game*

May 2nd, 2020

GameDev.tv Game Jam Theme: **TIME**

## Concept
Reaction Time is a single and multi-player car drag racing game. After selecting a car, player(s) will be spawned into a lane where they will either race against the clock (aka Time Attack Game)  to achieve the fastest time and speed or against another player.

## Gameplay
The game will consist of 3 qualifying rounds.

At the start of each round, players can optionally do a “Burn Out” to warm up their tires for traction.

Players will watch the countdown lights (Yellow, Yellow, Yellow, Green), and immediately press the spacebar when the lights go green. The faster the player’s reaction time, the faster they will accelerate from the starting line.  If the player presses the spacebar before the light turns green, the player will receive a red light and be disqualified for that round.

In order to obtain optimum speed during the race, players will need to execute perfect shifts (similar to action reloading found in many shooter games). Shifting will be done by pressing the spacebar when the “gear shift” indicator reaches a specific point. Pressing the spacebar before or after this perfect shift point will result in lower speeds, a missed shift or massive engine failure (resulting in a glorious explosion!).

At the end of each race, the player’s final time and speed will be displayed. For multiplayer games, the position the player came in will also be prominently displayed.

## User Interface (UI)
The user interface will consist of the following components:
* Keyboard / Mouse and/or Gamepad Controller
* Heads Up Display (HUD)
	* Speedometer / RPM
	* Action gear shift indicator (prototype will utilize a slider bar)
	* Stopwatch
	* Resulting time and speed
	* Fastest time and speed
	* History of timed and speeds
* Menu system
	* Splash screen
	* Start Menu
		* Racing background image (license free)
		* Background racing sounds and/or engine noises
		* Single Player Game Button (Takes player to Single Player Menu/Lobby)
		* Multiplayer Game Button (Takes player to Multiplayer Menu)
		* Exit Button (Quits game for player)
		* (Future) Credits Button (Display game developers)
	* Single Player Menu or Lobby
		* Car Selection
		* (Future) Track Selection
		* Cancel Button (Returns to Start Menu)
		* Start Game Button (Transfers player to racing game level)
	* Multiplayer Menu
		* Host a Game Button (Takes player to Host a Game Menu)
			* Host a Game Menu
				* Server Name
				* Max Number of Players
				* Local LAN or Internet (Steam) play
				* Cancel Button (Returns player to Multiplayer Menu)
				* Host Button (Transfers player to Lobby)
		* Join a Game Button (Takes player to Join a Game Menu)
			* Join a Game Menu
				* Displays user selectable list of active games to join
				* Cancel Button (Returns to Multiplayer Menu)
				* Join Button (Takes player to game lobby)
		* Cancel Button (Returns to Start Menu)
	* In Game Menu (Pauses Game)
		* Cancel Button (Returns player to game)
		* Leave Game Button (Returns player to either the Single Player Menu or the Multiplayer Menu)

## 3D Characters, Objects and Environments
The game will consist of the following 3D characters and objects:
* Futuristic Top Fuel Dragsters
* Countdown Lights (pole mounted)
* ¼ Mile (1,320 ft) Drag racing track with start and finishing lines
* (Future) Spectator stands
* (Future) NPC Track personal

## Music and Sound FX
The game will consist of the following music and sound fx:
* Start Menu background racing sounds
* Ambient racing sounds
* Track personnel talking
* Top fuel dragster engine revving sounds
* Tire burnout sounds
* Tire squealing sounds
* Race engine explosion sounds
* Car crash sounds
* Upbeat hard rock music to be played during the race
* Clapping sounds for the race winner
