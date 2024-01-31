# PctApp Cryptography

PctApp Cryptography is a simple Python program that provides a graphical user interface (GUI) for encrypting and decrypting text messages using a secret key. The program utilizes the `base64` module for encoding and decoding messages.

## Features

- **Encryption:** Input a text message and a secret key to encrypt the message.
- **Decryption:** Input an encrypted message and the correct secret key to decrypt the message.
- **Password Protection:** The program requires a password (in this case, "1234") to access the encryption and decryption features.

## Getting Started

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/PctApp-Cryptography.git
    cd PctApp-Cryptography
    ```

2. **Install Dependencies:**
   - Ensure you have Python installed.
   - The program relies on the standard library, and no additional external dependencies are required.

3. **Run the Program:**
    ```bash
    python main.py
    ```
    This will launch the GUI for the cryptography application.

4. **Usage:**
   - Enter the text you want to encrypt or decrypt in the provided text area.
   - Enter the secret key in the password field (default password is "1234").
   - Click the "ENCRYPT" or "DECRYPT" buttons to perform the respective operation.
   - The result will be displayed in the output text area.

5. **Reset:**
   - Click the "RESET" button to clear the input fields.

## Important Note

- Ensure that you remember the secret key ("1234" by default) used for encryption, as it is required for decryption.

## Contributions

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

*This cryptography code is a part of the PctApp project. For more information, visit [https://github.com/Ranadip213/PctApp](https://github.com/Ranadip213/PctApp).*
