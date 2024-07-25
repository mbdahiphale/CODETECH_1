# CODETECH_1

Name : Mahesh Bajirao Dahiphale
Company : CODTECH
ID : CT08DS4465
Domain : Cyber Security and Ethical Hacking
Duration : july to august 2024

overview :
This Python code defines a function `check_password_strength` that evaluates the strength of a given password based on several criteria. Here's an overview of how it works:

1. **Initial Setup**: 
   - The function initializes a `score` variable to zero, which will be used to accumulate points based on password characteristics.

2. **Length Check**:
   - The function checks the length of the password. If it is at least 8 characters long, it adds 1 point to the score. If it is at least 12 characters long, it adds another point.

3. **Complexity Check**:
   - The function uses regular expressions to check for the presence of lowercase letters, uppercase letters, digits, and special characters (`@#$%^&+=`). Each presence adds 1 point to the score.

4. **Uniqueness Check**:
   - The function compares the password against a list of common passwords. If the password is not in the list, it adds 1 point to the score.

5. **Feedback Based on Score**:
   - Based on the total score, the function provides feedback on the password's strength:
     - A score of 6 or more points results in "Strong password".
     - A score between 4 and 5 points results in "Moderate password".
     - A score of less than 4 points results in "Weak password".

6. **User Interaction**:
   - The code takes user input for the password, calls the `check_password_strength` function, and then prints the feedback along with the calculated score.

This function is useful for evaluating password strength and providing users with immediate feedback to encourage the creation of stronger, more secure passwords.
