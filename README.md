# PRODIGY_CS_02
Image encryption tool using pixel manipulation

# Image Encryption Tool Using Pixel Manipulation 🖼️🔒

## Overview
The Image Encryption Tool is a Python-based application designed to encrypt and decrypt images using pixel manipulation techniques. This project demonstrates how to manipulate image data at the pixel level, ensuring the security and privacy of visual content.

## Features
- **Image Encryption**: Encrypts images by manipulating pixel values using various mathematical operations.
- **Image Decryption**: Restores the original image from the encrypted data.
- **Support for Various Formats**: Works with common image formats (e.g., PNG, JPEG).
- **User-Friendly Interface**: Simple command-line interface for easy interaction.

## Technologies Used
- **Python**: The primary programming language for this implementation.
- **PIL (Pillow)**: A Python library used for opening, manipulating, and saving image files.
- **NumPy**: A library used for efficient array manipulation and mathematical operations.

## Installation
1. **Clone the Repository**:
  
   git clone https://github.com/your_username/Image-Encryption-Tool.git
   cd Image-Encryption-Tool
Install Dependencies: Ensure you have Python installed, then install the required libraries:

pip install pillow numpy
Run the Program: You can run the program directly using Python:

python image_encryption_tool.py
Usage
Encrypt an Image:

Provide the path to the image you want to encrypt.
Specify the output path for the encrypted image.
The program will process the image and save the encrypted version.
Decrypt an Image:

Provide the path to the encrypted image.
Specify the output path for the decrypted image.
The program will restore the original image from the encrypted data.
Example
Encrypting an Image
plaintext

Enter path to image: image.png
Enter output path for encrypted image: encrypted_image.png
Encryption successful! Encrypted image saved as encrypted_image.png.
Decrypting an Image
plaintext

Enter path to encrypted image: encrypted_image.png
Enter output path for decrypted image: decrypted_image.png
Decryption successful! Original image restored as decrypted_image.png.
Contributing
Contributions are welcome! If you would like to contribute, please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Commit your changes.
Push to your branch.
Create a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Disclaimer
This tool is intended for educational purposes and should be used ethically. Ensure that you have the right to encrypt and decrypt the images you are working with. Unauthorized use of encryption tools may lead to legal consequences.


Push to GitHub: Finally, push the changes to your GitHub repository:

git push origin main
