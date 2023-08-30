# ceasercipher

The provided C++ program demonstrates a simple implementation of the Caesar cipher encryption method with a user-friendly input mechanism. This program showcases both the caesarEncrypt function, which performs the encryption, and the main function, serving as the entry point of the program.

The caesarEncrypt function processes an input text and encryption key provided by the user. For each character in the text, the function checks if it is an alphabetic character. If it is, the function calculates a shifted position based on the key and handles both uppercase and lowercase letters. The resulting encrypted text is constructed and returned. Characters that are not part of the alphabet are included as is in the encrypted text.

In the main function, the user is prompted to input the original text they wish to encrypt and the encryption key they intend to use. The program utilizes std::getline to read the entire line of the original text and std::cin to acquire the encryption key. The std::cin.ignore() function is applied to ensure that any newline character in the input buffer does not affect the subsequent operations. Finally, the program calls the caesarEncrypt function to generate the encrypted text and displays both the original and encrypted texts.
