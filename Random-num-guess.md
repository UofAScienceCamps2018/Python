# Random Number Guessing Game 
The goal of this program is get the computer to select a random number and take in a user input, check if the two numbers match and tell the user if they are right or wrong.  
## Sample input ## 
    >>Please guess a number between 1 and 20: 7
    >>Good guess the computer also guessed 7!
## Reference ##
#### `print` ####
You will use this command to display messages to the user. `print("Hello World")` 
#### `input` ####
This command is used to take in user inputs. `input("Please enter your name")`

    name = input("Please enter your name")

#### Data types ####
Python has many different data types some of the main ones are:

String(`str`)   Integer(`int`)   Float(`float`)  Boolean(`bool`)

To convert between data types, use the following:

    num=int(numberString)
#### Logic ####
Logical operators and conditional statements are used by the computer to make decisions. 

       if (name=="Yasas"):
            ....
        elif(name="Tem"):
            ....
        else:
            ....
The operators `and`, `or` can also be used. 
#### Random ####
To generate random number, we must import a module called random. 

    import random
    rand_I=random.randint(min,max)
    
## Extension ##
If you have finished the first part of this program and have got it checked over move on to these extensions. 

#### Extension 1 ####
Now put this program in a loop so the program will automatically restart once if the user selects the wrong answer. 
#### Extension 2 #### 
Add lives so the user has 3 guesses for the same random number. 
#### Extension 3 #### 
Make the program say if the users guess is higher or lower than the random number.
