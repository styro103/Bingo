Bingo
=====

I.) A virtual card is generated, which contains five columns of
five numbers, noted as follows:
The 1st column (B) has five random numbers from 1-20.
The 2nd column (I) has five random numbers from 21-40.
The 3rd column (N) has five random numbers from 41-60.
The 4th column (G) has five random numbers from 61-80.
The 5th column (O) has five random numbers from 81-100.
The card generated for all 5 games in this problem looks
like...
B I N G O
--- --- --- --- ---
16 37 44 61 90
5 40 55 63 100
20 39 51 73 94
2 25 60 71 86
11 22 47 79 82
II.) The computer generates a random list of 100 distinct
numbers, to be used as the numbers called out during game play.
Sample Input for the first game:
43,35,13,52,34,16,62,29,04,78,30,73,97,25,89,23,96,03,53,14,
55,61,76,88,80,09,37,81,99,18,08,65,95,31,90,05,75,40,44,22,
65,100,95,38,28,39,32,54,60,89,30,33,51,70,16,46,83,21,58,27,
88,06,03,13,84,43,68,66,97,10,93,42,71,57,26,91,96,35,90,99,
45,12,87,61,56,08,72,79,36,59,44,37,92,20,01,48,52,53,63,02,
98,41,25,73,23,22,17,18,31,75,69,11,34,78,62,09,15,50,07,19,
III.) As the numbers from the list are called out, a comparison
to your card is performed. If your card contains the number
called out, a marker(*) is placed next to the entry of your card.
IV.) The game is over when your card has markers in all of the entries across any row, down any column, along any full diagonal, or in all four corners.
V.) You win the game if the game ends (it is over) before the 50th number is called out from the list.
VI.) The results of the game should include the game number, final card (numbers should be right-aligned under the BINGO letters, asterisks to the right), the list of numbers called out, the number of integers called out, and whether the game was won or lost.
-Game 1-
========
B I N G O
--- --- --- --- ---
16* 37* 44* 61* 90*
5* 40* 55* 63 100
20 39 51 73* 94
2 25* 60 71 86
11 22 47 79 82
The numbers called out during the game were...
43,35,13,52,34,16,62,29,04,78,30,73,97,25,89,23,96,03,53,14,
55,61,76,88,80,09,37,81,99,18,08,65,95,31,90,05,75,40,44.
This card was a WINNER in Game 1 because it needed
only 39 numbers to end the game.

==============================================================
Your program is to find the disposition of five games. There will be 500 numbers in the data file. If there are remaining numbers after a game concludes, they should be discarded before the next game commences. In the sample, numbers 40 to 100 would be discarded before game 2 is played.
All 500 numbers will be separated by commas. Game outputs should be separated by a horizontal line of =’s, as shown above.
