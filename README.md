# 🧮 Simple Python Calculator

A basic Python-based calculator that performs arithmetic operations (+, -, *, /, ^, %) with error handling and control operations. The program continuously runs until the user resets or terminates it.

## 🚀 Features
- ✅ Supports **Addition (+), Subtraction (-), Multiplication (*), Division (/), Power (^), and Remainder (%)**
- ✅ Handles **invalid inputs and division by zero**
- ✅ Provides **Reset ($) and Terminate (#) control operations**
- ✅ Runs continuously until the user chooses to exit

## 🔧 Installation & Usage

1. **Clone the Repository**  
   ```sh
   git clone https://github.com/your-username/simple-python-calculator.git
   cd simple-python-calculator
   ```

2. **Run the Program**  
   ```sh
   python calculator.py
   ```

## 📜 How It Works

1. The program prompts the user to select an operation.  
2. The user enters two numbers as operands.  
3. The result is displayed, and the program loops back to the main menu.  
4. Enter `$` to reset or `#` to terminate the program.  

## 📝 Example Usage

```
Select operation.
1.Add      : + 
2.Subtract : - 
3.Multiply : * 
4.Divide   : / 
5.Power    : ^ 
6.Remainder: % 
7.Terminate: # 
8.Reset    : $ 
Enter choice(+,-,*,/,^,%,#,$): +
Enter first number: 5
Enter second number: 3
5.0 + 3.0 = 8.0
```

## ⚠️ Error Handling
- **Invalid Input** → `"Not a valid number, please enter again"`
- **Invalid Operation** → `"Unrecognized operation"`
- **Division by Zero** → `"Something went wrong"`

## 🤝 Contributing
Feel free to fork this project and submit pull requests. Any improvements are welcome! 😊

## 📜 License
This project is licensed under the MIT License.
