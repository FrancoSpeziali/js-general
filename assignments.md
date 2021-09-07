/*

    Assignment 1

    Update the function below to return a value of type "number"

*/

function assignment1() {

    return 123;

}

/*

    Assignment 2

    Update the function below to return a value of type "string"

*/

function assignment2() {

    return 'Single quotation marks';

}

/*

    Assignment 3

    Update the function below to return a value of type "boolean"

*/

function assignment3() {

    return false;

}

/*

    Assignment 4

    Update the function below to return a value of type "object"

*/

function assignment4() {

    return {};

}

/*

    Assignment 5

    Update the function below to return an object with the properties "name" and "id"

*/

function assignment5() {

    return {
        name: "Any name",
        id: 123123
    };

}

/*

    Assignment 6

    Update the function below to return a function

*/

function assignment6() {

    return function () { // anonymous

    };

}

/*

    Assignment 7

    1. Update the function below to accept one argument "name"

    2. Update the function below to return the argument "name"

*/

function assignment7(name) {

    return name;

}

/*

    Assignment 8

    1. Update the function below to accept 2 arguments called "firstName" and "lastName".

    2. Update the function below to return a joined string of "firstName lastName". Including

    the space in between.

    Example: I call the function like so:

    assignment8("John", "Coltrane");

    I expect the result:

    "John Coltrane"

*/

function assignment8(firstName, lastName) {

    return firstName + " " + lastName;

}

/*

    Assignment 9

    1. Update the function below to accept an argument "number"

    2. Update the function so that if the argument "number" is equal to 50,

    the function returns the boolean TRUE

    Otherwise, return FALSE

*/

function assignment9(number) {

    if(number === 50) {
        return true;
    }

    return false;

}

/*

    Assignment 10

    1. Update the function below to accept 2 arguments "number1" and "number2"

    2. Update the function to return the boolean TRUE if "number2" is greater than "number1"

    Otherwise, return FALSE

*/

function assignment10(number1, number2) {

    if(number2 > number1) {
        return true;
    } else {
        return false;
    }

}

/*

    Assignment 11

    1. Update the function below to accept 2 arguments "number1" and "number2"

    2. Update the function to return the boolean TRUE if "number2" is less than "number1"

    Otherwise, return FALSE

*/

function assignment11(number1, number2) {

    if(number2 < number1) {
        return true;
    }

    return false;

}

/*

    Assignment 12

    1. Update the function below to accept 2 arguments "number1" and "number2"

    2. Update the function to return the boolean TRUE if "number2" is greater or equal to "number1"

    Otherwise, return FALSE

*/

function assignment12(number1, number2) {

    if(number2 >= number1) {
        return true;
    }

    return false;

}

/*

    Assignment 13

    1. Update the function below to accept 1 argument "value1"

    2. Update the function to return the boolean TRUE if typeof "value1" is equal to "string"

    Otherwise, return FALSE

*/



function assignment13(value1) {

    if(typeof value1 === "string") {
        return true;
    }

    return false;

}

/*

    Assignment 14

    1. Update the function below to accept 2 arguments "value1" and "value2"

    2. Update the function to return the boolean TRUE if

    typeof "value1" is equal to "string" AND typeof "value2" is equal to "string"

    Otherwise, return FALSE

*/

function assignment14(value1, value2) {

    if(typeof value1 === "string" && typeof value2 === "string") {
        return true;
    }

    return false;

}

/*

    Assignment 15

    1. Update the function below to accept 1 argument "value1"

    2. Update the function to return the boolean TRUE if typeof "value1" is NOT equal to "string"

    Otherwise, return FALSE

*/

function assignment15(value1) {

    // != (not strict) :(
    // !== (strict)! :)

    if(typeof value1 !== "string") {
        return true;
    } else {
        return false;
    }

}

/*

    Assignment 16

    1. Update the function below to accept 1 argument "value1"

    2. Update the function to return the boolean TRUE if

    typeof "value1" is equal to "string" OR typeof "value1" is equal to "number"

    Otherwise, return FALSE

*/

function assignment16(value1) {

    if(typeof value1 === "string" || typeof value1 === "number") {
        return true;
    }

    return false;

}
