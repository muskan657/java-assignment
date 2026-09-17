# Java Calculator

## 1. Project Overview

Java Calculator is a simple command-line calculator developed using Java. The project allows users to perform basic mathematical operations through a terminal or command prompt.

The calculator supports:

* Addition
* Subtraction
* Multiplication
* Division
* Modulus
* Division-by-zero error handling
* Menu-based user interaction

## 2. Technologies Used

* Java
* Java Scanner
* Java Switch Statement
* Command Line Interface

## 3. Requirements

Before running the project, make sure the following software is installed:

* Java Development Kit (JDK) 8 or later
* Command Prompt or Terminal
* Git (optional, only required if cloning the repository)

## 4. Check Java Installation

Open Command Prompt or Terminal and run:

```bash
java --version
```

Also check the Java compiler:

```bash
javac --version
```

If both commands display a Java version, the environment is ready.

## 5. Download the Project

Clone the GitHub repository using:

```bash
git clone https://github.com/muskan657/java-calculator.git
```

Replace `muskan657` with the GitHub username of the repository owner.

Then enter the project directory:

```bash
cd java-calculator
```

## 6. Compile the Project

Compile the Java source file using:

```bash
javac Calculator.java
```

If there are no compilation errors, the project has been compiled successfully.

## 7. Run the Project

Run the calculator using:

```bash
java Calculator
```

## 8. How to Use

After running the program, a menu will appear:

```text
=================================
        JAVA CALCULATOR
=================================
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Modulus
6. Exit
=================================
Enter your choice:
```

Enter the number corresponding to the desired operation.

For example:

```text
Enter your choice: 1
Enter first number: 25
Enter second number: 15
Result = 40.0
```

## 9. Operations

### Addition

Adds two numbers.

Example:

```text
25 + 15 = 40
```

### Subtraction

Subtracts the second number from the first number.

Example:

```text
25 - 15 = 10
```

### Multiplication

Multiplies two numbers.

Example:

```text
25 × 15 = 375
```

### Division

Divides the first number by the second number.

Example:

```text
25 / 5 = 5
```

The program prevents division by zero.

### Modulus

Returns the remainder after division.

Example:

```text
25 % 4 = 1
```

## 10. Error Handling

The program handles division by zero and modulus by zero.

Example:

```text
Enter your choice: 4
Enter first number: 20
Enter second number: 0
Error: Cannot divide by zero.
```

## 11. Project Structure

```text
java-calculator/
│
├── Calculator.java
├── README.md
└── .gitignore
```

## 12. Features

* Simple menu-driven interface
* Easy command-line execution
* Basic arithmetic operations
* Error handling
* Continuous operation until the user selects Exit
* No external libraries or dependencies required

## 13. Conclusion

The Java Calculator demonstrates fundamental Java programming concepts including variables, input/output, conditional statements, switch statements, loops, methods, and exception/error handling. The project is designed to be simple, portable, and executable directly from a command-line environment.
