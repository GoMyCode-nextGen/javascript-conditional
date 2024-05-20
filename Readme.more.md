# Logical operator && More Conditionals|| W1.D3.02
Exercises
## Basic Requirements

1.Evaluate the following statements in the console and compare the results:
```js
true 
!true 
!false
```
2.Evaluate the following statements in the console and compare the results:
```js
true && true 
true && false ,,false && true 
false && false
```
3.Evaluate the following statements in the console and compare the results:
```js
true || true 
true || false 
false || true 
false || false
```
4.Evaluate the following statements in the console and compare the results:
```js
3 > 4 
4 > 3 
!(4 > 3) 
4 <= 4 && 5 < 6 
3 < 4 && 8 < 12 
3 === 3 || 4 === 4 
3 === 2 || 4 === 4
```
5.Evaluate the following statements in the console and compare the results:
```js
true && (true || false) 
false && (true && true) 
(true || false) && (true || false) 
3 > 2 || (false && true)
 4 > 5 || (2 < 3 || 3 > 5)
```
6.Write a function called opposite that takes a boolean as parameter and returns the opposite.
```js
 function opposite(boolean) {
   //Write your code here 
}  
opposite(true) -> false 
opposite(false) -> true
```
7.Write a function called greaterThan5 that takes two numbers as parameters and returns true if one of the numbers is greater than 5 and false if none of the numbers are greater than 5.
```js
  function greaterThan5(num1, num2) {
   //Write your code here 
}  

greaterThan5(1, 6) -> true 
greaterThan5(5, 5) -> false 
greaterThan5(1, 4) -> false
```
8.Write a function called allGreaterThan5 that takes two numbers as parameters and returns true if both numbers are greater than 5 and false if one or both of them is not.
```js
function allGreaterThan5(num1, num2) {
   //Write your code here 
}  
allGreaterThan5(6, 7) -> true 
allGreaterThan5(2, 7) -> false
```
9.Write a function called largerThan5AndLessThan20 that takes a number as a parameter and returns true if it is larger than five and less than 20 and false if otherwise.
```js
function largerThan5AndLessThan20(number) {
   //Write your code here 
}  
largerThan5AndLessThan20(12) -> true 
largerThan5AndLessThan20(21) -> false 
largerThan5AndLessThan20(5) -> false
```
10.Write a function called not6AndLessThan10 that takes a number as a parameter and returns true if the number is not equal to 6 and less than 10 and false if otherwise.
```js
function not6AndLessThan10(number) {
   //Write your code here 
}  
not6AndLessThan10(6) -> false 
not6AndLessThan10(7) -> true 
not6AndLessThan10(10) -> false
```
11.Write a function called largerThan3AndLessThan18 that takes three numbers as parameters and returns true if all 3 numbers are within the range and false if one or more are not.
```js
function largerThan3AndLessThan18(num1, num2, num3) {
   //Write your code here 
}  
largerThan3AndLessThan18(2، 4، 20) -> false 
largerThan3AndLessThan18(5، 6، 7) -> true 
largerThan3AndLessThan18(3، 6، 18) -> false
```
12.Write a function called cloudyAndRainy that takes two strings and returns true if it’s cloudy and rainy and false otherwise.
```js
function cloudyAndRainy(string1, string2) {
   //Write your code here 
}  
cloudyAndRainy(“cloudy”, “rainy”) -> true 
cloudyAndRainy(“clear”, “rainy”) -> false
```
13.Write a function called weatherActivities that takes a type of weather (as a string) and returns an activity someone can do in that weather. Please include activities for at least four types of weather conditions.
```js
function weatherActivities(weather) {
   //Write your code here 
}  
weatherActivities(“rainy”) -> “hot chocolate” 
weatherActivities(“sunny”) -> “running”
```
14.Write a function called evenAndGreaterThan7 that takes a number as a parameter and returns true if the number is even and greater than 7 and false if otherwise.
```js
function evenAndGreaterThan7(number) {
   //Write your code here 
}  
evenAndGreaterThan7(6) -> false 
evenAndGreaterThan7(8) -> true 
evenAndGreaterThan7(9) -> false
```
## More Practice

