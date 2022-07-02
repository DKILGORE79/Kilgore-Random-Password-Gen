GIVEN I need a new, secure password
# PHASE 1
## STEP 1
```
THEN I am presented with a series of prompts for password criteria
WHEN prompted for password criteria
THEN I select which criteria to include in the password
WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters
```
1. how long is the password? make this show up on screen
should the user be able to type what they want- YEs
1a. check if less than 8 - this is bad
1b. check if greater than 128 - also bad
1c. Needs to be valid.

## STEP 2
```
WHEN asked for character types to include in the password
THEN I confirm whether or not to include lowercase, uppercase, numeric, and/or special characters

should the user be able to type what they want?
only acceptable answer is yes or no
boolean should suffice.
1.ask for lowercase
2.upppercase
3.numeric
4. special chara


## Step 3
```
WHEN I answer each prompt
THEN my input should be validated and at least one character type should be selected

make sure the user selects on of the four confirms,


```
## PHASE 3
```
WHEN all prompts are answered
THEN a password is generated that matches the selected criteria
```

1. guarantee we at least 1 character of each required type.
1. if any of the confirms are true add a character to your password. just one