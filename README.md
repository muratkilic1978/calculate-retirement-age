# Retirement Age Calculator Exercise
## Birthdate State Pension Age Guidelines

| Birthdate                           | State Pension Age  |
|--------------------------------------|--------------------|
| Born before 1. januar 1956            | 66 years         |
| January 1, 1956 – December 31, 1962   | 67 years           |
| January 1, 1963 – December 31, 1966   | 68 years           |
| January 1, 1967 or later              | 69 years           |


## Introduction

In this exercise, you will create a Retirement Age Calculator using JavaScript. The goal is to prompt the user for their birthdate, calculate their pension age based on the provided guidelines, and display the result using `console.log`.

## Instructions

1. Use the provided table to determine the pension age based on the user's birthdate.
2. Prompt the user to enter their birthdate using the `prompt` function.
3. Calculate the pension age using JavaScript, taking into account the guidelines provided.
4. Display the result using `console.log`, informing the user about their retirement age.

## Example Output

```javascript
// Example: User inputs birthdate '1990-05-15'
let birthdate = new Date('1990-05-15');
let retirementAge;

// Perform calculations based on the provided guidelines
// ...

// Display the result
console.log(`Your pension age is ${retirementAge} years.`);
