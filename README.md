# game1
Lets make a small prediction toss coin here i am going to make a toss prediction collection through coding
Here i am going to take a fair coin 10 times it gives us as a result of how much time ot got head or tail.


              this is  the code
import random
def tossingGame():
    mySample =['T','H']
    count_heads = 0
    userinput = int(input("please enter the coin of tossing:"))
    for item in range(userinput):
        myoptions = random.choice(mySample)
        if myoptions==mySample[0]:
            count_heads +=1
    print(f"Head Count{count_heads}")
    print(f"Tails Count{userinput - count_heads}")
    
    
    
tossingGame()
