# Vigenere Cryptographic Algorithm
This cryptographic algorithm is known as the Vigenere cipher. It is often used for low-security applications. The first byte of the file is encrypted with the first character of the password, the second byte with the second character, and so on. If all the characters of the password have been used, the next byte of the file is encrypted with the first character again.

To encrypt the byte with the character typically the XOR operation is used. This operation has the property that if you apply it twice with the same character, you get the original byte back. This makes it extremely easy to implement encryption and decryption.
