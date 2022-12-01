# roulette
Java Implementation of a Roulette Wheel

The goal of this project is to identify an ideal gambling strategy for betting on a traditional single 0 roulette wheel.
The European roulette wheel contains 37 pockets number 0-36.
Each pocket has a colour of either green, red, or black. There are 18 black pockets, 18 red pockets, and a single green pocket which is the 0 pocket.
A ball is spun around the wheel and winning bets match the attributes of the pocket that the ball lands on: color, parity, or pocket value.

It is assumed that the wheel is fair, and the chance of the ball landing in any of the 37 pockets is equal.

The success criteria of a gambling strategy are as follows:
- The expected return to the player of the strategy is maximized
- The strategy is effective at managing the player's bankroll, in other words the volatility of the strategy is low.
- The strategy is simple for a human to employ without requiring additional aids from the computer

Things to do:
- Design class structure
- Generate gambling strategies
- Identify specific metrics of how gambling strategies will be evaluated
