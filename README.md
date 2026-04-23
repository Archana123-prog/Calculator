# 🧮 Simple Calculator Web App

A modern and minimal **calculator web application** built using **HTML, CSS, and JavaScript**.
It supports basic arithmetic operations with a clean UI and smooth user interaction.

## 🚀 Features

* ➕ Addition
* ➖ Subtraction
* ✖️ Multiplication
* ➗ Division (with zero handling)
* 📊 Modulus (%)
* 🧹 Clear display (`C`)
* ⌫ Delete last digit (`del`)
* 🔢 Decimal support
* 🎨 Responsive and modern UI

## 🛠️ Tech Stack

* **HTML5** – Structure
* **CSS3** – Styling & Layout (Grid + Dark Theme)
* **JavaScript (Vanilla)** – Logic & Functionality

## 📂 Project Structure

```
calculator/
│── index.html     # Main structure
│── style.css      # Styling
│── script.js      # Logic
│── README.md      # Documentation
```

## ⚙️ How It Works

### 1. Input Handling

* Numbers are stored in:

  * `firstValue`
  * `secondValue`
* Operator is stored separately.

### 2. Operation Flow

1. User enters first number
2. Selects operator
3. Enters second number
4. Presses `=` to calculate

### 3. Calculation Logic

JavaScript uses a `switch` statement:

```js
switch (operator) {
  case "+": result = a + b; break;
  case "-": result = a - b; break;
  case "*": result = a * b; break;
  case "/": result = b !== 0 ? a / b : "Error"; break;
  case "%": result = a % b; break;
}
```

## 🧠 Key Functions

| Function             | Description             |
| -------------------- | ----------------------- |
| `appendNumber(num)`  | Adds numbers to display |
| `appendOperator(op)` | Stores operator         |
| `calculate()`        | Performs calculation    |
| `clearDisplay()`     | Resets everything       |
| `deleteLast()`       | Removes last input      |

## 🎨 UI Highlights

* Dark theme design 🌙
* Grid-based button layout
* Hover effects for better UX
* Highlighted operator & equals button

## 🖥️ How to Run

1. Download or clone the repository
2. Open `index.html` in your browser

## 🔮 Future Improvements

* ⌨️ Keyboard input support
* 📱 Mobile optimization
* 🧮 Scientific calculator features
* 📜 Calculation history

## 📸 Preview
<img width="1897" height="920" alt="Screenshot 2026-04-24 000101" src="https://github.com/user-attachments/assets/44ae62e1-50fb-4684-9ddf-211954a4eabb" />
<img width="1895" height="907" alt="Screenshot 2026-04-24 000251" src="https://github.com/user-attachments/assets/5a1137fc-24b9-482c-b911-f300218215ce" />

## 🙌 Author

**Archana Kumari**

