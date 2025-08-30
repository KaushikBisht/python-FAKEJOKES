# python-FAKEJOKES
fun mini program in python using concepts of list ,string concatination and all to generate jokes, its just a for fun no intention to make fun of anyone.

import random
choice=1
while(choice):
 print("enter the choice wanna continue or not :")
 choice=int(input("enter the choice yes or no"))
 subjects=["prime minister ", "Shahrukh khan","Viratkohli","jacky shroff"," krish"]
 actions=["launches","eating","dancing in ","bathing"]
 objects=["in tajmahal","front of redfort","on burjkhalifa","on mountains"]
 print(f"sentece:{random.choice(subjects)+" "+random.choice(actions)+" "+random.choice(objects)}")
