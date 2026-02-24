# Module_4_Exercises
Exercises# 1
"""
number = 3

while number <= 1000:
    if number % 3 == 0:
        print(number)
    number += 3
"""
Exercises# 2
import random
from mimetypes import guess_type

"""
Inch_to_CM = 2.54
while True:
    inches = float(input( "Enter inches (Negative to quit): "))
    if inches < 0:
        print(" Program Ended ")
        break
    centimeters = inches * Inch_to_CM
    print(f"{inches} inches = {centimeters:.2f} cm")
"""
Exercises# 3
Numbers = []
while True:
    s =input("Enter a number (Empty To Quit): ").strip()
    if s == "":
        break
    Numbers.append (float(s))
if len(Numbers) == 0:
    print("No Numbers were entered.")
else:
    print("Smallest.", min(Numbers))
    print(" Largest:", max(Numbers))
"""
Exercises# 4
import random
Hide = random.randint(1,10)
while True :
    guess = int(input("Guess a number (1-10): "))
    if guess > Hide:
        print("Too High")
    elif guess < Hide:
        print("Too Low")
    else :
        print("Correct")
        break
"""
Exercises# 5
Right_username = ("python")
Right_password = ("rules")
attempts = 0
while attempts < 5 :
    username = input("Enter username")
    password = input("Enter password")
    if username == Right_username and password == Right_password:
        print("Welcome")
        break
    else:
        attempts += 1
        print("Incorrect username or password.")
        print("Attempts left:", 5 - attempts)
    if attempts == 5:
        print("Access denied")
