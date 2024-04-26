# LuckyPerson
# Jarirtech
import random 
names = names_string.split(", ")
# names_string contains the input values provided. 
# The code above converts the input into an array seperating
# each name in the input by a comma and space.
# get the total of names
num_items=len(names)
#generate random numbers between 0 and the last index in names(-1)
random_choice = random.randint(0, num_items-1)
# pick out a person from the list
The_Lucky_Person = names[random_choice]
print(The_Lucky_Person+ " is the lucky person!")
