# flying-circus-game
#beginner code for random number game

import random
random_number = random.randint(0,10)
tries = 0
tries_remaining = 10
print(random_number)

while tries < 10:
    guess = input("guess 1 to 9.")
    tries += 1
    tries_remaining -= 1

try:
    guess_num = int(guess)
    except:
        print("whole number doof")
    break

    if not guess_num > 0 or not guess_num < 10: 
        print("can you count?")   
    break

    else guess_num == random_number:
        print("Bingo, got it!")
        print("you used {} tries.".format(tries))
    user_input = input(")
	
    if user_input == "!":
        print("type ! to exit cowboy")   
    break


    else guess_num < random_number:
        if tries_remaining > 0:
        print("too low, go higher!  {} tries left.".format(int(tries_remaining)))
        continue
    else:
      print("waaaa waah! {}".format(random_number))
      print("2 oz sparrows don't carry coconuts, try again")


    else guess_num > random_number:
        if tries_remaining > 0:
        print("noooo! go lower! {} tries remaining.".format(int(tries_remaining)))
        continue
    else:
        print("BZZZZT! you lose, the number was {}".format(random_number))
        print("nothing but a mere flesh wound, try again")


user_input = input(")
        if user_input == "!":
            print("type ! to run away if you feel repressed")   
    break
	  
	  
	  
	  
	  
