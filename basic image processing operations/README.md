# Basic Image Processing Operations

This repository contains a Python notebook that demonstrates fundamental image processing operations using the popular OpenCV library.

OpenCV offers a wealth of functions for various image manipulations. My goal is to elucidate these operations.

## Features

This repository demonstrates the following image processing operations:

- [Colour Space Conversion](notebooks/colour_space_conversion.ipynb#colour-space-conversion)
- [Image Resizing](notebooks/image_resizing.ipynb#image-resizing)
- [Image Cropping](notebooks/image_resizing.ipynb#image-cropping)
- [Image Filtering - Blurring and Sharpening](notebooks/image_filtering.ipynb#image-filtering---blurring-and-sharpening)
- [Edge Detection](notebooks/image_filtering.ipynb#edge-detection)
- [Image Rotation and Flipping](notebooks/image_transformations.ipynb#image-rotation-and-flipping)

Each operation is explained in detail within the Python notebook, complete with code examples and visual outputs.

## Requirements
- Python 3.7 or higher
- Jupyter Notebook
- Required libraries: `opencv-python`, `numpy`, `matplotlib`

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/basic-image-processing.git
    cd basic-image-processing
    ```
2. Install dependencies:
    ```bash
    # Create a new conda environment
    conda create -n image_processing_env python=3.7 -y

    # Activate the environment
    conda activate image_processing_env

    # Install dependencies
    pip install -r requirements.txt
    ```

## Usage
1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open the `image_processing.ipynb` file and run the cells to explore the operations.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [OpenCV](https://opencv.org/)
- [Pillow](https://python-pillow.org/)
- [Matplotlib](https://matplotlib.org/)


## Contributing
Contributions are welcome! To contribute to this project, follow these steps:
Feel free to contribute or raise issues!
1. Fork the repository on GitHub.
2. Clone your forked repository:
    ```bash
    git clone https://github.com/your-username/basic-image-processing.git
    ```
3. Create a new branch for your feature or bug fix:
    ```bash
    git checkout -b feature-or-bugfix-name
    ```
4. Make your changes and commit them:
    ```bash
    git add .
    git commit -m "Description of your changes"
    ```
5. Push your changes to your forked repository:
    ```bash
    git push origin feature-or-bugfix-name
    ```
6. Open a pull request on the original repository.

Please ensure your code follows the project's coding standards and includes appropriate documentation and tests.