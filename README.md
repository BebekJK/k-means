# Using K-Means: Building an Image Compressor

This project focuses on compressing images consisting of thousands of colors into an image with a reduced color palette. The goal is to create a compressed image while maintaining visual quality by representing the original image with only N number of colors.

## Features

- Image compression using the K-Means algorithm
- Downsizing the original image to 224 x 224 pixels for faster training process
- Customizable image size by modifying the IMG_SIZE variable

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/BebekJK/k-means.git
2. Navigate the project directory:

   ```bash
   cd k-means
3. Install the required dependencies

## Usage

1. Specify the size of the compressed image. The default is 224.
2. Specify the path to the original image. The default is set in the 'images/original' folder (and saved into 'images/compressed' folder). Only .jpeg or .jpg image extensions are accepted
3. Specify the number of colors that you want your compressed image to have. The default is 10.
4. Specify the number of iterations that you want your model to run. The default is 10.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please feel free to submit bug reports or pull requests. See the CONTRIBUTING.md file for more details.

## Credits

This project is inspired by the teachings of DeepLearning.AI. Special thanks to their educational resources for providing guidance and inspiration.

## Demo
<p>Original Image: </p>
<img src="./images/original/image_1.jpeg" alt="Image Description" width="300" height="300">

<p>Compressed Image: </p>
<img src="./images/compressed/image_1.jpeg" alt="Image Description" width="300" height="300">
