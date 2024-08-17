# Calculator-in-C-Program
- Name: Ankit Rai
- Department: BCA
- Sem: 2nd
- Roll no: 30001223060
- Registration no.: 233001010534

## Simple Calculator Program
### Description
This is a simple calculator program written in C. It performs basic arithmetic operations such as addition, subtraction, multiplication, and division based on user input.

### How to Use
Compile the Program: Use a C compiler to compile the program. For example, using gcc:
gcc -o calculator calculator.c

### Run the Program: Execute the compiled program:
./calculator

### Input Instructions:
- The program will prompt you to enter an operator (+, -, *, /).
- Then, you will be asked to enter two operands (numbers).
### Output:
- The program will display the result of the operation.
- If you attempt to divide by zero, the program will display an error message.
### Example
Enter an operator (+, -, *, /): +
Enter two operands: 5 3
5.00 + 3.00 = 8.00

### Error Handling
- The program checks for division by zero and displays an appropriate error message.
- If an invalid operator is entered, the program will display an error message.
### Code Explanation
- The program starts by declaring variables to store the operator and the two operands.
- It prompts the user to enter an operator and two operands.
- Using a switch statement, the program performs the corresponding arithmetic operation based on the operator entered.
- The result is then printed to the console.
- If the user attempts to divide by zero or enters an invalid operator, the program handles these cases and displays error messages.
### Requirements
A C compiler (e.g., gcc).
