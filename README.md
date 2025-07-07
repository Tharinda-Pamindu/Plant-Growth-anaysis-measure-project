# Plant Growth Monitoring System


## Introduction

This project is a comprehensive toolkit for analyzing and monitoring plant growth using computer vision techniques. It provides a suite of tools to measure various aspects of plant health and development from images, enabling users to track and quantify plant growth over time.

## About The Project

The Plant Growth Analysis and Measurement project is designed to offer an automated, non-invasive method for monitoring plant health and growth. By leveraging image processing, the system can analyze images of plants and extract key metrics such as leaf count, plant height, health status, and more. This is particularly useful for agricultural research, automated farming, and personal gardening projects where tracking plant development is crucial. The project is built with Python and utilizes popular libraries like OpenCV and Matplotlib for image processing and data visualization.

## Features

  * **Leaf Counting**: Automatically counts the number of leaves on a plant from an image to track growth stages.
  * **Health Indicator**: Analyzes the color, texture, and spots on leaves to determine the overall health of the plant.
  * **Height Measurement**: Calculates the height of the plant in an image with the help of a reference object.
  * **Image Preprocessing**: Includes utilities for noise removal and image format conversion (HEIC to JPG) to ensure high-quality analysis.
  * **Growth Analysis Over Time**: Tracks and visualizes plant growth metrics, such as leaf count and height, over a series of images.
  * **Region Analysis**: Identifies and analyzes specific regions of a plant to extract features like area, perimeter, and aspect ratio.

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This project requires Python and the following libraries:

  * OpenCV
  * NumPy
  * Matplotlib
  * scikit-image
  * Pillow
  * pillow-heif

You can install these packages using pip:

```sh
pip install opencv-python numpy matplotlib scikit-image Pillow pillow-heif
```

### Installation

1.  Clone the repo
    ```sh
    git clone https://github.com/tharinda-pamindu/plant-growth-anaysis-measure-project.git
    ```
2.  Navigate to the project directory.

## Usage

Each of the main features is available as a separate Jupyter Notebook or Python script.

  * **To count leaves**: Run the `Leaf_counter.ipynb` notebook. You will need to provide the path to the directory containing the plant images. The notebook will process the images and output the leaf count for each, along with a plot showing the growth over time.

  * **To check plant health**: Use the `Health Indicator.ipynb` notebook. This tool will analyze an image of a plant and provide a health status based on leaf color, texture, and damage.

  * **To measure plant height**: The `Height_calculator.ipynb` notebook can be used to measure the height of a plant from an image. You will need to provide a reference height in centimeters.

  * **To convert HEIC images to JPG**: Use the `heic_to_jpg_converter.ipynb` script in the `source files` directory. This is useful for preprocessing images taken on some mobile devices.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star\! Thanks again\!

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Tharinda Pamindu - [tharindapamindumudalige@gmail.com](mailto:tharindapamindumudalige@gmail.com)

Project Link: [https://github.com/tharinda-pamindu/plant-growth-anaysis-measure-project](https://www.google.com/search?q=https://github.com/tharinda-pamindu/plant-growth-anaysis-measure-project)
