# PRODIGY_CS_01
# Caesar Cipher Tkinter Application

## Overview

This is a simple graphical user interface (GUI) application for encrypting and decrypting text using the Caesar Cipher method. The application is built using Python's Tkinter library and provides a user-friendly way to apply Caesar Cipher encryption and decryption to text.

## Features

- **Encrypt**: Convert plain text into encrypted text using a Caesar Cipher with a specified shift value.
- **Decrypt**: Convert encrypted text back to plain text using the same shift value.
- **User Interface**: A clean and intuitive interface with text areas for input and output, and entry fields for shift value.

## Requirements

- Python 3.x
- Tkinter (included with Python standard library)

## Installation

1. **Clone the Repository** (if applicable):
   
   git clone https://github.com/Anasmc24/PRODIGY_CS_01/tree/main
   cd caesar-cipher-tkinter

Install Python (if not already installed):
Download and install Python from python.org.

Run the Application:

Navigate to the directory containing the Python script and run:
python caesar_cipher_app.py

Using the Application:
Input Text: Enter the text you want to encrypt or decrypt in the "Input Text" area.
Shift Value: Enter the shift value for the Caesar Cipher. For example, a shift value of 3 will shift letters by 3 positions in the alphabet.
Encrypt Button: Click this button to encrypt the input text with the specified shift value.
Decrypt Button: Click this button to decrypt the input text with the specified shift value.
Output Text: View the encrypted or decrypted text in the "Output Text" area.

Example

Encrypt:

Input Text: Hello, World!
Shift Value: 3
Output Text: Khoor, Zruog!
Decrypt:

Input Text: Khoor, Zruog!
Shift Value: 3
Output Text: Hello, World!
Code Explanation
Encryption Function: encrypt(text, shift) - Encrypts the input text by shifting each letter by the specified value.
Decryption Function: decrypt(text, shift) - Decrypts the input text by shifting each letter in the opposite direction.
GUI Class: CaesarCipherApp - Handles the layout and functionality of the Tkinter interface.
