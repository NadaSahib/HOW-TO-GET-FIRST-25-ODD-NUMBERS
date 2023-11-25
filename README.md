# HOW-TO-GET-FIRST-25-ODD-NUMBERS
count = 0
number = 1

print("The first 25 odd numbers are:")
while count < 25:
    if number % 2 != 0:
        print(number)
        count += 1
    number += 1
