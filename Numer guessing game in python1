import random 

def guess_number():
    random_number = random.randint(1,20)
    player_name = input("Enter Your name")
    confirm_play = input("Would you like to start the game?(Enter yes/no):")
    attempts = 0 
    
    while confirm_play.lower() == "yes":
         guess = int(input("Guess any number between 1 amd 20"))
         
         if guess < 1 or guess > 20:
            print("Please guess any number in the Range")
            
         elif  guess == random_number:
             print("Congratulations",player_name,'You Won!')
             attempts +=1 
             print("it took you", attempts,"attempts to win this game")
             break 
         
         elif guess > random_number:
             print("Hint try smaller number")
             attempts -=1
             
         elif guess < random_number:
             print ("Hint try larger number")
             attempts +=1 
             
    else:
        print("Thanks", player_name,"for your time")
            
guess_number()
             
