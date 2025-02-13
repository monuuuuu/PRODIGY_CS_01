# Caesar Cipher Encryption Tool

This Python script implements a **Caesar Cipher** encryption and decryption system. It allows users to securely encode and decode messages using a shift-based substitution technique.

## Features
- Encrypts a message using the **Caesar Cipher** technique.
- Decrypts an encrypted message back to its original form.
- Ensures the message contains only **letters and spaces** (no numbers or special characters).
- Limits message length to **18 words**.
- Allows the user to choose a **shift value (1-25)** for encryption.
- Provides an option to **read (decrypt) or discard** an encrypted message.
- Includes **error handling** for invalid inputs.

## How It Works
1. The user enters a message.
2. The script validates the message and checks for any **invalid characters**.
3. The user enters a shift value (1-25).
4. The message is encrypted using the **Caesar Cipher** method.
5. The encrypted message is displayed.
6. The user chooses to **read (decrypt) or discard** the message.
7. If the user chooses to decrypt, the message is returned to its original form.

## Example Usage
```
Enter your message to the recipient (max 18 words):
HELLO WORLD

Enter shift value (1-25):
3

Encrypted Message: KHOOR ZRUOG

You have an unread message. Press 1 to read and 2 to discard:
1

Decrypted Message: HELLO WORLD
```

## Installation & Running the Script
1. Ensure you have **Python 3.x** installed.
2. Copy the script into a `.py` file.
3. Run the script using:
   
   python script_name.py
  

## Encryption & Decryption Logic
- **Encryption:** Each letter is shifted forward by a fixed number of positions.
- **Decryption:** The encrypted text is shifted backward by the same number of positions.

Example with shift `3`:
```
Plaintext:  HELLO
Ciphertext: KHOOR
```



