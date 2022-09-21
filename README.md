# Dice-Rolling-simulator
# A Dice rolling simulator is nothing but a computer model that can be created by a software program and it functions same as a normal dice in which user rolls a dice and a random number gets shown on the screen. There are many ways a dice simulator can be implemented.
import random
while True:
print('''1.roll the dice 2.To exit ''')
user = int(input("what you want to do\n"))
if user==1:
	number = random.randint(1,6)
	print(number)
else:
	break
