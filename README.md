# Caesar Cipher Application using python

This project is a graphical user interface (GUI) application built with Python's Tkinter library that allows users to encrypt and decrypt messages using the Caesar Cipher algorithm. Users can input a message and a shift value, select an operation (encrypt or decrypt), and view the result, which can also be copied to the clipboard.

## Features

- **Graphical User Interface**: Easy-to-use interface for encryption and decryption.
- **Encrypt and Decrypt Messages**: Users can shift letters in a message by a specified number.
- **Clipboard Support**: Resulting messages can be copied to the clipboard with a click.
- **Error Handling**: Validates user input for the shift value.

## Prerequisites

- Python 3.12 installed on your machine.
- Tkinter library (usually included with standard Python installations).

##**Example**

Encrypting a Message

Enter: hello

Shift value: 3

Result: Encrypted Message: khoor

#Decrypting a Message

Enter: khoor

Shift value: 3

Result: Decrypted Message: hello

#Error Handling

If the shift value is not a valid integer, an error message will prompt the user to enter a valid value.
