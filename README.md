# Simple GUI Calculator using Tkinter

## Overview
This project is a basic calculator built using Python's `tkinter` module. It can perform simple arithmetic operations like addition, subtraction, multiplication, and division.  

## How It Works
- The calculator has buttons for numbers `0-9`, operators (`+`, `-`, `*`, `/`), a clear button (`C`), and an equals button (`=`).
- When you press the buttons, the input appears in a text box.  
- Clicking `=` evaluates the input, and the result is displayed.  

### Screenshot of the Calculator
Below is a screenshot of how the app looks when running:

![GUI Calculator](/src/img.jpg)

## Steps to Create the App
1. **Import Tkinter**  
   Use the `tkinter` module to create a graphical interface.  
2. **Create the Main Window**  
   Use `tk.Tk()` to set up the main application window.  
3. **Add an Entry Box**  
   Add an entry widget for the user to type and display the calculations.  
4. **Add Buttons**  
   Use `tk.Button()` to create buttons for numbers and operations.  
5. **Handle Click Events**  
   Write a function to handle button clicks and perform calculations.  
6. **Arrange Layout**  
   Use the `grid` method to arrange widgets in rows and columns.  

That's it! The app is simple and works as expected.  

## Running the App
To run this app, ensure you have Python installed. Save the code in a `.py` file and run it using:
```bash
Simple_GUI_Calculator.py
