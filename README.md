# Multi-op Calculator Program

## 📌 Project Overview
A simple calculator program that performs multiple operations: Addition, Subtraction, Multiplication, and Division.

## 🛠️ Features
- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)
- Error handling for invalid inputs
- Division by zero protection

## 🧠 Logic Breakdown

### 1. **Program Structure**
Multi-op Calculator Program
├── Main function: calculator()
├── Helper functions: add(), subtract(), multiply(), divide()
└── Error handling for invalid inputs

### 2. **How It Works**
1. **User Input Phase:**
   - Program prompts for two numbers
   - User selects an operation (+, -, *, /)

2. **Processing Phase:**
   - Input validation checks
   - Appropriate function is called based on operation
   - Calculations are performed

3. **Output Phase:**
   - Result is displayed in clear format
   - Error messages shown for invalid operations

### 3. **Key Functions**
- `add(a, b)`: Returns sum of a and b
- `subtract(a, b)`: Returns a minus b
- `multiply(a, b)`: Returns product of a and b
- `divide(a, b)`: Returns a divided by b (with zero-check)

### 4. **Error Handling**
- Prevents division by zero
- Catches non-numeric inputs
- Validates operation symbols

### Run the calculator:

python calculator.py

