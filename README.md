# QR Code Generator

## Description
This is a simple QR code generator implemented in Python. The program allows users to generate a QR code for any text or URL and save it as an image file.

## Features
- Generates a QR code for any text or URL input.
- Allows users to specify the filename for saving the QR code.
- Uses the qrcode library to create high-quality QR codes.
- Supports customization of box size and border thickness.

## How to Use
1. Run the script in a Python environment.
2. Enter the text or URL you want to encode into the QR code.
3. Specify the filename to save the QR code image.
4. The program generates and saves the QR code as an image file.

## Requirements
- Python 3.x
- qrcode library (can be installed using pip install qrcode[pil])

## Installation
1. Download or clone this repository.
2. Ensure Python is installed on your system.
3. Install the required library using:
      pip install qrcode[pil]
   
4. Run the script using the command:
      python qrcode_generator.py
   

## Example Usage
Enter the text or URL: https://example.com
Enter the filename: my_qrcode.png
QR code saved as my_qrcode.png

## Notes
- The generated QR code will be saved in the current directory.
- The QR code can be scanned using any QR code reader.
- The default colors are black for the QR code and white for the background.

## License
This project is open-source and free to use.

## Author
Developed by Shantanu Suvarna.