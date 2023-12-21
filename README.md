# Calculator
Calculator

var prompt = require('prompt-sync')();

let n1: number = parseInt(prompt('Please enter your first number:'));
let n2: number = parseInt(prompt('Please enter your second number:'));
let operator: string = prompt('Please enter your operator (+, -, *, /):');

if (operator === '+') {
    console.log(`The answer of ${n1} ${operator} ${n2} = ${n1 + n2}`);
} else if (operator === '-') {
    console.log(`The answer of ${n1} ${operator} ${n2} = ${n1 - n2}`);
} else if (operator === '*') {
    console.log(`The answer of ${n1} ${operator} ${n2} = ${n1 * n2}`);
} else if (operator === '/') {
    console.log(`The answer of ${n1} ${operator} ${n2} = ${n1 / n2}`);
} else {
    console.log('Please select the correct operator');
}


export {};
