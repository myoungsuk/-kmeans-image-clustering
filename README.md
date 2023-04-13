#  K-Means Image Compression and Color Palette Extraction

This repository contains a Python script that demonstrates the application of the K-Means clustering algorithm to image compression and color palette extraction.

Overview
The K-Means clustering algorithm is an unsupervised learning technique used to partition data points into K distinct groups based on their similarity. In this project, we apply the K-Means algorithm to compress an image by reducing the number of unique colors while preserving its visual quality. Additionally, the algorithm is employed to extract a representative color palette from the image.

Dependencies
To run the script, you will need the following Python libraries:

NumPy
OpenCV
Matplotlib
scikit-image
scikit-learn
SciPy
seaborn
You can install these libraries using pip:

arduino
Copy code
pip install numpy opencv-python matplotlib scikit-image scikit-learn scipy seaborn
Usage
Clone this repository and navigate to the project directory.

Place the image you want to process in the project directory and replace the image_path variable in the script with the path to your image.

python
Copy code
image_path = "/path/to/your/image.jpg"
Run the script:
Copy code
python kmeans_image_compression.py
The script will display the original image, a histogram of cluster label distribution, the compressed image with reduced colors, the masked image for a specific cluster, and the extracted color palette.

You can adjust the number of clusters (colors) in the n_clusters variable to see how it affects the compressed image and color palette.

python
Copy code
n_clusters = 5
License
This project is licensed under the MIT License. See the LICENSE file for details.
