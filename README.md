    Text Encryption/Decryption with RSA Key Generation Web Tool



This simple web application allows users to input text, which can then be encrypted or decrypted using the AES-256-CBC algorithm. Additionally, the app offers functionality to generate RSA key pairs (both public and private keys).
Features

    Encrypt and decrypt text using AES-256-CBC.
    Display the encrypted or decrypted text directly on the web page.
    Generate RSA key pairs (public and private keys).
    View the generated RSA keys on the web page.
    Responsive design with basic styling.

Prerequisites

    Node.js
    npm (Node Package Manager)

Installation

    Clone the repository:

    bash

git clone https://github.com/Esom/gmc-final-project.git

Install the necessary dependencies:

bash

    npm install

Usage

    Start the server:

    bash

    node server.js

    Open your browser and navigate to http://localhost:3000.

Text Encryption/Decryption

    To encrypt text: Enter the text in the input field and click the "Encrypt" button. The encrypted text will be displayed below.
    To decrypt text: Enter the encrypted text in the input field and click the "Decrypt" button. The decrypted text will be displayed below.

RSA Key Generation

    Choose the desired key length from the dropdown menu (1024, 2048, or 4096).
    Click the "Generate key pair" button. The generated RSA private and public keys will be displayed in the respective text areas.


