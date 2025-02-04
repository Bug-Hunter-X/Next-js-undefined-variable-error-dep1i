# Next.js Undefined Variable Error

This repository demonstrates a common error in Next.js applications: attempting to access a property of an undefined variable. The error occurs in the `About` page when trying to access `nonExistentVariable.someProperty`, where `nonExistentVariable` is not defined.

## Bug

The `about.js` file contains the error.  The `nonExistentVariable` is declared but not initialized, leading to a runtime error when its property is accessed. 

## Solution

The `aboutSolution.js` file shows how to fix the error by using optional chaining or nullish coalescing to handle potential undefined values.

## How to reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Navigate to `/about`.
5. Observe the error.
