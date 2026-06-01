# calculator
source code for calculator 


print("=" * 40)
print("         SIMPLE CALCULATOR")
print("=" * 40)

# Taking user input
num1 = float(input("Enter First Number  : "))
num2 = float(input("Enter Second Number : "))

# Menu
print("\nSelect Operation")
print("1. Addition (+)")
print("2. Subtraction (-)")
print("3. Multiplication (*)")
print("4. Division (/)")

choice = input("\nEnter choice (1/2/3/4): ")

print("\n" + "=" * 40)

# Operations
if choice == '1':
    result = num1 + num2
    print(f"Result: {num1} + {num2} = {result}")

elif choice == '2':
    result = num1 - num2
    print(f"Result: {num1} - {num2} = {result}")

elif choice == '3':
    result = num1 * num2
    print(f"Result: {num1} × {num2} = {result}")

elif choice == '4':
    if num2 != 0:
        result = num1 / num2
        print(f"Result: {num1} ÷ {num2} = {result}")
    else:
        print("Error: Division by zero is not allowed!")

else:
    print("Invalid Choice! Please select 1, 2, 3 or 4.")

print("=" * 40)
print("     THANK YOU FOR USING")
print("=" * 40)
