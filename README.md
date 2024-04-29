# Car Number Plate Detection using Haar Cascade

## Overview
The Car Number Plate Detection project aims to automatically detect and extract license plates from car images using Haar Cascade classifiers. License plate recognition (LPR) systems play a crucial role in various applications, including traffic management, toll collection, and parking enforcement.

## Dataset Description
The dataset consists of car images containing license plates. Each image may have one or more license plates. The goal is to train a model that can accurately locate and recognize license plates within these images.

## Project Structure
1. `data/`: Contains the car image dataset (e.g., `car_images/` directory).
2. `notebooks/`: Jupyter notebooks for data exploration, preprocessing, and model building.
3. `models/`: Trained Haar Cascade models (e.g., `haarcascade_russian_plate_number.xml`).
4. `src/`: Python scripts for license plate detection and extraction.
5. `README.md`: This file, providing an overview of the project.

## Getting Started
1. Clone this repository to your local machine.
2. Install the required Python packages (e.g., `opencv-python`, `numpy`).
3. Explore the data using the Jupyter notebooks in the `notebooks/` directory.
4. Train a Haar Cascade classifier to detect license plates.
5. Evaluate the model's performance on test images.

## Usage
1. Load the trained Haar Cascade model (`haarcascade_russian_plate_number.xml`).
2. Preprocess car images (resize, normalize, etc.).
3. Apply the Haar Cascade classifier to detect license plates.
4. Extract the detected license plates for further processing (e.g., character recognition).

## Acknowledgments
The Haar Cascade model used in this project is based on the work by Viola and Jones. We appreciate their contributions to object detection and recognition.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
