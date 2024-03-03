# SomeContract

`SomeContract` is a sample contract written in Move, a programming language designed for the Move blockchain.

## Overview

This contract defines a structure `SomeStruct` containing four variables and three functions. It also includes a resource `SomeResource` with its own variable and function. Additionally, the contract provides public functions to interact with the defined structures and resources.

## SomeStruct

### Variables
- `a`: Publicly readable and settable string variable.
- `b`: Publicly readable and settable string variable.
- `c`: Accessible only within the contract, string variable.
- `d`: Accessible only within the structure itself, string variable.

### Functions
- `publicFunc()`: Public function with no parameters.
- `contractFunc()`: Accessible only within the contract, no parameters.
- `privateFunc()`: Accessible only within the structure itself, no parameters.
- `structFunc()`: Public function demonstrating an area marked as "AREA 1."

### SomeResource

- `e`: Publicly readable and settable integer variable.

### Functions
- `resourceFunc()`: Public function demonstrating an area marked as "AREA 2."

## Contract Functions

- `createSomeResource()`: Creates and returns an instance of `SomeResource`.
- `questsAreFun()`: Public function demonstrating an area marked as "AREA 3."

