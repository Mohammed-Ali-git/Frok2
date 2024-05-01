# Encrypt Decrypt Tool

Description:
This Python-based Encrypt Decrypt Tool is a versatile command-line utility capable of encrypting and decrypting files of various formats, including mp3, jpeg, png, txt, and more. It employs the Fernet encryption algorithm, ensuring robust security for your sensitive data.

Features:

Encryption and Decryption: Allows users to encrypt and decrypt files of various formats, providing flexible data protection.
Support for Multiple File Formats: Capable of encrypting and decrypting files in formats such as mp3, jpeg, png, txt, and more, catering to diverse user needs.
Fernet Encryption: Utilizes the Fernet symmetric encryption algorithm, known for its strength and reliability in securing data.
Command-line Interface: Offers a straightforward command-line interface for seamless usage and integration into scripts and workflows.
File Input and Output: Supports specifying input and output file paths for encryption and decryption operations, enhancing user control and convenience.

Usage
python encrypt_decrypt_tool.py {encrypt|decrypt} input_file [--output_file OUTPUT_FILE]

Examples

Encrypt a file:
python encrypt_decrypt_tool.py encrypt sensitive_file.txt --output_file encrypted_file.txt
Decrypt a file:
python encrypt_decrypt_tool.py decrypt encrypted_file.txt --output_file decrypted_file.txt
