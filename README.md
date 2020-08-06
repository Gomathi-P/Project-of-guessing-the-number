Project of guessing the number


In [ ]:
import random
a=0
n=random.randint(1,20)
while a<4:
   print("Guess a number between 1 to 20")
   guess=int(input())
   print(guess)
   a=a+1
   if guess<n:
     print("Your guess is too low")
   if guess>n:
     print("Your guess is too large")
   if guess==n:
     break
if guess==n:
    a=str(a)
    print("You guessed correctly")
if guess!=n:
    n=str(n)
    print("Try again")
Guess a number between 1 to 20
5
5
Your guess is too low
Guess a number between 1 to 20
15
15
Your guess is too large
Guess a number between 1 to 20
10
10
Your guess is too large
Guess a number between 1 to 20
8
8
You guessed correctly
