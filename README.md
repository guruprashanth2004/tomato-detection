# Tomato Detection

This repository contains Python code for detecting tomatoes in images using OpenCV.

## Description

This project utilizes image processing techniques to identify and count tomatoes in crop images. It leverages OpenCV library for image manipulation and analysis.

## How it Works

1. **Image Loading:** The code imports the necessary libraries and loads an image of tomato crops.
2. **Color Space Conversion:** The image is converted from BGR to HSV color space for better color-based segmentation.
3. **Tomato Detection:** An HSV color range is defined to identify red tomatoes, and a mask is created to isolate them.
4. **Contour Detection:** The code finds the contours (outlines) of the detected tomatoes.
5. **Tomato Counting:** It iterates through the contours, filters out small detections, draws bounding boxes around tomatoes, and increments a counter.
6. **Result Display:** The original image and the image with detected tomatoes and bounding boxes are displayed, along with the total count.

## Usage

1. **Clone the repository:** `https://github.com/guruprashanth2004/tomato-detection.git`
2. **Install opencv library in python**
3. **Upload an image:** Use the `files.upload()` function in Google Colab to upload an image of tomato crops.
4. **Run the code:** Execute the Python script in Google Colab.

## Results

The code will output the original image and the image with detected tomatoes and bounding boxes, along with the total count of tomatoes detected.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
