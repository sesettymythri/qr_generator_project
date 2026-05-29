# qr_generator_project
A Python project that generates QR codes from user input such as text, URLs, or data using the qrcode library.

## Features

-Generate QR codes instantly

-Save QR code as an image

-Beginner-friendly Python project

-Useful for links, text, contact info, and more

## Technologies Used
-Python

-qrcode library

-Pillow (PIL)

## Project Structure

qr_generator/

│── qr_generator.py

│── README.md

│── output.png

## Future Improvements

-Add GUI using Tkinter

-Generate colored QR codes

-Add logo inside QR code

-Create web version using Flask

## How It Works
-The user enters a text or URL.

-The program uses the qrcode library to convert the input into a QR code.

-The QR code is generated as an image.

-The image is saved in the project folder.

-The generated QR code can be scanned using any QR scanner app.

     Workflow
     User Input → Python Program → QR Code Generation → Image Saved
## Installation and Execution
1. Clone the Repository

   git clone https://github.com/sesettymythri/qr_generator_project.git

2. Navigate to the Project Folder
   cd qr_generator

3. Install Required Libraries
   pip install qrcode[pil]

4. Run the Program
   python qr_generator_project.py

5. Enter Text or URL
   Example:Enter text or URL: https://github.com

6. Output

    The program generates and saves a QR code image:

    QR Code generated successfully!

    Generated file:output.png
