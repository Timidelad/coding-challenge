# DAY 1 OF CODING CHALLENGE

## CHALLENGES I COMPLETED FROM A JAVSCRIPTR COURSE ON UDEMY

## Day1 challenge 1

Back to the two gymnastics teams, the Dolphins and the Koalas! There is a new gymnastics discipline, which works differently.Each team competes 3 times, and then the average of the 3 scores is calculated (so one average score per team). A team **only** wins if it has at least double the average score of the other team. Otherwise, no team wins!

## The tasks:

- Create an arrow function _calcAverage_ to calculate the average of 3 scores. This function should have three parameters and return a single number (the average score).
- Create two new variables — _scoreDolphins_ and _scoreKoalas_, and assign the value returned from the _calcAverage_ function to them (you will need to call this function, and pass scores as arguments).
- Create a function _checkWinner_ that takes the average score of each team as parameters (_avgDolphins_ and _avgKoalas_), and then logs the winner to the console, together with the victory points, according to the rule above. Example: _Koalas win (30 vs. 13)_ (use avgDolphins and avgKoalas instead of hard-coded values).
- Use the _checkWinner_ function to determine the winner for both **DATA 1** and **DATA 2**.
- Ignore draws this time. Instead, log _No team wins..._ to the console if there is no winner.

- **TEST DATA 1:** Dolphins scored 44, 23, and 71. Koalas scored 65, 54, and 49.

- **TEST DATA 2:** Dolphins scored 85, 54, and 41. Koalas scored 23, 34, and 27.

**This challenge include if/else statements and functions topic in javascript**

## CHALLENGE 2

## This challenge involves coditional (ternary) operator and function topics

Steven wants you to improve his tip calculator, using the same rules as before — tip 15% of the bill if the bill value is between 50 and 300, and if the value is different, the tip is 20%.

**Your tasks:**

- Write a function _calcTip_ that takes any bill value as an input and returns the corresponding tip, calculated based on the rules above (you can check out the code from the first tip calculator challenge if you need to). Use the function type you like the most. Test the function using a bill value of 100.
- And now let's use arrays! So, create an array called _bills_ containing the test data below
- Create an array called _tips_ containing the tip value for each bill, calculated from the function you created before.
- Create an array _totals_ containing the total values, so the _bill + tip_.
  **TEST DATA:** 125, 555, and 44.
