import random
print("1 : stone \n2 : paper\n3 : scissors\n")
j=0
k=0
n=0
while n!=100: 
  a=random.randint(1, 3)
  b=int(input("Enter your move "))
  if(a==b):
    if a==1:
      print("stone")
    elif a==2:
      print("paper")
    else:
      print("scissors")
    print("draw\n")
    
  elif((a==1 and b==2 ) or (a==2 and b==3 ) or (a==3 and b==1 )):
    j=j+1
    if a==1:
      print("stone")
    elif a==2:
      print("paper")
    else:
      print("scissors")
    print("you won\n")
  elif ((a==2 and b==1 ) or (a==3 and b==2 ) or (a==1 and b==3 )):
    k=k+1
    if a==1:
      print("stone")
    elif a==2:
      print("paper")
    else:
      print("scissors")
    print("you lost\n")
  else:
    
    print("wrong input\n") 
  if j==3 :
    n=100
    print("you won the game!!")
  elif k==3 : 
    n=100
    print("you lost the game!!!")
