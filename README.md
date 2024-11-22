# Encrypter-Decrypter
This is a simple C++ program for encrypting and decrypting text files using a user-specified numerical key. The tool transforms the contents of a file by shifting each character based on the provided key, allowing for basic text security. 
Features
File Encryption: Converts a plaintext file into an encrypted file using a custom key.
File Decryption: Restores the original file from an encrypted file using the same key.
User Input: Dynamically input file names and keys for flexible usage.
Ease of Use: Intuitive interface with clear prompts for encryption or decryption.

How It Works
Encryption:

Each character in the input file is shifted forward by the key value.
The resulting characters are written to an encrypted file.
Decryption:

Each character in the encrypted file is shifted backward by the key value.
The resulting characters are restored to the original plaintext.
