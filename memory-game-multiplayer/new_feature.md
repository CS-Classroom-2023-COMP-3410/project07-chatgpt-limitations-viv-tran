### New Feature Description
The project I was iteratively developing on was the memory game project. The feature that I wanted to add was "head to head" functionality. Memory is a multi-player game, so I wanted to add to the game a turn system. The game would display which player's turn it was, and it would also keep track of the number of pairs/matches each player had gotten. The idea was that if you are sitting next to your friend, you could take turns flipping cards and getting matches.

### Why it is a reaonable feature
I honestly thought this was a very reasonable feature to add for an all front end project. This is reasonable becayse this sort of thing is definitely acheivable with just HTML, CSS, and JS. 

### How it was supposed to work
This was supposed to work by using JS to keep track of which player's turn it was, and then displaying that to the screen. Once the player made their turn, if they got a match, then the number of matches for that player would increment and display on the screen. There was a small wrinkle that made it slightly more complex, but if a player got a match, then they got to keep their turn until they didn't get a match. Once a player flips two cards and does not get a match, the turn transfers to the other player. This process repeats until the end of the game.

### How ChatGPT Failed
Chat GPT failed miserably at this, it wasn't even close. The main issue is that the grid of cards (the most core part of the game) simply was no longer on the screen. The game was working perfectly before trying to add this feature. I gave GPT two tries to fix this, basically just telling it that the grid was completely missing. After failing twice, I decided that maybe it was my fault. I updated my description of the new feature to be even more detailed, and then asked again. The grid was still missing. I gave it three tries with the new description, and each time, the grid was still missing. So in the end, it ended up failing 5 times at this. For some reason it just couldn't fix it.

