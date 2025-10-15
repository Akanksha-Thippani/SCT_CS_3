# Password Strength Checker 🛡️

A simple Python program that checks the strength of a password based on common security criteria.  


## Features

- Checks if the password length is **at least 8 characters**
- Checks for **lowercase letters**
- Checks for **uppercase letters**
- Checks for **numbers**
- Checks for **special characters** (`!@#$%^&*()-_=+[]{};:'",.<>?/|`~`)
- Gives a strength rating: **Weak**, **Moderate**, or **Strong**


## How It Works

The program assigns a score for each criteria the password meets:

1. Length ≥ 8 → +1 point  
2. Contains lowercase → +1 point  
3. Contains uppercase → +1 point  
4. Contains digits → +1 point  
5. Contains special characters → +1 point  

Strength levels:  
- 0–2 points → Weak  
- 3 points → Moderate  
- 4–5 points → Strong  

## Requirements

Python 3.x

