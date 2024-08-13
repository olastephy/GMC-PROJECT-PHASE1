AES and RSA Cryptography Web Application

This project is a web-based tool designed to demonstrate and facilitate the use of cryptographic algorithms for secure data handling. The application supports two primary functionalities:

    AES Encryption/Decryption:
        AES (Advanced Encryption Standard) is a symmetric encryption algorithm used to secure data through encryption. This project implements AES encryption and decryption features to allow users to encode and decode text using a shared secret key.
        Features:
            Encrypt with AES: Users can input plain text and encrypt it using a predefined secret key. The encrypted text is displayed in a separate output area.
            Decrypt with AES: Users can decrypt previously encrypted text to retrieve the original plain text.

    RSA Key Pair Generation and Encryption/Decryption:
        RSA (Rivest-Shamir-Adleman) is an asymmetric encryption algorithm that uses a pair of keys: a public key for encryption and a private key for decryption. This project includes functionalities to generate RSA key pairs and use them for encrypting and decrypting text.
        Features:
            Generate RSA Key Pair: Users can select a key length (1024 or 2048 bits) and generate a pair of RSA keys (public and private). These keys are displayed for use in subsequent encryption and decryption operations.
            Encrypt with RSA: Users can encrypt text using the RSA public key.
            Decrypt with RSA: Users can decrypt encrypted text using the RSA private key.

Components:

    HTML: Provides the structure for the web interface, including input fields for text, buttons for cryptographic actions, and text areas for displaying results.
    CSS: (External file, styles.css) Used for styling the application to enhance its visual appeal and usability.
    JavaScript: Handles the logic for AES and RSA operations using the CryptoJS and JSEncrypt libraries. This includes functions for encryption, decryption, and key generation.

Libraries Used:

    CryptoJS: A JavaScript library for cryptographic algorithms, specifically used for AES encryption and decryption.
    JSEncrypt: A JavaScript library for RSA encryption and decryption, used to handle RSA key pair generation and operations.

Usage:

    AES: Enter text into the input field and use the provided buttons to encrypt or decrypt the text with AES.
    RSA: Generate RSA keys, and use the generated keys to encrypt or decrypt text through the respective RSA functions.

Potential Enhancements:

    Implement more robust key management practices.
    Add user authentication to secure access to the cryptographic features.
    Improve error handling and user feedback.

This project serves as a practical demonstration of cryptographic concepts and provides a functional interface for basic encryption and decryption tasks.

PUBLIC URL:    http://127.0.0.1:5500/index.html
