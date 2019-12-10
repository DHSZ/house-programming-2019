# Task 4 - Breaking and entering

Mr. Yim is ready to drive home after a long day but has left his car keys in the teachers office!

Unfortunately, the school has just installed a new security system on the front door and he has forgotten the passcode to get back into the building.

There are 8 total buttons on the security system, 4 numbers and 4 letters: 
```
 _________________
|                 |
| School security | 
|                 |
| [0] [1] [2] [3] |
|                 |
| [A] [B] [C] [D] |
|                 |
|_________________|
```

Mr. Yim remembers these facts about the passcode:
- It is 3 characters long
- The first 2 characters are definitely numbers
- The last character is a letter

Mr. Yim begins working through all of the possible combinations:
```
00A
00B
00C
00D
01A
01B

etc...
```

Write a program that **lists all possible inputs** and **counts the total number of combinations** Mr. Yim may need to try to get into the office.

## Bonus - What is the correct number?!

When the user inputs their code, it is read as a hexadecimal number and then converted into a denary number.

The correct passcode stored as a **denary number is 59**
