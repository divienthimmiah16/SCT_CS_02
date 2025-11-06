# SCT_CS_02
Image Encryption Tool is a Python-based desktop application that allows users to encrypt and decrypt images using simple pixel-level transformations. Built with Tkinter for the GUI and powered by NumPy and PIL, this tool offers two methods of image manipulation
 Image Encryption Tool

A simple Python GUI application to encrypt and decrypt images using XOR and pixel swapping techniques.

 Features

- Load and process `.jpg`, `.png`, and `.bmp` images
- Choose between two encryption methods:
  - XOR: Bitwise XOR with a user-defined key
  - Swap: Structured pixel swapping
- Encrypt and decrypt with a single click
- Save processed images automatically

 Tech stack Used

- Python 3
- Tkinter (GUI)
- PIL (Pillow)
- NumPy

 Installation

1. Clone the repository:
   bash
   git clone https://github.com/yourusername/image-encryption-tool.git
   cd image-encryption-tool

2.pip install pillow numpy
3.python image_encryption_tool.py
Usage- Launch the app.
- Click Browse to select an image.
- Choose a method: xor or swap.
- If using XOR, enter a numeric key.
- Click Encrypt or Decrypt.
- The processed image will be saved in the same directory with _encrypt.png or _decrypt.png suffix.
   ExampleOriginal → XOR Encrypted → XOR Decrypted
Original → Swapped → Swapped (again to restore)
