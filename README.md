# 🐞 prank-bugger – Fake Bugs to Confuse Your Teammates

**prank-bugger** randomly throws **fake, funny, and harmless errors** 5% of the time to mess with your teammates (or yourself). 😈

## 🚀 Installation

```sh
npm install prank-bugger
```

## 🔧 Usage

```js
const prankBugger = require("prank-bugger");

// Run once to see if a bug appears
prankBugger.run();

console.log("No bugs this time... or maybe next time?");
```

### Example Output:

- "SyntaxError: Unexpected token 'fun'. Fun is not allowed in production."
- "Critical failure: Your code is too good. Downgrading to PHP."
- "404: Developer motivation not found."

## 🎛️ Customization

### **Set the Bug Probability**

By default, errors appear **5%** of the time. You can change this:

```js
prankBugger.setBugRate(0.1); // 10% chance of throwing a bug
```

### **Add Custom Fake Errors**

Want to add your own? No problem!

```js
prankBugger.addError("Memory Leak: Your coffee cup is empty.");
```

## 🎯 Why Use This?

✅ Funny way to throw fake bugs for testing
✅ Harmless fun for your team
✅ Perfect for April Fool’s Day
✅ Keeps your teammates paranoid

---

### **⚠️ Disclaimer**

This package is meant for **fun and harmless pranks**. Don’t use it in production (unless you want to get fired).
