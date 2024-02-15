smth smth

in this code:
'''py
import random

repeat = True

while repeat:
    number = random.randint(1, 100)
    guess = 0
    tries = 0

    while guess != number:
        if guess < number:
            print("lower. ")
        else:
            print("higher. ")
        
        guess = int(input("guess the number: "))
        tries += 1
    else:
        if tries < 4:
            print(f"wow it only took you {tries} treis")
        elif tries < 7:
            print(f"not bad but it took you a whole {tries} tries")
        else:
            print(f"damn it took you {tries} tries to guess you shit at this")

    response = input("do you wish to continue? y/n: ")
    if response == "y":
        repeat = True
    elif response == "n":
        repeat = False
        print("thank you for playing bye bye")
    else:
        repeat = False
        print("thank you for playing bye bye")
'''
