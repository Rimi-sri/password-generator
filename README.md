
# password generator
The PyPassword Generator is a Python project designed to create highly secure passwords tailored to user preferences. This project focuses on randomness and strength, ensuring passwords are unpredictable and resistant to brute-force attacks.

Users can interact with the program via a simple command-line interface to specify:

Number of letters: The count of alphabetic characters (both uppercase and lowercase) in the password.

Number of symbols: The count of special characters such as !, #, or $.

Number of numbers: The count of numeric digits in the password.

The project features two modes:

Easy Level (optional): Generates a password by appending characters in the specified sequence (letters, symbols, and numbers) without additional randomization.

Hard Level (default): Creates a more secure password by shuffling the characters after generation, making the sequence truly random.

The program uses Python’s random module to:  Select random characters from predefined lists of letters, numbers, and symbols.
