import random
menuscreen = 0
newuser = True
name = None
adventure = None
combatstyle = None
haircolor = None
gender = None
race = None
yourlevel = 1# initiallizing your level to 1 when game starts
character = []
def cls(): 
    print ("\n" * 100)

def createuser():# user creation screen
    global newuser
    global name
    global adventure
    global combatstyle
    global haircolor
    global gender
    global race
    questions = ['name', 'quest', 'combat style','hair color','gender','race']
    length = len(questions)
    #answers = []
    for q in range(0,length):
        print("What is your "+questions[q]+"?")
        answer = input()
        character.append(answer)
    print(character)
    
def adventure():#chooses the adventure setup to set out on
    global travel
    if travel == 1:#first adventure to get a treasure
        print("stuff")

def menu():# menu function
    start = False #bool to start game
    global menuscreen #State of menu screen
    screenstate = 0 #
    val = 0
    correctvalue  = False

    menuoptions = ["Welcome to the game","Enter in an option as seen below","1) Play Game","2) Saved Games","3) Settings","4) Credits"]
    lmenuoptions = len(menuoptions)#gets lenght of menuoptions
    while correctvalue == False:
        if start == False and menuscreen ==0:#if start is false go to menu
        ##    print("Welcome to the game")
        ##    print("Enter in an option as seen below")
        ##    print("1) Play Game")
        ##    print("2) Saved Games")
        ##    print("3) Settings")
        ##    print("4) Credits")
            for x in range(0,lmenuoptions):#dynamic clean menu
                print(menuoptions[x])
            while menuscreen == 0:
                menuscreen = input("Enter your choice :  ")
                #print(menuscreen)
                val = int(menuscreen)
                #print(val)
                #except ValueError:
                 #   print("That's not an int!")
                if val <= 4  and val >= 1: # makes sure input is correct
                    menuscreen = val
                    correctvalue = True
                 #   print("In assigning statement")
                else: #prompt for loop
                    menuscreen = 0
                    print("Please enter a correct value")
    return menuscreen
#player class
class playerrace:

    def __init__(self, name, attack, health, level, critical, tricks):
        self.name = name
        self.attack = attack
        self. health = health
        self.level = level
        self.critical = critcal
        self.tricks = []
        attack = (1+level)#base attack

    def add_tricks.append(self, tricks):
        self.tricks.    


#end player class

#creating monster classes start skeleton class
class monster:

    def __init__(self, name, attack, health,  monsterlevel, critical, tricks):
        self.name = name
        self.attack = attack
        self. health = health
        self.monsterlevel = monsterlevel
        self.critical = critcal
        self.tricks = []
        multiplier = 0.000456
        
        attack = (1+level)*(level*multiplier)

    def add_trick.append(self, trick):
        self.tricks.append(trick)

#end skeleton class

def battle(yourlevel):
    #generate monster
    global yourlevel
    monstername = ["Skeleton","Goblin","Blood Elf"]
    namechoice = monster[random.randint(0,len(monster)]
    attack = random.randint(1,5)
    health = random.randint(10,25) 
    monsterlevel = random.randint(-5,5)
    monstername[namechoice] = monster(monstername[namechoice],            
    monsterdmg = skeleton.attack()

    print("stuff")

def traveling():#probably need to make a battle function
    count = 0
    encounter = False
    flag = False
    num = 0
    choice = 0;
    encounteroptions = []
    while count <= 250:
        count += 1
    num = random.randomint(1,100)
    if num >= 50:
        encounter = True
        cls()
        while encounter == True:
            encounteroptions=["You have encounter a (monster name from list)",
                              "Please select an option","1) Battle","2)Equipement",
                              "3) Run"]
            lengthe = len(encounteroptions)
            for x in range(0,lengthe):
                print(encounteroptions[x])
                while flag == False:
                    choice = int(input("Please enter your choice : "))
                    if choice >= 1 and choice <=3:
                        flag = True
                    else:
                        print("Error input out of bounds please try again")
        if choice == 1:# battle
            print("Battle")
            

        elif choice == 2:
            print("")
        elif choice == 3:
            print("")
        else:
            print("error")
            
    
travel = None
menu()
#print(menuscreen)
while menuscreen == 1:
    if newuser == True:
        createuser()
        newuser = False
    print(character[0],", you are currently in town")
    travel = input("Would you like to travel to the next town : (y/n)")
    if travel == y:
        print("")
