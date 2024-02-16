<link rel="stylesheet" type="text/css" href="../assets/content.css">
<h1 class="custom-header">Notes</h1>

# Introduction to JavaScript

## What is JavaScript?

* JavaScript is a powerful language which helps build dynamic web pages.

## Console

* The `console` keyword in JavaScript is an object which contains various functions and other data. 
* One of these functions is `.log()`, which helps print or log something to the console.
* The `console.log()` method is the JavaScript equivalent of python's `print()` function or C++'s `std::cout` function.
* The following statement prints '5' to the console:
```
console.log(5);
```
* You might have noticed a semicolon<b><i>(i)</i></b> at the end of the statement. Semicolons in JavaScript are _optional_, however, it is recommended to use semicolons.

## Comments

* Single line comments can be made using `//`
```
// This runs
console.log(53) // this runs
// It still runs
```
* Multi-line comments can be made using `/* */`. Anything between the slash-star and star-slash is a comment.
```
/*
This
is
a multiline
comment.
*/
```	

## Data Types

* Detail explanations can be found [here](https://www.codecademy.com/resources/docs/javascript/data-types?page_ref=catalog).
* There are 8 fundamental data types in JavaScript
	* Number
		* Any number including decimal numbers. E.g. 1, 2, 5, 5891.23, 1299
	* BigInt
		* Any integer number greater than 2<sup>53</sup>-1 or lesser than -2<sup>53</sup>-1, with the character 'n' appended to the end of the number
	* String
		* Any sequence of characters one can see on their keyboard, including but not limited to, alphabets, letters, special characters, symbols. Can be written in single-quotes, `'...'` or double-quotes, `"..."`.
	* Boolean
		* Only has two values, `true` or `false`
	* Null
		* Has the value of `null`, which denotes the absence of a value
	* Undefined
		* Has the values of `undefined`, which denotes the non-existence of a value
		* Is different than `null`, even though it defines the absence of a value