# Secret Message

A simple Python command-line tool for encrypting and decrypting text messages using Fernet symmetric encryption.

Originally built as an early coding project, this tool demonstrates basic encryption concepts, key generation, and message handling in Python.

## Features

* Generate a new Fernet encryption key
* Use an existing key to decrypt previous messages
* Encrypt plain text into a secure token
* Decrypt encrypted messages back into readable text
* Simple command-line interface
* Optional background audio using `pygame`

## Disclaimer

This project is intended for educational purposes only. It is not designed for production-grade security or sensitive real-world use.

Please do not copy or redistribute this project without credit.

## Credits

Created by **Abhinav Ranish**

* GitHub: `abhinav-ranish`
* Marco B — Stack Overflow
  https://stackoverflow.com/a/69043349/14836433

## Installation

Clone the repository:

```bash
git clone <repo-url>
cd secret-message
```

Install the required dependencies:

```bash
pip install cryptography pygame
```

Make sure the `bis.wav` audio file is in the same directory as the Python script.

## Usage

Run the program:

```bash
python main.py
```

You will be asked whether you already have a key.

* Enter `y` if you want to use an existing key.
* Enter `n` if you want to generate a new key.

If a new key is generated, save it somewhere safe. You will need the same key to decrypt your messages later.

## Example Flow

```text
Do You Have A Key? (yes - y and no - n)
n

Please keep this key safely:
-------------------------------------------
<your-generated-key>
-------------------------------------------

Do You Want to Encode Or Decode The Message?
Encode = e, Decode = d, quit = q
```

## Important Notes

* Losing your key means you cannot decrypt your messages.
* Anyone with your key can decrypt your encrypted messages.
* This project is mainly for learning how encryption works in Python.

## Donation

If you found this useful and would like to support my work:

https://paypal.me/AbhinavRanish

## License

Open source for educational use. Please provide proper credit if you reuse or modify this project.
