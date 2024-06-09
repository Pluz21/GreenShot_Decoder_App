[![copyright: TVL](https://img.shields.io/badge/Copyright-TVL-yellow.svg)](https://pluz21.itch.io/)

# Instant-Screenshot-To-Text-App
# ⚠️ Only working for Windows 11 & English language⚠️

## Introduction
This repository contains an application that converts screenshots to text using Optical Character Recognition (OCR) with the Tesseract OCR engine in C#.

## Features

- Takes a screenshot of a selected area on the screen.
- Performs OCR on the captured image using the Tesseract OCR engine.
- Extracts the recognized text from the image.
- Copies the recognized text to your clipboard instantly.

## Requirements

- Screenshot tool like Snipping Tool(Windows) or Greenshot

### Optional Requirement

- Second screenshot tool like Greenshot to allow image capture with one, screenshot to text conversion with the other

## Installation

1. Clone this repository using Git: `git clone https://github.com/Pluz21/Instant-Screenshot-To-Text-App.git`
2. Launch Instant Screenshot To Text.exe

OR
1. Download GitHub repo zip
2. Extract zip
3. Launch Instant Screenshot To Text.exe

## Usage

1. If the app doesn't automatically recognize the path to the Tesseract tessdata folder, navigate to `Tesseract-OCR/tessdata` folder, copy the path, and paste it into the console.
2. The app will ask you to specify the path where your screenshots are stored (default is `%USERPROFILE%/Pictures/Screenshots`). Paste the path into the console.
3. If you want to have two screenshot tools for screen captures and image-to-text conversion, you can optionally install Greenshot.
4. Once the setup is complete, every time a screenshot is saved in the specified folder, the app will attempt to convert it to text.
5. You can directly paste the converted screenshot; no extra steps are needed.



## Acknowledgements

This project utilizes the Tesseract OCR engine for optical character recognition. Tesseract OCR is an open-source engine developed by Google and maintained by a community of contributors. 
For more information about Tesseract OCR, visit the project's official GitHub repository: [https://github.com/tesseract-ocr/tesseract](https://github.com/tesseract-ocr/tesseract)
