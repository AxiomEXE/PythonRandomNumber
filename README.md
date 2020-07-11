# PythonRandomNumber
Python Random Number Game

```
#!/usr/bin/python3

import random

num = random.randint(1, 10)
while True:
	print('Pick a number between 1 and 10')
	guess = input()
	i = int(guess)
	if i == num:
		print('Correct!')
		break
	elif i < num:
		print('Higher.')
	elif i > num:
		print('Lower.')

```
