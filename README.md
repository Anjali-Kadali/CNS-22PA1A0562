Caesar Cipher Encryption and Decryption

This repository contains a simple Python implementation of the Caesar cipher for encrypting and decrypting messages.

Overview

The Caesar cipher is a basic encryption technique where each letter in the plaintext is shifted a fixed number of places in the alphabet. This script allows users to:

Encrypt a given message using a shift value.

Decrypt the encrypted message back to its original form.

Features

Encrypts plaintext using a specified shift value.

Decrypts ciphertext by reversing the shift.

Handles both uppercase and lowercase letters.

Retains non-alphabetic characters unchanged.

Usage

Running the Script

Ensure you have Python installed on your system, then execute the script:

python caesar_cipher.py

Input

The script will prompt you for:

A message to encrypt.

A shift value (between 1 and 25).

Example

Input:

Enter the message: Hello, World!
Enter the shift value (1-25): 3

Output:

Encrypted message: Khoor, Zruog!
Decrypted message: Hello, World!

Functions

caesar_encrypt(plain_text, shift)

Encrypts the input text by shifting each letter forward.

caesar_decrypt(cipher_text, shift)

Decrypts the input text by reversing the shift.

main()

Handles user input and displays the encrypted and decrypted messages.

