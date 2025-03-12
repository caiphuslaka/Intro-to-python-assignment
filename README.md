# Intro-to-python-assignment
# ADD
# MULTIPLYING
# SUBTRACTION
# DIVISION

def calculate(num1, num2, operation):
    if operation == 'addition':
        return num1 + num2
    elif operation == 'subtraction':
        return num1 - num2
    elif operation == 'multiplication':
        return num1 * num2
    elif operation == 'division':
        if num2 != 0:
            return num1 / num2
        else:
            return "Error: Division by zero is not allowed."
    else:
        return "Error: Invalid operation."

# Input from the user
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
operation = input("Enter the operation (addition, subtraction, multiplication, division): ").lower()

# Perform calculation and display the result
result = calculate(num1, num2, operation)
print("Result:", result)
