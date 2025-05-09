# overcomplicated-even-odd

The Overcomplicated Even Odd™ is a **Node.js** module that provides an absurdly overcomplicated solution to determine if a number is even or odd.

* Colorful console output
* Multi-algorithm analysis
* Extensive logging system
* Enterprise-grade error handling
* Promised-based API

**Installation**
**Node.js 14 or newer is required.**

```
npm install overcomplicated-even-odd
yarn add overcomplicated-even-odd
pnpm add overcomplicated-even-odd
```

**Features**

* **Multiple redundant algorithms** - Uses modulo, binary AND, string analysis, and recursive division to verify parity
* **Dramatic console output** - Colorful logs with emojis and progress bars for maximum entertainment
* **Artificial delays** - Takes approximately 5 seconds to determine if a number is even or odd
* **Enterprise-grade validation** - Handles edge cases you never knew existed
* **Strategy pattern implementation** - Because design patterns make everything better

**Example usage**

Basic usage:

```javascript
const { isEvenOrOdd } = require('overcomplicated-even-odd');

// Watch your console explode with information
isEvenOrOdd(42).then(result => {
  console.log(`The final result is: ${result}`); // "even"
});
```

With custom error handling:

```javascript
const { isEvenOrOdd } = require('overcomplicated-even-odd');

async function checkNumber(input) {
  try {
    const result = await isEvenOrOdd(input);
    console.log(`${input} is ${result}`);
  } catch (error) {
    console.error('Parity analysis failed:', error.message);
    // Handle non-numeric inputs or other validation errors
  }
}

checkNumber(42);    // Works fine
checkNumber("42");  // Throws error - strings not allowed
```

**The Simple Alternative**

For those who prefer simplicity over entertainment:

```javascript
const isEvenOrOddSimple = (num) => num % 2 === 0 ? "even" : "odd";
```

**Why This Package Exists**

This package demonstrates what happens when developers apply enterprise-level architecture to trivial problems. Use it for:

* Education on over-engineering
* Entertaining your colleagues
* Making simple tasks unnecessarily complex

**License**

MIT