1.Write a function called areValidCredentials that takes name and password as a parameter and returns true if the name is longer than 3 characters, AND, the password is at least 8 characters long. Otherwise, it returns false.
```js
 areValidCredentials(name, password) {;;   //Write your code herefunction ;;}  ;;areValidCredentials(“hi”, “password123”) -> false ;;areValidCredentials(“Nancy”, “123”) -> false ;;areValidCredentials(“Ahmed”, “password”) -> true
```
2.Write a function called findMinLengthOfThreeWords that takes three words as parameters and returns the length of the shortest word.
```js
function findMinLengthOfThreeWords(string1, string2, string3) {
   //Write your code here 
}

findMinLengthOfThreeWords(“hi”, “hello”, “marhaba”) -> 2 
findMinLengthOfThreeWords(“1234”, “5678”, “12345678”) -> 4
```
3.Write a function called findMaxLengthOfThreeWords that takes three words as parameters and returns the length of the longest word.
```js
function findMaxLengthOfThreeWords(string1, string2, string3) {
   //Write your code here 
}  
findMinLengthOfThreeWords(“hi”, “hello”, “marhaba”) -> 7 
findMinLengthOfThreeWords(“1234”, “12345678”, “12345678”) -> 8
```
4.Write a function called guessMyNumber that takes a number as a parameter and compares it to a random number between 0 and 5, and returns one of the following strings: 'You guessed my number!' if the number matches the random number. 'Nope! That wasn't it!' if the number did not match the random number. HINT: Look at these functions on MDN to learn how they work: Math.random, Math.floor and Math.ceil.
```js
function guessMyNumber(number) {
   //Write your code here 
}  
guessMyNumber(5) -> “You guessed my number!” 
guessMyNumber(5) -> “Nope! That wasn’t it!”
```
## Advanced
1.Write a function called or that takes two boolean statements and it functions as an OR operator but write it using only AND and NOT operators.
```js
function or(statement1, statement2) {
   //Write your code here 
}  
or(true, true) -> true 
or(true, false) -> true 
or(false, true) -> true 
or(false, false) -> false 
or(1 < 3, 5 > 7) -> true
```
2.Write a function called and that takes two boolean statements and it functions as an AND operator but write it using only OR and NOT operators.
```js
function and(statement1, statement2) { 
  //Write your code here 
}

and(true, true) -> true 
and(true, false) -> false 
and(false, true) -> false 
and(false, false) -> false 
and(1 < 3, 5 > 7) -> true 
and(1 < 3, 7 > 5) -> true
```
3.Write a function called shirtWidth that takes a number as a parameter and returns a specific string for four different cases. if the number is greater than or equal to 20, and less than 30, return 'You should select a size S'; if the number is greater than or equal to 30, and less than 40, return 'You should select a size M'; if the number is greater than or equal to 40, and less than 50, return 'You should select a size L'. If none of these conditions is met, return 'You should select a different shirt'.
```js
function shirtWidth(width) {
   //Write your code here 
}  
shirtWidth(25) -> “You should select a size S” 
shirtWidth(35) -> “You should select a size M” 
shirtWidth(45) -> “You should select a size L” 
shirtWidth(100) -> “You should select a different shirt”
```
4.Write a function called playerOneChoice that takes a string representing the choice of Player 1 in a game of rock/paper/scissors as a parameter and returns a specific string of which choice the player has made, it returns: 'Player 1 chose rock'; 'Player 1 chose paper'; 'Player 1 chose scissors'; or, 'Player 1 has chosen poorly!', depending upon the value of the input parameter.
```js
function player1Choice(choice) {
   //Write your code here 
}  
playerOneChoice(“rock”) -> “Player 1 chose rock” 
playerOneChoice(“paper”) -> “Player 1 chose paper”

playerOneChoice(“scissors”) -> “Player 1 chose scissors” 
playerOneChoice(“gun”) -> “Player 1 chose poorly”
```
5.Write a function called convertScoreToGrade that takes a score as a parameter and returns a string representing the letter grade corresponding to the given score as follows: (100 - 90) --> 'A' (89 - 80) --> 'B' (79 - 70) --> 'C' (69 - 60) --> 'D' (59 - 0) --> 'F' If the given score is greater than 100 or less than 0, it should return 'Invalid Score'

 function convertScoreToGrade(score) {
   //Write your code here 
}  
convertScoreToGrade(91) -> “A” 
convertScoreToGrade(80) -> “B” 
convertScoreToGrade(110) -> “Invalid Score”
6.Write a function called convertScoreToGradeWithPlusAndMinus that takes a score as a parameter and returns a string representing the letter grade corresponding to the given score as follows: (100 - 95) --> 'A+' (94 - 90) --> 'A-' (89 - 87) --> 'B+' (86 - 80) --> 'B-' (79 - 77) --> 'C+' (76 - 70) --> 'C-' (69 - 67) --> 'D+' (66 - 60) --> 'D-' (59 - 0) --> 'F' If the given score is greater than 100 or less than 0, it should return 'Invalid Score'.

function convertScoreToGradeWithPlusAndMinus(score) {
   //Write your code here 
}  
convertScoreToGradeWithPlusAndMinus(91) -> “A-” 
convertScoreToGradeWithPlusAndMinus(80) -> “B-” 
convertScoreToGradeWithPlusAndMinus(-10) -> “Invalid Score”
7.Write a function called isItTruthy that takes any value as a parameter and returns the string 'Input is truthy' if the parameter is truthy, otherwise returns 'Input is falsy'.

  function isItTruthy(value) {
   //Write your code here 
} 
 isItTruthy(“anything”) -> “Input is Truthy” 
isItTruthy() -> “Input is Falsy” 
isItTruthy(0) -> “Input is Falsy” 
isItTruthy(“”) -> “Input is Falsy” 
isItTruthy(false) -> “Input is Falsy”
8.Write a function called checkArea that takes area as a parameter and returns true if the input is larger than 48 AND less than 100, otherwise returns false.

function checkArea(area) {
   //Write your code here 
}  
checkArea(50) -> true 
checkArea(100) -> false
9.Write a function called multiply that takes two numbers as parameters and returns true if their multiplication is greater than 50 And less to 150, otherwise returns false.

function checkMultiply(num1, num2) {
   //Write your code here 
}  
checkMultiply(10, 6) -> true 
checkMultiply(7, 7) -> false
