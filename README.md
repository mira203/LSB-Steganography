# LSB-Steganography

This project implements Image Steganography in Python using OpenCV and NumPy. It allows encoding secret text messages inside images and decoding them back using Least Significant Bit (LSB) substitution.

# Features

Encode secret text inside an image.

Decode and retrieve hidden messages.

Uses LSB technique for steganography.

Supports any image format (JPG, PNG, etc.).

Simple command-line interface with options for encoding/decoding.

# How It Works

User selects an image to encode a message.

The text message is converted to binary and hidden in the least significant bits of image pixels.

Encoded image is saved with hidden data.

To decode, the program extracts binary data from the modified pixels and reconstructs the original message.

# Example Run

Image Steganography 
 1. Encode the data 
 2. Decode the data 
 Your input is: 1

Encoding...
Enter image name (with extension): sample.png
Enter data to be encoded: hello world
Enter the name of new encoded image (with extension): secret.png


Image Steganography 
 1. Encode the data 
 2. Decode the data 
 Your input is: 2

Decoding...
Enter hidden image name (with extension): secret.png
Decoded message is hello world

# Files

steganography.py → Main Python program

README.md → Documentation 
