# WE COVER

*Modern JavaScript for React JS - ES6.*


1. [Getting Started]() 👇

	 
```bash
	 Getting Started - Course Introduction
```


👋  [Babel](https://babeljs.io/repl) : It is a preprocessor for Javascript/ECMAScript. It is mainly used to convert ES6+ code into a backwards compatible version of JavaScript that can be run by older browsers.


```bash
	 const mFunc = () => {
	 	// Func Body
	}
```


```bash
	 ES6 - Variable Creation using "let" and "const"
```


ES6 introduced 2 new ways to create variables.

let: It is a replacement for var.
For example,
let mName = "John";
let mSum = 100;


const: It is used to create variables with constant 
values also known as constants. The variables created using const cannot be updated later in the code.

For example,
const API_URL = "https://api.test.com/v1";


console.clear();

let num1 = 10;
console.log(num1);

let name = "Thenavigo";
let isOldEnough = true;
let See-Docs = [10, 15, 20, 23,];
let blogSD = {
	title: 'See-Docs',
	description: 'See-Docs blog'
}


const num2 = 20;
// num2 = 30;
console.log(num2);


```bash
	 ES6 - Templates Strings
```

It is just a string which allows emedding expressions
inside it. To create a template string you don't use single or double quotes, you use back tick. The expressions are embedded by wrapping them inside ${}.

For example:

const mGreetings = `Hello ${name}`
Here, the expression is a variable.
const moreGreetings = `Hello ${fullName()}`
Here, this expression is a function call.


Example:

```bash
	 console.clear();

	 const firstName = 'See-Docs';
	 const lastName = 'Thenavigo';

	 function getFullName(firstName, lastName) {
	 	return `${firstName} ${lastName}`;
	 }

	 const mGreetings = `Hello ${getFullName(firstName, lastName)}`;

	 console.log(mGreetings);
```



```bash
	 ES6 - Arrow Functions
```

ES6 gives us a new syntax for defining functions using
a fat arrow. Arrow functions bring a lot clarity & code reduction. 

Syntax: 

function greetings(name) {
	return('Welcome' + name);
}

const greetings = (name) => {
	return(`Welcome ${name}`)
}



Example:

```bash
	console.clear();

	function greetings(name) {
		return `Welcome ${name}`
	}ome ${name}

	const mGreetings = (name, age) => {
		return `Welcome ${name} ${age}`
	}

	console.log(greetings('Thenavigo'));
	console.log(mGreetings('Thenavigo', 50));
```



```bash
	 ES6 - Rest and Spread Operator (PART 1)
```

Syntax:

```bash
	 console.clear();

	 const mSum = (...args) => console.log(args);

	 mSum(1, 2, 3, 4, 5);
```


Example :

```bash
	 console.clear();

	 const mSum = (num1, num2, ...args) => {
	 	console.log(num1);
	 	console.log(num2);
	 	console.log(args);
	 	let sum = num1 + num2;
	 	for(let i=0; i<args.length; i++) {
	 		sum += args[i]
	 	}

	 	console.log(sum);
	 }

	 mSum(1, 2, 3, 4, 5, 6, 7, 8);
```



```bash
	 ES6 - Rest and Spread Operator (PART 2)
```
