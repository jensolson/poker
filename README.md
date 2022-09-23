# poker
My python implementations of two of my favorite poker hand evaluators from Coding the Wheel's [roundup](https://www.codingthewheel.com/archives/poker-hand-evaluator-roundup/):

* v4 calculates pre- and post-flop equity for randomly generated or user-specified hole cards. Accepts 5-card hands
  - Hash scheme courtesy of Cactus Kev's 5-card [hand evaluator](https://suffe.cool/poker/evaluator.html)
  - Attached CSV file is of 7,462 ranked [equivalence classes](https://suffe.cool/poker/7462.html)

* v6 is my python implementation of the famous 2+2 evaluator described in the roundup above. Accepts 7-card hands 
  - Up to 40x+ faster than looping through 21 (choose(7,5)) combinations of 5-card hands on my machine. 
  - v6 requires the HandRanks.dat file found at [Christoph Schmalhofer's github](https://github.com/christophschmalhofer/poker/blob/master/XPokerEval/XPokerEval.TwoPlusTwo/HandRanks.dat)
