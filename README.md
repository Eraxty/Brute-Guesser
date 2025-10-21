# Password Brute-Force Demo

This is a simple Python script that demonstrates a basic brute-force approach to "guessing" a password. It uses a growing-list method to try all combinations of lowercase letters up to a certain length.

## How it works

- The user enters a password.
- The script generates all possible combinations of lowercase letters (`a-z`) 
- It checks each generated combination to see if it matches the entered password.
- When the password is found, it stops and prints the password along with the time taken.

## How to run

1. Make sure you have Python 3 installed.
2. Save the script as `brute_force_demo.py`.
3. Open a terminal and run:

```bash
python brute_force_demo.py
```

### Enter a password (keep it short to avoid very long run times).

## Notes

-Long passwords or large character sets will cause extremely long run times.
-Numbers and punctuations are not included
