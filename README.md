# Text-extraction-from-Image
preprocesses images using techniques like grayscale conversion, noise reduction, and skew correction before using Pytesseract to extract the text. It also localizes text within the image by drawing rectangles around detected characters or words. This project showcases an OCR pipeline for extracting text from various images.

## Introduction
This project allows you to run a local application that utilizes Tesseract for optical character recognition (OCR). Follow the steps below to set it up and run it locally.

## Steps to Run the Application Locally

1. **Create a Copy of the Project**
   - Clone or download the project repository to your local machine.

2. **Open Command Prompt**
   - Change your current path to the folder where you can find the `app.py` file.

3. **Create a Conda Environment**
   ```bash
   conda create -n <environment_name>
#Activate the Environment
conda activate <environment_name>
#Install Tesseract

Download and install Tesseract using the Windows installer available at: Tesseract Installation
Note the Tesseract Path

Default installation path at the time of this edit was: C:\Program Files\Tesseract-OCR. Please check your installation path as it may change.
#Requirements
opencv-python-headless==4.2.0.32
pytesseract==0.3.7
numpy==1.19.3
Flask==1.1.1
Pillow==8.0.1


Feel free to modify any section to better fit your project needs!

