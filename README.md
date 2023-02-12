# Image Editor using PySimpleGUI and PIL
This code demonstrates the use of PySimpleGUI and PIL library to create a simple image editor. The user can open an image and apply different filters like blur, contrast, emboss, contour, flip x and flip y to the image. The user can also save the edited image.

## Dependencies
- PySimpleGUI
- PIL
- io

## Features
- Open an image
- Apply filters like blur, contrast, emboss, contour, flip x and flip y
- Save the edited image
- How to use
- Clone the repository
- Install the dependencies
- Run the code in the terminal or IDE
- Click on the "Open" button to select an image
- Apply filters using the sliders, checkboxes and buttons
- Click on the "Save Image" button to save the edited image

## Code explanation
The code starts by importing the required libraries. The updateIMG function takes the original image, blur, contrast, emboss, contour, flipx and flipy as parameters and updates the image using the PIL library. The controlCOL contains the sliders, checkboxes and buttons for applying filters to the image. The imageCOL contains the image to be edited. The layout is a combination of the controlCOL and imageCOL. The original image is opened using the Image.open function from the PIL library. The PySimpleGUI window is created with the specified layout. In the while loop, the window is read and updated continuously. The updateIMG function is called whenever the values of the sliders or checkboxes are changed. If the user clicks on the "Save Image" button, the user can save the edited image by providing the save path. The window is closed when the user closes the window.
