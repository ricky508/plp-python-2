# plp-python-2
Here is a simple Python program that performs the operation based on user input:

```python
# Get user input for two numbers and the operation
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
operation = input("Enter the operation (+, -, *, /): ")

# Perform the operation based on the user's choice
if operation == '+':
    result = num1 + num2
elif operation == '-':
    result = num1 - num2
elif operation == '*':
    result = num1 * num2
elif operation == '/':
    if num2 != 0:
        result = num1 / num2
    else:
        result = "Error! Division by zero."
else:
    result = "Invalid operation."

# Display the result
print(f"{num1} {operation} {num2} = {result}")
```

### Explanation:
1. The program first asks the user to input two numbers (`num1` and `num2`).
2. Then it asks for the operation (either `+`, `-`, `*`, or `/`).
3. Based on the operation input, it performs the calculation and displays the result.
4. If the operation is invalid or if there is a division by zero, the program will handle these cases accordingly.

### Example Output:
```
Enter the first number: 10
Enter the second number: 5
Enter the operation (+, -, *, /): +
10.0 + 5.0 = 15.0
```
