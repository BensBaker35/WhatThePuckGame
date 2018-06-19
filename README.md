# WhatThePuckGame
What The Puck is a Turn Based Ice Hockey strategy game. The idea spawned from the Ludum Dare 41 which challenged devs to create a game that used a mix between less common or "incompatible" genres. However, due to work and being relatively inexperienced with game development and design, it took me about 6 weeks extra working on and off to get the game to a place where I was happy to put it on the internet.

How to play
	Faceoffs	
		1. Team 1 selects a number 1 - 5 first
		2. Team 2 selects a number 1 - 5 second
		3. Whichever team is close to the random number generated will be the team that is closest will be the one who can make the first move

	Gameplay
		Move
			1. Select a player
			2. Select a Waypoint
			3. If the waypoint is greater than a distance of three, the game will ask you to choose a new waypoint

		Block
			1. Select a player
			2. The player will stop the puck from passing through for three turns

		Pass
			1. Select a player
			2. Select a waypoint
			3. The farther the waypoint, the less likely the pass is going to complete
			4. When the puck starts to move if there are any obstructions, it will stop

		Shoot
			1. Select a player
			2. The farther away the player is from the goal, the less likely the shot will score
			3. The puck will move toward the goal and it will stop at any obstructions

		Body Check
			1. Select a player
			2. Select a waypoint that contains a player, who has the puck
			3. The other player will be knocked back, while the select player will take spot previously held by the other player
		Undo
			1. Will bring you back to the previous selection state
		
		Next Turn
			1. Will end the current teams turn and move on to the next
	 Winning
		- The team with the greater score after 20 rounds
		
