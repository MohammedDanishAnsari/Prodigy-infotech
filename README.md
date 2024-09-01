How the Program Works:
Encrypt Function:

Converts each character in the input text to a new character by shifting its position in the alphabet by the specified shift value.
Handles both uppercase and lowercase letters, keeping other characters (like spaces and punctuation) unchanged.

Decrypt Function:
Reverses the encryption by shifting each character in the encrypted text back by the same shift value.
Main Function:

Asks the user whether they want to encrypt or decrypt a message.
Prompts for the message and the shift value.
Calls the appropriate function based on the user's choice and displays the result.

Example Usage:
If the user inputs "Hello World" with a shift value of 3 for encryption, the output will be "Khoor Zruog".
Decrypting "Khoor Zruog" with a shift value of 3 will return "Hello World".
