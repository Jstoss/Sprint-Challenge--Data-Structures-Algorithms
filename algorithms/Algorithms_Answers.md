Add your answers to the Algorithms exercises here.

EX1:

A) O(n), as the number increases, the number of iterations also increases at a steady rate. In this case for example, if n is 3, it'll loop 3 times, but if n is 10, it'll loop 10 times.

B) O(n^c), nested loops that all get their length based off n means each one will grow as n grows

C) O(n), as n increases, so will the number of calls, but nothing in the code will modify the number of times it's called

EX2:
Start at the floor in the middle of the building, drop an egg, and if it doesn't break, go up half the floors between you and the top, or if it does break, go down to the floor halfway between current and the floor. Then repeat with the bottom floor and top floor being replaced with the previous floor depending on going up or down, until you find the floor where it'll break with the floor underneath where it doesn't break.
