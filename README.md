# Python-password-checker
This is how you can code a password checker using python :)



Importing the necessary modules:
The code begins by importing the re module, which provides support for regular expressions in Python.

<img width="1005" alt="Screenshot 2023-07-03 at 2 44 40 AM" src="https://github.com/dormorr993310/Python-password-checker/assets/138055368/6bf5e4b2-52e4-4201-9377-8cf7e3331e14">



Defining the check_password_strength function:
The check_password_strength function takes a password as input and checks its strength based on certain requirements.
It uses a series of if and elif statements to check various conditions.
If the password fails any of the conditions, it returns a corresponding error message.
If the password meets all the requirements, it returns a message indicating that the password is strong.

<img width="1009" alt="Screenshot 2023-07-03 at 2 45 09 AM" src="https://github.com/dormorr993310/Python-password-checker/assets/138055368/9acba10b-ba4f-4970-95fa-dbfd6c2a443f">


Example usage:
The code prompts the user to enter a password using the input function and stores it in the password variable.
It then calls the check_password_strength function, passing the user's password as an argument.
The result of the function call is stored in the result variable.




Printing the result:
Finally, the code prints the result of the password strength check using the print function.
That's it! The code takes a user's input for a password, checks its strength according to certain requirements (minimum length, presence of digits, uppercase and lowercase letters, and special characters), and provides feedback on whether the password meets the criteria or not.
