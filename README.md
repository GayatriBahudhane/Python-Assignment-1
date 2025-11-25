# ------------------------------
# Greeting Program
# ------------------------------

First_name = input("Enter your first name: ")
Last_name = input("Enter your last name: ")

print("\nHello, " + First_name + " " + Last_name + " !" + " Welcome to the Python program.\n")

# ------------------------------
# Mathematical Operations Program
# ------------------------------

num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))

print("\n--- Results ---")
print("Addition: ", num1 + num2)
print("Subtraction: ", num1 - num2)
print("Multiplication: ", num1 * num2)

# Handling division by zero
if num2 != 0:
    print("Division: ", num1 / num2)
else:
    print("Division: Undefined (cannot divide by zero)")
