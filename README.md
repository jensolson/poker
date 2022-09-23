# poker
v4 calculates pre- and post-flop equity for randomly generated or user-specified hole cards using Kevin Suffecool's 5-card hand evaluator.

Hash scheme courtesy of https://suffe.cool/poker/evaluator.html

Attached CSV file is of 7,462 ranked equivalence classes found here: https://suffe.cool/poker/7462.html

v6 is my python implementation of the famous 2+2 evaluator. The 2+2 lookup tables evaluate the best 5-card hold'em hand from a 7-card input. Up to 40x+ faster than looping through 21 (choose(7,5)) combinations of 5-card hands on my machine. 

v6 requires the HandRanks.dat file found here: https://github.com/christophschmalhofer/poker/blob/master/XPokerEval/XPokerEval.TwoPlusTwo/HandRanks.dat
