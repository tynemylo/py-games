# py-games
import random 
secret_number = random.randint(1, 100)
guess = None

while guess != secret_number:
    guess = int(input("Guess a number between 1 and 100: "))
    if guess < secret_number:
        print("Too low! Try again. ")
    elif guess > secret_number:
        print("Too high! Try again. ")
    else:
        print('You win!')