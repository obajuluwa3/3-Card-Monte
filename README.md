# Project 1 - Three Card Monte
*Created by Odunayo Obajuluwa - June 16, 2017*

 **General Assembly, Chicago - WDI Course**




## User Stories & Breakdown
One-player game where user is dealt 3 cards. The cards are flipped over and then shuffled and user earns points by following the "Queen of Hearts" and flipping the right card.

**Game flow**
* Click + or - to make a wager
* Click shuffle button to flip over and shuffle cards
* Flip over the Queen of Hearts
* Levels advance and cards move faster as the user advances

**Scoring**
* User earns or loses the amount wagered before each turn
* Once user is out of point, the game ends

## Initial Wireframe
![alt text](https://obajuluwa3.github.io/3-Card-Monte/3-Card-Monte-wireframe.jpg "wireframe")

## Original Pseudocode
- Put cards on the screen in random order
- Highlight target card
- On click of shuffle button:
	- Flip cards
	- Shuffle cards
- On click of a card:
	- Flip the card to reveal
	- Then display message
		- If card is queen of hearts, “Correct!” displays
			- Cards are reset facing up on the screen
			- Score goes up by 1
			- If score is 1 more than a multiple of 10, Level goes up by 1
		- If card is not queen of hearts, “Game over” displays
			- Cards are reset facing up on the screen
			- Score is reset
			- Level is reset

## Technologies Used
* HTML5
* CSS3
* JavaScript/JQuery
* Adobe Illustrator
* Draw.io

## Project Planning
Check out my Project 1 Trello Board [here](https://trello.com/b/guS21SVL).

## Possible further development..
* Add Theme music - I'd like to add some music that plays during gameplay. I could probably do this by linking in the sound file in the HTML and triggering it in JavaScript
* Refine Shuffling & flipping animation - I would have liked to make the shuffling and flipping animations look more natural by perhaps using keyframe animations in CSS
* Create a mobile version of the game

### Inspirations & References
- www.freepik.com
- www.stackoverflow.com
- www.css-tricks.com

