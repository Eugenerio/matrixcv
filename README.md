# matrixcv
This code is a matrix simulation using Pygame. It creates a matrix of random letters, with columns shifting and characters changing at random intervals. The matrix is drawn over a live video feed from the user's webcam.

# To use this code, you will need to have the following libraries installed:

* Numpy
* Pygame
# To run the simulation, simply run the Matrix class, passing in an instance of the app class. The app class should have the following attributes:

* **HEIGHT**: the height of the matrix in pixels
* **WIDTH**: the width of the matrix in pixels
* **RES**: the resolution of the video feed, as a tuple of (width, height)
* **cam**: an instance of the Pygame camera module, initialized with the user's webcam.
* The Matrix class takes an optional argument, **font_size**, which determines the size of the letters in the matrix. The default value is 7.

# The Matrix class has the following methods:

* **get_frame()**: returns a pixel array of the current video frame
* **get_image(path_to_file)**: returns a pixel array of the image at the specified file path
* **get_prerendered_chars()**: returns a dictionary of prerendered characters in different colors
* **run()**: updates the matrix and draws it over the video feed
* **shift_column(frames)**: shifts the specified columns of the matrix
* **change_chars(frames)**: changes the characters in the matrix at random intervals
* **draw()**: draws the matrix over the video feed.
