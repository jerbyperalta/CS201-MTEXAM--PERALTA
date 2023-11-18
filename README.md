var lastName = "PERALTA" a = 3;var
const sum = 100 + 50;finale = a * sum;
let add x = "reference";
let output = x + PERALTA;
console.log(output);

// Problem Scenario 2
let x = 5;
let y = 2;
console.log(x + y); // addition;
console.log(x - y); // subtraction;
console.log(x * y); // multiplication;
console.log(x / y); // division;
console.log(x % y); // modulus;

// Problem Scenario 3
let incrementValue = x + y;
console.log(++incrementValue);

// Problem Scenario 4
let decrementValue = x + y;
console.log(--decrementValue);Test 1.B → probFive.js// Problem Scenario 5
let x = 10;
let y = 5;
let numberOfIterations = 10;
let iterations = 0;

while (iterations < numberOfIterations) {
    if (x > y) {
        alert("True");
        break;
    } else {
        alert("False");
    }
    iterations++;
}Test 1.C → probSix.js// Problem Scenario 6
const users = [{ username: 'admin', password: 'admin@2023' }];

function login(username, password) {
    for (const user of users) {
        if (user.username === username && user.password === password) {
            return true;
        }
    }
}

let enteredUsername = prompt("Enter username:");
let enteredPassword = prompt("Enter password:");

if (login(enteredUsername, enteredPassword)) {
    alert('Successfully logged in!');
} else {
    alert('Invalid username or password. Please try again.');
}
