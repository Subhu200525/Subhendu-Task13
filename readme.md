# Even and Odd Number Checker

## 📌 Description

This is a simple JavaScript program that checks whether two given numbers are **even or odd** using the modulus (`%`) operator and an `if-else` condition.

## 🛠️ Technologies Used

* JavaScript

## 📂 Program

The program uses two variables:

```javascript
let a = 5;
let b = 10;

if (a % 2 === 0) {
    console.log(a + " is even");
} else {
    console.log(a + " is Odd");
}

if (b % 2 === 0) {
    console.log(b + " is even");
} else {
    console.log(b + " is odd");
}
```

## ⚙️ How It Works

The program uses the modulus operator `%` to find the remainder after dividing a number by `2`.

* If `number % 2 === 0`, the number is **Even**.
* Otherwise, the number is **Odd**.

### Example

For `a = 5`:

```text
5 % 2 = 1
```

Therefore, `5` is odd.

For `b = 10`:

```text
10 % 2 = 0
```

Therefore, `10` is even.

## ▶️ Output

```text
5 is Odd
10 is even
```

## 🚀 How to Run

1. Create a JavaScript file, for example `evenOdd.js`.
2. Add the JavaScript code to the file.
3. Open a terminal in the project folder.
4. Run the program using:

```bash
node evenOdd.js
```

## 📚 Concepts Used

* JavaScript Variables
* `if-else` Condition
* Modulus `%` Operator
* `console.log()`
