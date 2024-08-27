# Python Screen Recorder

## Introduction
This project demonstrates how easy it is to build a screen recorder software using Python. Screen recorder software and applications are incredibly helpful for recording classes, taking notes on important topics, or preserving memories. This project will teach you how to use the necessary libraries, proposed modules, and references with accompanying screenshots to understand how the code works.

## Libraries
To build the screen recorder, we need the following Python libraries:

1. **Pillow** - Python Imaging Library (PIL) used for opening, manipulating, and saving images.
2. **Numpy** - A fundamental package for scientific computing with Python, used here for handling arrays.
3. **Opencv-contrib-python** - A Python binding for the OpenCV library, used here for video processing.
4. **Pywin32** - Provides access to many of the Windows APIs from Python.
5. **ImageGrab** - Part of PIL, used to capture the screen.
6. **GetSystemMetrics** - A function in the `pywin32` module that retrieves the screen resolution.
7. **DateTime** - A module for working with dates and times in Python.

## Proposed Modules
The screen recorder includes the following functionalities:

- **Current Date and Time:** The video filename is automatically generated based on the current date and time.
- **Recorded Video as .mp4 Files:** The recorded video is saved as an `.mp4` file in the specified folder.
- **Screen Resolution and Frame Rate:** The screen resolution is captured, and the frame rate is set to 20 frames per second.
- **Duration of the Video:** The video records continuously until the user stops it manually.
- **Color Format Conversion:** OpenCV uses BGR as its default color format, so the project includes conversion of BGR to RGB.

## Usage
1. Ensure you have Python installed on your system.
2. Install the required libraries using pip:
   ```bash
   pip install Pillow numpy opencv-contrib-python pywin32
