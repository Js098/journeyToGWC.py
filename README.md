# journeyToGWC.py
start = '''
Good Morning. It's your first day going to Girls Who Code Summer Immersion Program.
 Your're super excited but also nervous. Little did you know the dangers that you would
 encounter on your way to the program.
'''

Missedbus = "You missed the bus and you realize that you're going to be very late."

Wrongbus = "You get on the late bus and your driver is suspiciously nervous."

Busride = "The bus ride is pleasant as it isn't crowded and there's no traffic"


def ontimebus():
    print (Busride)
    bus = True
    while bus:

        user_input = raw_input("What stop do you want to get off at? Type '3' to get off at stop 3 or '4' to get off at stop 4.")
        if user_input == "3":
            print("Yay! You got off at the right stop.") # finished the story by writing what happens
            bus = False

        elif user_input == "4":
            print("You got off at the wrong stop.")
            bus = False

        else:
            print("Please type 3 or 4")

def wrongtimebus():
    print (Wrongbus)
    bus = True
    while bus:

        user__input = raw_input("Do you sit in the front seats or the back seats? Type front for front seats and back for back seats.")
        if user_input == "Front":
            print("The bus driver kidnaps you and you die.")
            exit()

        elif user_input == "back":
            print("The bus driver accidentally drives off a cliff and you die.")
            exit()

        else:
            print("Please type front or back.")

def stuckintraffic
    bus = True
    while bus:

        user_input = raw_input("Do you want to go on lane 1 or lane 2? Type 1 for lane 1 and 2 for lane 2.)
        if user_input == "1":
            print("You arrive late and get kicked out of the program")
            exit()

        elif user_input == ""





def missedbus():
    print(Missedbus)
    bus = True
    while bus:

        user_input = raw_input("Do you ask your parents to take you there or do you take the late bus? Type ask for asking parents or wait to take the late bus.")
        if user_input == "ask":
            print("You ask your parents to take you and they agree but on the way there you get stuck in traffic.")
            bus = False
            print stuckintraffic

        elif user_input == "Wait":
            print ("You wait for the late bus.")
            bus = False
            print wrongtimebus()

        else:
            print("Please type ask or wait.")




#display the text in the start variable to the player
print(start)
Wakeup = True
while Wakeup:


    user_input = raw_input("First things first. Who should I feed? My turle or chicken? Type chicken to feed your chicken or turtle to feed your turtle.")
    if user_input == "turtle":
        print("Okay turtle it is then. Should I feed it vegetables or insects?") # finished the story by writing what happens
        user_input = raw_input("Type vegetables or insects.")
        if user_input == "vegetables":
            print("Your turtle is fed and you leave your house and get on your bus.")
            Wakeup = False
            print ontimebus()

        elif user_input == "insects":
            print("Youe turtle died and therefore you died.")
            Wakeup = False
            exit()

    elif user_input == "chicken": #elif = else + if
        print("Okay chicken it is then. Should I feed it chicken or eggs?")
        user_input = raw_input("Type chicken or eggs")
        if user_input == "chicken":
            print("The chickens pecked you to death.")
            Wakeup = False
            exit()

        elif user_input == "eggs":
            print("The chickens are fed but when you leave the house you realize you missed your bus.")
            Wakeup = False
            print missedbus()


    # finished the story writing what happens
#what happens if I don't type "left" or "right" and where should put the code
    else:
        print("Please type 'chicken' or 'turtle' ")
