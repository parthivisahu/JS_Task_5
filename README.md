# JS_Task_5
# JavaScript Function to Reverse a Number

This JavaScript function allows you to reverse a given number. It takes a numeric input and returns the reversed number as output.

## Usage

1. Include the JavaScript function in your code or script file:

   ```javascript
   function reverseNumber(number) {
     const reversedString = String(number).split('').reverse().join('');
     return parseInt(reversedString) * Math.sign(number);
   }
   ```

2. Call the `reverseNumber` function with a number as an argument:

   ```javascript
   const number = 12345;
   const reversedNumber = reverseNumber(number);
   console.log(reversedNumber);
   ```

   The `reverseNumber` function will reverse the given number and assign the reversed number to the `reversedNumber` variable. It will then log the reversed number to the console.

## Example

```javascript
function reverseNumber(number) {
  const reversedString = String(number).split('').reverse().join('');
  return parseInt(reversedString) * Math.sign(number);
}

const number = 12345;
const reversedNumber = reverseNumber(number);
console.log(reversedNumber);
```

The output of the above example will be:

```
54321
```

The `reverseNumber` function reverses the digits of the input number. In the example, the number 12345 is reversed to 54321 and logged to the console.

Feel free to use this function in your JavaScript code to reverse numbers as needed.
