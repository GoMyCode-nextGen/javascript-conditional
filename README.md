# Boolean, Operators and Conditionals Exercises
## Basic Requirements
1.Write a function called returnTrue that takes no parameters and returns true when invoked.
```js
function returnTrue(){
//Write your code here
}
returnTrue() -> true
 ```

2.Write a function called returnFalse that takes no parameters and returns false when invoked.
```js
function returnFalse( ) { 

//Write your code here

 }

returnFalse() -> false
```


3.Write a function called isEven that takes a number as a parameter and returns true if the number is even and false if it is odd.
```js
function isEven(number) { 

//Write your code here 

} 

isEven(2) -> true isEven(3) -> false

```


4.Write a function called isOdd that takes a number and returns true if the number is odd and false if it is even.
```js
function isOdd(number) {

//Write your code here

}

isOdd(3) -> true 

isOdd(2) -> false
```


5.Write a function called isGreaterThan10 that takes a number as a parameter and returns true if the number is greater than 10 and false if it is not.

```js
function isGreaterThan10(number) {

 //Write your code here

 }

 isGreaterThan10(5) -> false 

isGreaterThan10(10) -> false 

isGreaterThan10(11) -> true

```


6.Write a function called isLessThan30 that takes a number as a parameter and returns true if the number is less than 30 and false if it is not.
```js
function isLessThan30(number) {

 //Write your code here 

}

 isLessThan30(5) -> true 

isLessThan30(30) -> false 

isLessThan30(32) -> false

```


7.Write a function called isEqualTo10 that takes a number as a parameter and returns true if the number is equal to 10 and false if it is not

```js
function isEqualTo10(number) {

 //Write your code here

 }

 isEqualTo10(1) -> false

 isEqualTo10(10) -> true 

isEqualTo10(15) -> false
```

8.Write a function called isGreaterOrEqualTo15 that takes a number as a parameter and returns true if the given number is greater than or equal to 15 and false if it is not.
```js
function isGreaterOrEqualTo15(number) { 

//Write your code here

}

 isGreaterOrEqualTo15(0) -> false

 isGreaterOrEqualTo15(15) -> true

isGreaterOrEqualTo15(20) -> true
```

9.Write a function called isLessOrEqualTo8 that takes a number as a parameter and returns true if the given number is less than or equal to 8 and false if it is not.
```js
function isLessOrEqualTo8(num1) { 

//Write your code here 

}

 isLessOrEqualTo8(2) -> true 

isLessOrEqualTo8(8) -> true 

isLessOrEqualTo8(12) -> false

```
## More Practice
1.Write a function called isLessThan that takes two numbers as parameters and returns true if num1 is less than num2 and false if otherwise.
```js
function isLessThan(num1, num2) {

 //Write your code here 

}

 isLessThan(2, 3) -> true

 isLessThan(3, 2) -> false 

isLessThan(3, 3) -> false

```
2.Write a function called isEqualTo that takes two numbers as parameters and returns true if num1 is equal to num2 and false if otherwise.
```js
function isEqualTo(num1, num2) {

 //Write your code here 

}

 isEqualTo(3, 3) -> true 

isEqualTo(3, 2) -> false


```

3.Write a function called isOldEnoughToDrive that takes an age as a parameter and returns true if the person’s age is old enough to drive. Note: In Jordan, you can get a driving licence when you’re 18.
```js
function isOldEnoughToDrive(age) {

 //Write your code here 

} 

isOldEnoughToDrive(12) -> false

 isOldEnoughToDrive(18) -> true

 isOldEnoughToDrive(20) -> true
```

4.Write a function called isValidPassword that takes a password as a parameter and returns true if that password is equal to or longer than 8 characters and false if the password is less than 8. HINT: Use “.length”.
```js
function isValidPassword(password) {

 //Write your code here

 }

 isValidPassword(“hello”) -> false

 isValidPassword(“password”) -> true 

isValidPassword(“strongPassword”) -> true
```

5.Write a function called longerString that takes two strings as parameters and returns the longest string and returns “both” if they are the same length.
```js
function longerString(string1, string2) {

 //Write your code here 

 }

 longerString(“cat”, “kitty”) -> “kitty”

 longerString(“Hello”, “Hi”) -> “Hello” 

longerString(“Hello”, “World”) -> “both”
```

6.Write a function called opposite, that takes a boolean value as a parameter and returns the opposite of that value.
```js
function opposite(boolean) {

 //Write your code here 

 } 

opposite(true) -> false 

opposite(false) -> true

```
## Advanced
1.Write a function called rectAreaGreaterThan50 that takes the length and width of a rectangle and returns true if its area is greater than or equal to 50, and false if it's less than 50.
```js
function rectAreaGreaterThan50(length, width) {

 //Write your code here

 } 

rectAreaGreaterThan50(10, 6) -> true 

rectAreaGreaterThan50(10, 5) -> true 

rectAreaGreaterThan50(2, 3) -> false
```

2.Write a function called budgetStatus that takes a number as a parameter, and returns a string stating the status of your budget. If the number is greater than 250, the result should be an "over budget", If the number is less than or equal to 250, the result should be an "Under budget".
```js
function budgetStatus(number) { 

//Write your code here 

 } 

budgetStatus(260) -> “over budget” 

budgetStatus(250) -> “under budget” 

budgetStatus(240) -> “under budget”
```
