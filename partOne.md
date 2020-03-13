### @activities true

```blocks
sprites.onOverlap(SpriteKind.Player, SpriteKind.Enemy, function (sprite, otherSprite) {
    game.over(false)
})

```
## Test your game and Next Steps 
### Test your game and Next Steps @unplugged
**This tutorial is now complete.** 

You can test your game to check that each time you add in a red block in your level tilemaps an enemy appears 
and that when you touch the enemy the game ends with a Game Over message. 

For example: you may want to learn how to do the following

* Add player lives
* Add moving enemies. 

This tutorial is one of many allowing you add different Game Element on the home page of this Platformer Making Course.

## Part One Test  
### A part one test step two

We now code what happens when our player overlaps with the enemy ``||variables:snake||``. 
Drag in an on player overlap with block from Sprites. Set the second value to be Enemy. 
Inside the block drag in from Game block of ``||game:game over||`` and keep it set to **Lose**. 
