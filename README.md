# Password-Strength-Checker
A Python-based cybersecurity tool to help users test password strength, generate secure passwords, save them to a file with timestamps, and view saved passwords. Built as a personal project to learn Python and explore cybersecurity concepts.

# Features
1. Test Password Strength: Evaluates passwords for length (≥8 characters), uppercase, lowercase, digits, and special characters, with SHA-256 hashing to simulate secure storage.
2. Generate Secure Passwords: Creates random passwords with user-defined length (minimum 8) using Python’s secrets module for cryptographic security.
3. Save Passwords: Stores generated passwords with timestamps in passwords.txt.
4. View Saved Passwords: Displays previously generated passwords from the file.
5. Common Password Check: Warns if the tested password is common (e.g., "password", "123456").
6. Colored Interface: Uses colorama for color-coded output (green for Strong, yellow for Medium, red for Weak/errors).

# How to Use
1. Run the program (python main.py).
2. Choose an option (1–4):
3. 1: Test a password’s strength (e.g., "Test@123!" for Strong).
4. 2: Generate a secure password (enter a length ≥8).
5. 3: Exit the program.
6. 4: View saved passwords in passwords.txt.
7. Follow prompts to enter passwords or lengths.
8. Check passwords.txt in the project directory for saved passwords.

# Example Output
========================================
 Welcome to Password Strength Checker!
 Developed by Sandeep Kumar (2025)
========================================

--- Menu ---
1. Test a password
2. Generate a secure password
3. Exit
4. View saved passwords
5. • Enter 1, 2, 3, or 4: 1
6. • ========================================
7. • Enter a password: Test@123!
8. • Hashed password (SHA-256): 315f5bdb76d078c43b8ac0064e4a0164612b1fce77c869345bfc94c75894edd3
9. • Password Strength: Strong
10. • Great job! Your password is secure.

========================================
 Welcome to Password Strength Checker!
 Developed by Sandeep Kumar (2025)
========================================

--- Menu ---
1. Test a password
2. Generate a secure password
3. Exit
4. View saved passwords
5. • Enter 1, 2, 3, or 4: 2
6. • ========================================
7. • Enter desired password length (minimum 8): 10
8. • Generated secure password: X7#kP9@mL2
9. • Password saved to passwords.txt

========================================
 Welcome to Password Strength Checker!
 Developed by Sandeep Kumar (2025)
========================================

--- Menu ---
1. Test a password
2. Generate a secure password
3. Exit
4. View saved passwords
5. • Enter 1, 2, 3, or 4: 4
6. • ========================================
7. • Saved Passwords:
8. • [2025-06-13 10:00:00] X7#kP9@mL2

# Notes
1. Built for personal learning to explore Python and cybersecurity basics.
2. Does not store tested passwords (only generated passwords are saved).
3. Safe for learning; not intended for production use without additional security (e.g., salting hashes).

# Author
Developed by Sandeep Kumar as a personal project in June 2025.
