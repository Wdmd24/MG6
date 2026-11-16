# MG6


1. The for loop will finished before the update finished. As a result, if I write a for loop that is extremely large, it will lag the game.

2. Since the collider of the cat will only disappear when player is going upward. Because the ground is always under the player, if player wants to pass through it, player's vertical speed will be negative, which causes the collider reopen. 
