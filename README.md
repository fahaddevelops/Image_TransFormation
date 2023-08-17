
# Image Transformations with OpenCV

This repository showcases various image transformation techniques implemented using the OpenCV library in Python. These techniques include translation, rotation, resizing, flipping, and cropping of images.

## Prerequisites

Make sure you have the following prerequisites installed:

- Python 3.x
- OpenCV library (`cv2`)

You can install the OpenCV library using the following command:

```bash
pip install opencv-python
```

## Usage

1. Clone this repository or download the script (`image_transformations.py`).
2. Provide an input image by placing it in the `resources` directory with the filename `girl.jpg`.
3. Run the script using a Python interpreter.

```bash
python image_transformations.py
```

4. The script will display the original image along with the transformed versions:
   - Translation
   - Rotation
   - Resizing
   - Flipping
   - Cropping

## Techniques Demonstrated

### Translation

Use the `trans` function to move an image in both the x and y directions. Positive values translate the image down and right, while negative values translate it up and left.

### Rotation

Apply rotation using the `rotate` function. Specify the angle of rotation in degrees. You can also set a custom rotation point for the image.

### Resizing

Resize an image using the `resize` function. Provide the desired dimensions and choose an interpolation method for resizing.

### Flipping

Flip an image horizontally using the `cv2.flip` function. The `flip` function takes the image and a flip code as parameters.

### Cropping

Crop an image using array slicing. Define the region of interest (ROI) by specifying the starting and ending coordinates.

## Customization

Feel free to modify the script to experiment with different transformation parameters. Adjust the values in the transformation functions to achieve the desired results.

## Acknowledgements

This script serves as a simple example of applying various image transformations using the OpenCV library.

---

Adapt and enhance this README to match your repository's structure and style. You can provide more details about each transformation technique and add additional examples if needed.
