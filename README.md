# Bangla HandWritten Character Recognition


![image](https://github.com/SumontaNandy/BanglaHandWrittenCharRecognition/assets/71792339/d2aecce2-0e9f-4e72-86fb-c0efd8117163)

A machine learning project focused on recognizing Bangla handwritten characters within form fields. The project involves two key components: box detection and character recognition.

## Overview

The project aims to automate the extraction of information from handwritten Bangla character images found in forms. It leverages machine learning techniques to first detect the bounding boxes around individual characters using a box detection model. Subsequently, a character recognition model interprets and classifies the characters within these detected boxes.

## Features

- **Box Detection Model:** Implemented a model to accurately identify and locate the bounding boxes around handwritten characters in the input images.

- **Character Recognition Model:** Developed a character recognition model capable of classifying Bangla characters within the detected boxes.

- **Preprocessing Techniques:** Applied various preprocessing techniques to enhance the quality and interpretability of input character images.

## Usage

1. **Input Image:**
   - Provide the Bangla handwritten character image from the form field as input.

2. **Box Detection:**
   - The box detection model identifies and outlines the individual character regions within the image.

3. **Character Recognition:**
   - The character recognition model processes each detected box, recognizing and classifying the Bangla characters.

4. **Output:**
   - Obtain the recognized characters and their corresponding locations as the output.

## Project Structure

- **`box_detection_model/`:** Contains code and resources related to the box detection model.
- **`character_recognition_model/`:** Includes code and resources for the character recognition model.

## Getting Started

1. Clone the repository:
   ```bash
   https://github.com/SumontaNandy/BanglaHandWrittenCharRecognition.git



