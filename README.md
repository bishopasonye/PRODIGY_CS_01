Caesar Cipher
A Python implementation of the Caesar Cipher, one of the simplest and most widely known encryption techniques. The Caesar Cipher works by shifting each letter in the plaintext by a fixed number of positions in the alphabet.

Description
The Caesar Cipher is a basic encryption algorithm that shifts the letters of a message by a certain number of positions in the alphabet. This method of encryption is named after Julius Caesar, who used it in his private correspondence. It is a type of substitution cipher where each letter in the plaintext is replaced by a letter some fixed number of positions down or up the alphabet.

How It Works:
Given a plaintext message, each letter is shifted by a set number (referred to as the "key").
The same key is used to decrypt the ciphered text by reversing the shift.
For example, with a shift of 3:

Plaintext: HELLO
Ciphertext: KHOOR
This project provides both encryption and decryption functionalities for the Caesar Cipher.


Features

Encryption: Encrypts a given plaintext message by shifting letters according to the key.
Decryption: Decrypts a ciphered message using the same key, reversing the shift.
Support for Upper and Lower Case Letters: Both upper and lower case letters are handled.
Non-Alphabet Characters: Special characters, numbers, and spaces remain unchanged.

Installation
Clone the repository:
git clone https://github.com/bishopasonye/PRODIGY_CS_01

Navigate into the project directory:

bash
cd caesar-cipher

(Optional) Create and activate a virtual environment:

bash

python -m venv venv

source venv/bin/activate   # On Windows: venv\Scripts\activate
Run the script:

bash
python caesar_cipher.py

Encrypting a Message
To encrypt a message, run the script and follow the prompts to input your plaintext and key (the shift amount).

Enter the text to encrypt: HELLO WORLD
Enter the shift key (number): 3
Encrypted text: KHOOR ZRUOG







Contact
For questions or suggestions, please contact Charles Asonye

Email
bishopasonye@gmail.com

LinkedIn
https://www.linkedin.com/in/charles-asonye
