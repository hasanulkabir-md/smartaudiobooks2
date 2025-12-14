# smartaudiobooks2

## Project Overview
**smartaudiobooks2** is a Python-based application that converts text and PDF documents into audiobooks using text-to-speech technology.

## Requirements
- Python 3.x
- PyCharm (recommended IDE)

## Installation

1. **Install Python**
   Download and install Python from the official website:
   https://www.python.org/

2. **Install required libraries**
   Open the terminal (or PyCharm Terminal) and run:
   ```bash
   pip install pyttsx3
   pip install PyPDF2
````

## Usage

1. Create or open `main.py`
2. Import the required libraries:

   ```python
   import pyttsx3
   from PyPDF2 import PdfReader
   ```
3. Run the application to convert text or PDF content into speech.

## Features

* Text-to-speech conversion using **pyttsx3**
* PDF text extraction using **PyPDF2**
* Offline audiobook generation
* Simple and lightweight implementation

## Notes

* Ensure your Python environment is correctly configured in PyCharm.
* The project uses offline TTS and does not require an internet connection.

```
