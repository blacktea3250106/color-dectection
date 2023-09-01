# Color Detection

![Demo](screenshots/color-dectection.png)

## Introduction

The "color-detection" project is a Python program that analyzes images to identify and predict the closest matching colors for the prominent colors in the images. It uses a predefined color palette to make predictions based on the RGB values of the colors in the images.

## Features

- Load and display images.
- Extract HSV color features from images.
- Convert HSV colors to RGB and RGB to HEX color codes.
- Predict and display the closest matching color for each image.

## Installation

To run the "color-detection" program, follow these steps:

1. Clone the repository to your local machine:

    ```
    git clone https://github.com/your-username/color-detection.git
    ```

2. Navigate to the project directory:

    ```
    cd color-detection
    ```

3. Install the required Python packages using pip:

    ```
    pip install -r requirements.txt
    ```

## Usage

1. Add your images to the `images` directory within the project folder.

2. Open a terminal and navigate to the project directory.

3. Run the program using the following command:

    ```
    python color_detection.py
    ```

4. The program will analyze the images in the `images` directory and display the original images, their prominent color in RGB format, and the predicted closest matching color along with its HEX color code.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The predefined color palette and color matching algorithm are based on Wikipedia's color code data.
