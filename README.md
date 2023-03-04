# RCT101-Assignment
## what is the difference between Props and State? 
`state` to track the current list of items as well as the text that the user has entered and Conceptually, components are like JavaScript functions. They accept arbitrary inputs called “props” and return React elements describing what should appear on the screen.
## Explain the useState API?
The useState() is a Hook that allows you to have state variables in functional components . so basically useState is the ability to encapsulate local state in a functional component. React has two types of components, one is class components which are ES6 classes that extend from React and the other is functional components. Class components a Component and can have state and lifecycle methods: class Message extends React. The  useState hook is a special function that takes the initial state as an argument and returns an array of two entries.  UseState encapsulate only singular value from the state, for multiple state need to have useState calls.
### Syntex:- const [state, setState] = useState(initialstate)
## Explain the how map, filter, reduce work  ?
 ## MAP 
 The map() method is used for creating a new array from an existing one, applying a function to each one of the elements of the first array.
### syntex:-var new_array = arr.map(function callback(element, index, array) { // Return value for new_array  }[, thisArg])
In the callback, only the array element is required. Usually some action is performed on the value and then a new value is returned.
## REDUCE
The reduce() method reduces an array of values down to just one value. To get the output value, it runs a reducer function on each element of the array.

## Syntax
## arr.reduce(callback[, initialValue])
The callback argument is a function that will be called once for every item in the array. This function takes four arguments, but often only the first two are used.
## FILTER
The filter() method takes each element in an array and it applies a conditional statement against it. If this conditional returns true, the element gets pushed to the output array. If the condition returns false, the element does not get pushed to the output array.

### Syntax
var new_array = arr.filter(function callback(element, index, array) {
    // Return true or false
}[, thisArg])
The syntax for filter is similar to map, except the callback function should return true to keep the element, or false otherwise. In the callback, only the element is required.

### Examples
In the following example, odd numbers are "filtered" out, leaving only even numbers.


const numbers = [1, 2, 3, 4];
const evens = numbers.filter(item => item % 2 === 0);
console.log(evens); // [2, 4]

