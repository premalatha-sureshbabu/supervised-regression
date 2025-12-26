## Pixel Coordinate Prediction using Deep Learning

This assignment focuses on predicting the (x, y) coordinates of a single active pixel
with value 255 in a 50×50 grayscale image. All other pixels in the image have a value
of 0. The pixel position is randomly generated.

Since no dataset is provided, a synthetic dataset is created where each image contains
exactly one active pixel. The task is treated as a supervised regression problem, and
a Convolutional Neural Network (CNN) is used to learn the mapping between the image and
the corresponding pixel coordinates.

### Approach
- Synthetic 50×50 grayscale images are generated with one pixel set to 255.
- The model predicts the (x, y) coordinates of the active pixel.
- A simple CNN is used to extract spatial features from the image.
- Mean Squared Error (MSE) is used as the loss function.

### Results
The notebook includes:
- Training and validation loss logs
- A plot comparing ground truth and predicted coordinates
- Sample predictions to demonstrate model behavior


### Requirements
- Python 3.x
- TensorFlow
- NumPy
- Matplotlib
