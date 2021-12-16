# Python-1-Rock-Paper-ans-Scissors-game-
import random
dict={0:"rock",1:"paper",2:"scissors"}
num=random.randint(0,2)
robot=dict[num]
you=input("Enter your choice between Rock,Paper or scissors:").lower()
if you==robot:
    print(f"Tie As Your choice is {you} and the robot's chose is {robot}")
elif you=="rock" and robot=="paper":
    print(f"Robot won!! As Your choice is {you} and the robot's choice is {robot}")
elif you=="rock" and robot=="scissors":
    print(f"You won!! As Your choice is {you} and the robot's choice is {robot}")
elif you=="paper" and robot=="scissors":
    print(f"Robot won!! As Your choice is {you} and the robot's choice is {robot}")
elif you=="paper" and robot=="rock":
    print(f"You won!! As Your choice is {you} and the robot's choice is {robot}")
elif you=="scissors" and robot=="paper":
    print(f"You won!! As Your choice is {you} and the robot's choice is {robot}")
elif you=="scissors" and robot=="rock":
    print(f"Robot won!! As Your choice is {you} and the robot's choice is {robot}")
