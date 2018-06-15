# Tennis Scoring Kata

*GOAL:* Write a program that will tell you the proper tennis scoring given two integer point values. For example:

```javascript
tennisScore(3, 0); // => "Forty-Love"
// or
new TennisScore(4, 5).score(); // => "Advantage"
```

## Tennis Scoring Rules

* A game is won by the first player to have won at least four points in total and at least two points more than the opponent.
* The running score of each game is described in a manner peculiar to tennis: scores from zero to three points are described as "Love", "Fifteen", "Thirty", and "Forty" respectively.
* If less than three points have been scored by each player and they are tied, the second part of the score would be "All" (ex. "Love-All", "Fifteen-All", "Thirty-All").
* If at least three points have been scored by each player, and the scores are equal, the score is "Deuce".
* If at least three points have been scored by each side and a player has one more point than his opponent, the score of the game is "Advantage" for the player in the lead.