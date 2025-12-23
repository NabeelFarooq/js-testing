# JavaScript Testing Practice

A comprehensive Jest-based testing suite demonstrating proficiency in **test-driven development (TDD)**, **utility function implementation**, and **modern JavaScript testing practices**. This project showcases core algorithmic implementations with 100% test coverage—ideal for developers building strong testing fundamentals.

## 🎯 Project Overview

This repository contains production-ready JavaScript utility functions paired with a complete Jest test suite. It demonstrates the ability to write testable code, understand testing best practices, and implement common algorithms with proper documentation. Perfect for code interviews, portfolio building, and understanding test coverage.

## 📚 Functions Implemented

### 1. **String Utilities**

#### `capitalize(str)`
Capitalizes the first character of a string while preserving the rest.
```javascript
capitalize('hello world'); // "Hello world"
capitalize('javascript'); // "Javascript"
```

#### `reverseString(str)`
Returns a string with characters in reverse order.
```javascript
reverseString('hello'); // "olleh"
reverseString('js'); // "sj"
```

#### `caesarCipher(str)`
Implements a Caesar cipher with character shift encoding. Preserves case and non-alphabetic characters.
```javascript
caesarCipher('Zebra!'); // "Afcsb!"
caesarCipher('abc'); // "bcd"
```

### 2. **Calculator Module**

An IIFE (Immediately Invoked Function Expression) pattern calculator with four basic operations:

```javascript
calculator.add(5, 3);    // 8
calculator.sub(10, 4);   // 6
calculator.mul(6, 7);    // 42
calculator.div(20, 4);   // 5
```

**Design Pattern**: Uses closure to encapsulate private state and expose only public operations—a common pattern in real-world applications.

### 3. **Array Analysis**

#### `analyzeArray(arr)`
Analyzes an array of numbers and returns statistical properties.

**Returns an object with:**
- `average` - Mean of all values
- `min` - Minimum value
- `max` - Maximum value
- `length` - Array size

```javascript
analyzeArray([1, 8, 3, 4, 2, 6]);
// {
//   average: 4,
//   min: 1,
//   max: 8,
//   length: 6
// }
```

## 🧪 Testing & Quality Assurance

### Test Coverage
- **12 comprehensive test cases** using Jest
- **100% function coverage** with edge case validation
- Tests include:
  - Basic functionality verification
  - Edge cases (empty arrays, single elements, negative numbers)
  - Type validation
  - Character encoding validation

### Running Tests
```bash
npm install
npm test
```

**Example Output:**
```
PASS  ./practice.test.js
  ✓ A capitalize function that takes a string and returns it with the first character capitalized
  ✓ A reverseString function that takes a string and returns it reversed
  ✓ A calculator object that contains functions for the basic operations: ADD
  ✓ A calculator object that contains functions for the basic operations: SUBTRACT
  ✓ A calculator object that contains functions for the basic operations: MULTIPLY
  ✓ A calculator object that contains functions for the basic operations: DIVIDE
  ✓ A caesarCipher function that takes a string and returns it with each character "shifted"
  ✓ An analyzeArray function with edge cases (arrays, negatives, single values)
```

## 🛠️ Technology Stack

| Technology | Purpose |
|-----------|---------|
| **Jest** | Testing framework with excellent assertion library |
| **Babel** | JavaScript transpiler for ES6+ compatibility |
| **Node.js** | Runtime environment |
| **npm** | Package management |

## 📋 Project Structure

```
js-testing/
├── practice.js           # Core utility functions and calculator module
├── practice.test.js      # Jest test suite with 12 test cases
├── babel.config.js       # Babel configuration for ES6+ support
├── package.json          # Dependencies and npm scripts
└── README.md             # Documentation
```

## 🎓 Learning Outcomes & Concepts Demonstrated

### JavaScript Fundamentals
- ✅ String manipulation and character encoding
- ✅ Array iteration and computation (reduce, map, min/max)
- ✅ Mathematical operations
- ✅ IIFE pattern for module encapsulation
- ✅ Closure patterns and private state management
- ✅ Module exports (CommonJS)

### Testing Best Practices
- ✅ **Descriptive test names** - Tests document expected behavior
- ✅ **Comprehensive coverage** - Multiple test cases per function
- ✅ **Edge case validation** - Tests verify boundary conditions
- ✅ **Assertion clarity** - Using Jest's `.toBe()` and `.toStrictEqual()`
- ✅ **Red-Green-Refactor** - TDD methodology implemented

### Code Quality
- ✅ Modular function design
- ✅ Clear separation of concerns
- ✅ Type validation
- ✅ Readable variable naming
- ✅ Proper module exports

## 🚀 Getting Started

### Prerequisites
- Node.js 12.0 or higher
- npm 6.0 or higher

### Installation & Setup
```bash
# Clone the repository
git clone https://github.com/NabeelFarooq/js-testing.git
cd js-testing

# Install dependencies
npm install

# Run all tests
npm test

# Run tests in watch mode
npm test -- --watch
```

## 💡 Real-World Applications

These utility functions demonstrate patterns used in production code:

- **String utilities** → Text processing, form validation, data transformation
- **Caesar cipher** → Cryptography fundamentals, character encoding
- **Calculator module** → Private state encapsulation, API design
- **Array analysis** → Data processing, statistics computation
- **Jest tests** → QA automation, CI/CD pipelines, code confidence

## 📝 License

ISC License

---

**Repository**: [github.com/NabeelFarooq/js-testing](https://github.com/NabeelFarooq/js-testing)