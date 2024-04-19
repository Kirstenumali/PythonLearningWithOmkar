# 1. wap(write a program) ask the user take three number
# find the average implement using the function call

def calculate_average(num1, num2, num3):
    return (num1 + num2 + num3) / 3

def main():
    try:
        number1 = float(input("Enter the first number: "))
        number2 = float(input("Enter the second number: "))
        number3 = float(input("Enter the third number: "))
        average = calculate_average(number1, number2, number3)
        print(f"The average of the numbers is: {average:.2f}")
    except ValueError:
        print("Please enter valid numbers.")

if __name__ == "__main__":
    main()
