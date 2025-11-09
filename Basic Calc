let input = require("prompt-sync")();

// --- Declarations ---
let numberA;
let numberB;
let CalcResults = [];

console.log("Basic Calculator");

//While Loop
while (true) {

  let inputA = input("Enter the first number (A): ").trim();
  let inputB = input("Enter the second number (B): ").trim();
  
  // 1. Blank inputs
  if (inputA === "" || inputB === "") {
    console.log("\n❌ ERROR: Cannot leave input blank. Please enter a number.");
    continue; 
  }
  
  numberA = parseInt(inputA);
  numberB = parseInt(inputB);

  if (numberA === 0 || numberB === 0 || numberA !== parseInt(inputA) || numberB !== parseInt(inputB)) {
    console.log("\n❌ ERROR: Input cannot be Zero. Please try again.");
    continue;
  }
  break; 
}
//End Loop


// 2. CALCULATIONS 
// 2a. Addition (+)
let sum = numberA + numberB;
CalcResults.push(`+ Result: ${sum.toFixed(2)}`);

// 2b. Subtraction (-)
let difference = numberA - numberB;
CalcResults.push(`- Result: ${difference.toFixed(2)}`);

// 2c. Multiplication (*)
let product = numberA * numberB;
CalcResults.push(`* Result: ${product.toFixed(2)}`);

// 2d. Division (/)
let quotient = numberA / numberB;
CalcResults.push(`/ Result: ${quotient.toFixed(2)}`);

// 3. FINAL OUTPUT
console.log(" Results");

for (let result of CalcResults) {
  console.log(result);
}
