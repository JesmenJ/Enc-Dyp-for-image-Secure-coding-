Image Encryption-Decryption Tool using Python
Introduction
The Image Encryption-Decryption Tool is a Python-based GUI application that allows users to encrypt and decrypt images. It provides an intuitive interface for visual encryption using randomly generated Gaussian noise as the key. The encrypted images become unintelligible and can only be restored to their original form using the same key.

Features
Select Images: Load images from your local file system.
Encrypt Images: Apply visual encryption using random Gaussian keys.
Decrypt Images: Restore the original image using the encryption key.
Reset Images: Reload the original image.
Save Images: Save the encrypted or decrypted image to a desired location.
Exit Application: Safely close the application with confirmation.
Prerequisites
Make sure you have the following dependencies installed:

Python 3.x
Pillow (PIL)
Install via:
bash
Copy code
pip install pillow
OpenCV
Install via:
bash
Copy code
pip install opencv-python
NumPy
Install via:
bash
Copy code
pip install numpy
How to Run the Application
Clone the Repository (if applicable):

bash
Copy code
git clone <repository_url>
cd <repository_folder>
Run the Python Script:

bash
Copy code
python image_encryption.py
Use the Application:

Click "Choose" to select an image from your local machine.
Click "Encrypt" to encrypt the image.
Click "Decrypt" to decrypt the image.
Click "Reset" to reload the original image.
Use "Save" to store the encrypted or decrypted image.
Exit the application using the "EXIT" button or close the window.
GUI Overview
Original Image Panel: Displays the original image.
Encrypted-Decrypted Image Panel: Shows the encrypted or decrypted version.
Buttons:
Choose: Load an image.
Encrypt: Encrypt the selected image.
Decrypt: Decrypt the encrypted image.
Reset: Reload the original image.
Save: Save the modified image.
EXIT: Close the application.
Code Structure
image_encryption.py: Main Python script with GUI logic and encryption-decryption functionality.
image_encrypted.jpg: Temporarily stores encrypted images during execution.
image_output.jpg: Temporarily stores decrypted images during execution.
How Image Encryption Works
The image is converted to grayscale.
A Gaussian noise matrix is generated as the encryption key.
Encryption Formula:
image_encrypted
=
image_input
key
image_encrypted= 
key
image_input
​
 
Decryption Formula:
image_output
=
image_encrypted
×
key
image_output=image_encrypted×key
Known Issues and Limitations
Works only with grayscale images.
The encryption key is stored in memory and lost if the program crashes.
The application doesn’t handle color images (RGB channels need separate encryption).
If the encrypted image is modified externally, decryption may fail.
Future Improvements
Support for color image encryption (handling RGB channels).
Persistent key management to avoid key loss.
Enhanced security with AES or RSA encryption.
Add drag-and-drop support for faster image selection.
License
This project is licensed under the MIT License. You are free to use, modify, and distribute the software as long as proper attribution is given.

Contact
If you encounter any issues or have suggestions, feel free to contact:

Jesmen
