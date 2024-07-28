# CryptoApply Tool

This is a simple cryptography tool that can encrypt and decrypt text using four different algorithms: Shift, XOR, DES, and AES. The tool features a simple GUI built with Python.

## Features

- **Shift Cipher**: A basic substitution cipher where each letter in the plaintext is shifted a certain number of places down the alphabet.
- **XOR Cipher**: A symmetric key encryption algorithm that uses the XOR bitwise operation.
- **DES (Data Encryption Standard)**: A symmetric-key algorithm for the encryption of digital data.
- **AES (Advanced Encryption Standard)**: A symmetric encryption algorithm widely used across the globe.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/John-A0/CryptoApply.git
    ```
2. Navigate to the project directory:
    ```bash
    cd CryptoApply
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the main script to start the GUI:
    ```bash
    python3 CryptoApply.py
    ```
2. Select the encryption/decryption algorithm.
3. Enter the text and key (if required).
4. Click the "Encrypt" or "Decrypt" button to see the result.

## Dependencies

- Python 3
- Tkinter (for GUI)
- PyCryptodome (for AES)
- pyDes (for DES)
- xorencryption (for XOR)

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request.

## Acknowledgments

- Thanks to the developers of the libraries used in this project.
- Special thanks to John for developing this tool.

