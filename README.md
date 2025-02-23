operator = input("Enter an o[perator(+ - * /):" )
num1 = float(input("enter the 1st number:"))
num2 = float(input("enter the 2nd number:"))

if operator =="+":
    result = num1 + num2
    print(round(result, 1))
elif operator =="-":
    result = num1 - num2
    print(round(result, 1))
elif operator == "*":
    result = num1 * num2
    print(round(result, 1))
elif operator == "/":
    result = num-1 / num2
    print(round(result , 1))
else:
    pirnt (f"{operator}is not valid operator")
