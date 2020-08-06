# toss-a-coin
Simulates the random tossing of a coin for head or tails.

This was inspired by a tutorial from WildCodeSchool.com's 10 hr Data Analyst Prep Course.
The code was generated & run with Jupyter Notebook in Anaconda.
Here is the code as text:

import random 
# Get the random module which gives access to randint function

toss = random.randint(1,2)
# Function random.randit generates a random integer between 1 and 2

if toss == 1:
  print("Heads")
else:
  print("Tails")
