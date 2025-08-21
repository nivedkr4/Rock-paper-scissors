# Rock-paper-scissors
import random  
print("===================")
print("Rock Paper Scissors")
print("===================")
print("1) ✊")
print("2) ✋")
print("3) ✌️")
player=int(input("Pick a number"))
computer=random.randint(1,3)
if player==1:
  print("you chose:✊")
elif player==2:
  print("you chose:✋")
elif player==3:
  print("you chose:✌️")
else:
  print("Go Back!")
if computer==1:
  print("you chose:✊")
elif computer==2:
  print("you chose:✋")
elif computer==3:
   print("you chose:✌️")
else:
  print("Go Back")

if computer==player:
  print("tie")
elif (player == 1 and computer == 3) or \
     (player == 2 and computer == 1) or \
     (player == 3 and computer == 2):
    print("The player won!")
else:
    print("CPU won!")

