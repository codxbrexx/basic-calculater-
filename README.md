# basic-calculater-
#progammer = Md mozammil ali
#date = 2024-04-14

print("-------- mini calculater ---------")

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

print(
    "press 1 for addition \npress 2 for subtraction \npress 3 for multiplication \npress 4 for division"
)

choice = int(input("Enter your choice from 1-4:"))

if choice == 1:
  print("The addition of given two numbers is", num1 + num2)

elif choice == 2:
  print("The subtraction of given two numbers is", num1 - num2)

elif choice == 3:
  print("The multiplication of given two numbers is", num1 * num2)
elif choice == 4:
  print("The division of given two numbers is", num1 / num2)
else:
  print("invalid inpur")


