# gamblers-problem
A dynamic programming solution to the classic gambler's problem introduced in Sutton and Barton's RL book.

Problem statement - The gambler has a stake s between 0 and 100.  At each play he wagers an integer <= s.  He wins that much with prob p, else he loses that much.  If he builds his stake to 100 he wins (thus he never wagers more than (- 100 s)); if his stake falls to 0 he loses.

The solution (Or rather one of the possible solutions. It all boils down to the finer details, like how ties are broken the compiler etc...)

<img src="https://github.com/kraftpunk97/gamblers-problem/blob/master/solution.png">
