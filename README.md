# Steganography-Hiding-text-in-image
# Steganography Project

## Overview

This project is a simple implementation of steganography, a technique for hiding information within an image. The program takes an input image and a secret message, performs encryption by embedding the message in the image, and saves the result as a new image file. The encrypted image can later be decrypted to retrieve the original message.

## Features

- **Encryption:** Embed a secret message within an image.
- **Decryption:** Retrieve the original message from an encrypted image.

## Requirements

- Python 3.x
- OpenCV library (install using `pip install opencv-python`)

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/gauravjha-hackerboy/Steganography-Hiding-text-in-image.git
    cd steganography-project
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the program:

    ```bash
    python steganography.py
    ```

    Follow the on-screen prompts to enter the input image, secret message, and perform encryption/decryption.

## Example

```bash
python steganography.py
