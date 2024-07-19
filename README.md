# Random Password Generator Script

Overview

This script generates a list of secure passwords using a combination of 
uppercase letters, lowercase letters, digits, and symbols. 
The passwords are generated based on predefined criteria and can be used 
for various security purposes.

Features

Generates multiple passwords.
Customizable character set including uppercase letters, lowercase letters, digits, and symbols.
Allows setting the length of each password.
Easy to modify the criteria for including different types of characters.

# Usage

1. Character Sets:

upper_case: A string containing all uppercase letters.
lower_case: A string containing all lowercase letters.
digits: A string containing digits from 0 to 9.
symbols: A string containing various symbols for added complexity.

3. Configuration:

upper: Boolean value to include uppercase letters in the passwords.
lower: Boolean value to include lowercase letters in the passwords.
nums: Boolean value to include digits in the passwords.
sym: Boolean value to include symbols in the passwords.
all: An empty string that will be populated with the selected character 
sets based on the above boolean values.

4. Password Length and Amount:

length: The length of each generated password. Default is set to 20 characters.
amount: The number of passwords to generate. Default is set to 10 passwords.

5. Generating Passwords:

The script loops through the number of passwords specified by amount and generates 
each password by randomly sampling characters from the all string.
Each password is printed to the console.

# Notes

The generated passwords are printed to the console. For better security, 
consider saving them to a secure location instead of printing them.
Ensure that the password length and character set meet your security requirements. 
Longer passwords with a mix of character types are generally more secure.


This README provides a comprehensive guide on how to use and customize the password generator script. 
If you have any further questions or need additional functionality, feel free to modify the script 
as needed.







