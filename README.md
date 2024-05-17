This is my first Git Repository.
<br>
Author - Shantanu Pandit
<br>
#Guessing the number game
import random
random_number=random.randint(1,100)
print("GUESSING THE NUMBER GAME ")
print("SHANTANU PANDIT THE OWNER ")
while True:
    number=int(input("ENTER THE NUMBER : "))
    if number==random_number:
        print("CONGRATULATIONS YOU GUESSING THE RIGHT NUMBER ")
        break
    elif number<random_number:
        print("Sorry Boss your number is too small , Try Bigger Number ")
    else:
        print("Sorry Boss your number is too Bigger , Try Smaller Number ")
        if random_number%2!=0:
            print("HINT-- Number is ODD")
        else:
            print("HINT -- Number is EVEN ")
print("GAME OVER THANK YOU ")
