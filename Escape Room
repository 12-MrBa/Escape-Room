import time

def play_again():
    play = input("Do you want to play again? Y or N")

    if play.upper() == "Y":
        main_room()
    elif play.upper() == "N":
        print("\nThanks for playing come again soon!")
    else:
        print("It's not that hard, just type 'Y' or 'N'")
        print("Capital letters don't even matter!")
        play_again()

def game_over():
    print("Unfortunately, you died and coudn't escape the escape rooms without dying")
    print("\n\n\nYou just got coconut malled")
    print("Send this to all your friends to totally coconut mall them")
    play_again()

def win():
    print("\nCongratulations! You have completed and successfully escaped the escape room alive")
    print("You also have a cool trophy!")
    print("Now I can rickroll you! \n Scroll down through the rickroll to play again or to stop!")
    print("•"*200)
    print("We're no strangers to love\nYou know the rules and so do I\nA full commitment's what I'm thinking of\nYou wouldn't get this from any other guy\nI just wanna tell you how I'm feeling\nGotta make you understand")
    print("Never gonna give you up\nNever gonna let you down\nNever gonna run around and desert you\nNever gonna make you cry\nNever gonna say goodbye\nNever gonna tell a lie and hurt you\nWe've known each other for so long")
    print("Your heart's been aching but you're too shy to say it\nInside we both know what's been going on\nWe know the game and we're gonna play it\nAnd if you ask me how I'm feeling\nDon't tell me you're too blind to see")
    print("Never gonna give you up\nNever gonna let you down\nNever gonna run around and desert you\nNever gonna make you cry\nNever gonna say goodbye\nNever gonna tell a lie and hurt you\nNever gonna give you up")
    print("Never gonna let you down\nNever gonna run around and desert you\nNever gonna make you cry\nNever gonna say goodbye\nNever gonna tell a lie and hurt you\nNever gonna give, never gonna give\n(Give you up)")
    print("We've known each other for so long\nYour heart's been aching but you're too shy to say it\nInside we both know what's been going on\nWe know the game and we're gonna play it\nI just wanna tell you how I'm feeling")
    print("Gotta make you understand\nNever gonna give you up\nNever gonna let you down\nNever gonna run around and desert you\nNever gonna make you cry\nNever gonna say goodbye\nNever gonna tell a lie and hurt you")
    print("Never gonna give you up\nNever gonna let you down\nNever gonna run around and desert you\nNever gonna make you cry\nNever gonna tell a lie and hurt you\nNever gonna give you up\nNever gonna let you down")
    print("Never gonna run around and desert you\nNever gonna make you cry\nNever gonna say goodbye")
    play_again()


def main_room():
    print("\nWelcome to the first room")
    time.sleep(1.2)
    print("•"*200)
    time.sleep(0.5)
    print("This is a land of monsters and saints. You must make your moves cautiously to survive!")
    time.sleep(1.5)
    print("You see two doors in the distance. \n 1. The Bear Room \n 2. The Monster Room")
    time.sleep(2)
    input_check(bear_room, monster_room)

def bear_room():
    print("\nYou've just been eaten by a bear! \n What did you think would happen?")
    print("•" * 200)
    game_over()

def input_check(room1, room2):
    while True:
        choice_one = input("Where do you want to go? Type 1 or 2")
        if choice_one=="1":
            room1()
            break
        elif choice_one=="2":
            room2()
            break
        else:
            print("Invalid input! Try again.")

def silver_room():
    print("\n There was a knife made of pure silver and it just stabbed you!")
    print("Then you died...")
    print("•" *200)
    game_over()

def monster_room():
    print("\n\nTurns out that the monster is harmless. It is indeed friendlier than you might have thought")
    time.sleep(0.5)
    print("The monster wants to direct you to a room where you might get some reward!\n")
    time.sleep(0.5)
    print("The monster leads you to two doors leading to different rooms \n 1. Leads to the Gold Room \n 2. Leads to the Silver Room")
    time.sleep(0.5)

    input_check(gold_room, silver_room)

def gold_room():
    print("\n\nNice! You've discovered a room full of raw gold")
    time.sleep(0.5)
    print("Be sure to take some with you. It may become useful later\n")
    time.sleep(0.5)
    print("After picking up some gold you uncover two new rooms \n 1. The Mahogany Room \n 2. The Oak Room")
    time.sleep(0.5)

    input_check(mahogany_room, oak_room)

def mahogany_room():
    print("\nThe tree just fell on you and you died!")
    print("Someone must have made traps!")
    print("•" * 200)
    game_over()

def oak_room():
    print("\n\nWow you found the oak room which is full of luxurious wood")
    time.sleep(0.5)
    print("Take some with you! It might be helpful later")
    time.sleep(0.5)
    print("Now there are only a few more rooms to go!\n")
    time.sleep(0.5)
    print("Which of the two new rooms do you want to go to now?\n 1. The Diamond room \n 2. The Crystal room")
    time.sleep(0.5)

    input_check(diamond_room, crystal_room)

def crystal_room():
    print("\nTurns out that the 'Crystal' in the Crystal room was actually a saint named Crystal who just shot you!")
    print("The shot had enough to kill you")
    print("•" * 200)
    game_over()

def diamond_room():
    print("\n\nThis room is full of the biggest, clearest and shiniest diamonds you've ever seen!")
    time.sleep(0.5)
    print("Bring some of it along with yo, it may be helpful!")
    time.sleep(0.5)
    print("Now you only have 1 more room to go!")
    time.sleep(0.5)
    print("\n Choose carefully, where do you want to go? \n 1. The Magician's Room \n 2. The Wizard's Room")
    time.sleep(0.5)

    input_check(magician_room, wizard_room)

def wizard_room():
    print("\n You accidentally startled the wizard by opening the door")
    print("This scared him so much that he used a spell to freeze you to death")
    print("•" * 200)
    game_over()

def magician_room():
    print("\n\nThe magician is outstanded by all the amazing items you've collected!")
    time.sleep(2)
    print("He offers to turn all of your items to make a beautiful trophy")
    time.sleep(2)
    print("You need to type the magic word 'GOOMY' in order to claim your trophy")
    time.sleep(1.5)
    choice = input("Type the magic word here: ")
    time.sleep(2)
    if choice.upper()=="GOOMY":
        win()
    else:
        print("The magician got offended by the fact that you couldn't use the magic word correctly!")
        game_over()

main_room()
