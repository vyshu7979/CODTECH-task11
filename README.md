# CODTECH-task11
Name:CHENU VAISHNAVI
company:CODETECH IT SOLUTIONS
domain:cybersecurity and ethical hacking
duration:august to september 2024
mentor:CT08DS5959
Overview of the project
project:PASSWORD STRENGTH CHECKER
Explanation
Length:

The tool checks the length of the password. Longer passwords are generally stronger.
Scores are awarded based on thresholds (e.g., 12+ characters = strong).
Complexity:

The tool checks for the presence of lowercase letters, uppercase letters, digits, and special characters. The more categories your password covers, the more complex it is.
Uniqueness:

The tool estimates entropy by counting unique characters in the password. A more diverse set of characters increases the score.
Overall Strength Assessment:

The tool aggregates the scores from length, complexity, and uniqueness to classify the password as "Strong," "Moderate," or "Weak."
Usage
To use the tool, simply create an instance of PasswordStrengthChecker with a password string, and call assess_strength() to get a report on the password's strength.

This implementation can be extended with additional checks, such as common password dictionary attacks or more sophisticated entropy calculations for a more advanced password assessment.
Technologies used:
1. Python Programming Language
Core Technology: The entire tool is written in Python, a versatile and popular programming language. Python is chosen for its simplicity and readability, making it an excellent choice for implementing security tools.
2. Regular Expressions (Regex)
Module: re
Purpose: Regex is used to search for specific patterns in the password, such as the presence of lowercase letters, uppercase letters, digits, and special characters. This helps determine the complexity of the password.
Example: re.search(r'[a-z]', self.password) checks for lowercase letters.
