# Javascript Homework

1.  Variables

    - https://www.youtube.com/watch?v=cXUWYZXru6o (7 min video)
    - https://www.codeanalogies.com/jsconstruction/ (interactive game)

2.  Conditions
    - https://blog.codeanalogies.com/2018/06/18/javascript-booleans-explained-by-going-to-court/ (reading)

## Assignment Operator

Without running the following code, try to determine:

```js
let a = 1;
let b = "bongos";
let c = true;

a = b;
b = c;
c = a;
```

### Your solution here:

1.  What is `a`?

```
a is bongos
```

2.  What is `b`?

```
b is true
```

3.  What is `c`?

```
c is bongos
```

## Concatenation

Use the `+` operator to concatenate these strings together within a `console.log()`: "Please", "squeeze", "the", "cheese". Make sure there are spaces in-between each word.

```js
const firstWord = "Please";
const secondWord = "squeeze";
const thirdWord = "the";
const fourthWord = "cheese";
```

Result should be:

```js
"Please squeeze the cheese";
```

### Your solution here:

4.  Fill in the `console.log()`?

```js
console.log(firstWord + " " + secondWord + " " + thirdWord + " " + fourthWord);
```

Output a console log `The sum of 5 and 10 is 15` where the values for 5 and 10 are saved to variables, and where 15 comes from those variables being summed.

```js
const num1 = 5;
const num2 = 10;
```

### Your solution here:

5.  How can we make `num3` equal to the sum of `num1` and `num2`?

```js
const num3 = num1 + num2;
```

6.  Use variables `num1`, `num2` and `num3` to fill in the `console.log()` to complete the sentence:

> The sum of 5 and 10 is 15

```js
console.log(`the sum of ${num1} and ${num2} is ${num3}`);
```

## Comparisons

By just looking at the following expressions, determine in your mind whether or not each will evaluate to true or false

```
a) 999 > 999
b) 999 === 999
c) 999 !== 999
d) -5 >= -4
e) 100 <= -100
f) 20 + 5 < 5
g) 81 / 9 === 9
h) 9 !== 8 + 1
```

### Your solution here:

7.  Write `true` or `false` based on the list above

```
a) false
b) true
c) false
d) false
e) false
f) false
g) true
h) false
```

## Conditionals

Declare a variable equal to a number 0 to 100

Write a conditional statement that...

- If it is a multiple of 3, print “Fizz” instead of the number.
- If it is a multiple of 5, print “Buzz” instead of the number.
- If it is a multiple of both 3 and 5, print “FizzBuzz” instead of the number.
- Otherwise, print the number

### Your solution here:

8.  Write your javascript solution below

```js
const num = 30;
// 1. check if num divisable by 5 and 3 if so print "FizzBuzz"
// 2. check if num divisable by 3 if so print "Fizz"
// 3. check if num divisable by 5 if so print "Buzz"
// otherwise print num
if (num % 5 === 0 && num % 3 === 0) {
  console.log("FizzBuzz");
} else if (num % 3 === 0) {
  console.log("Fizz");
} else if (num % 5 === 0) {
  console.log("Buzz");
} else {
  console.log(num);
}
```

#### BONUS

9.  Research a [loop](https://javascript.info/while-for) so that your condition runs on every number from 0 to 100

```js
let i = 0;
while (i <= 100) {
  console.log(i);
  i++;
}

// another solution
for (let i = 0; i <= 100; ++i) {
  console.log(i);
}
```

10. Research a [function](https://javascript.info/function-basics) so that your condition runs on every number from 0 to whatever number is passed into the function

```js
// the input is number
function range(number) {
  // 1. check if the input {number} is less than or equal to 0
  if (number <= 0) {
    // return will stop the function from execution
    return console.log("the number should be greater than 0");
  }

  // 2. loop from 0 to {number} and print i in each iteration
  let i = 0;
  while (i <= number) {
    console.log(i);
    i++;
  }
}
```

# Additional Resources

For more practice read about...

- https://javascript.info/variables
- https://javascript.info/types
- https://javascript.info/operators
- https://javascript.info/comparison
- https://javascript.info/ifelse
- https://javascript.info/logical-operators
