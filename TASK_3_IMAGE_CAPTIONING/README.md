# Image Captioning

## Description

This project is an Image Captioning System developed as part of the CodSoft Artificial Intelligence Internship.

The system uses a pre-trained MobileNetV2 deep learning model to analyze an image, identify the main object present, and automatically generate a descriptive caption for the image.

## Features

* Upload an image for analysis
* Detects the main object in the image
* Generates an automatic caption
* Displays the image with the generated caption
* Uses a pre-trained deep learning model

## Technologies Used

* Python
* TensorFlow
* MobileNetV2
* NumPy
* Matplotlib
* Pillow

## How It Works

1. The user uploads an image.
2. The image is preprocessed and resized.
3. MobileNetV2 predicts the main object in the image.
4. The predicted label is converted into a readable caption.
5. The image and generated caption are displayed.

## Sample Output

Input Image:
Cat Image

Generated Caption:
This image contains a tiger cat.

## Project Structure

TASK_3_IMAGE_CAPTIONING

* image_captioning.ipynb
* README.md
* requirements.txt
* sample_image.jpg
* output.png

## Future Improvements

* Use advanced models such as BLIP or Transformers
* Generate complete natural language sentences
* Support multiple objects in a single image
* Improve caption accuracy

## Author

V. Venkata Nagendra

CodSoft Artificial Intelligence Internship
