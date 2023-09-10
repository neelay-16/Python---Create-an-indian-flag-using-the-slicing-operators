# Python---Create-an-indian-flag-using-the-slicing-operators
This Python script generates an image of the Indian flag using the Python Imaging Library (PIL). The flag consists of three horizontal stripes of different colors and the Ashoka Chakra at the center.

# Prerequisites

Make sure you have the PIL library installed in your Python environment. You can install it using pip.

# Preview

https://github.com/neelay-16/Python---Create-an-indian-flag-using-the-slicing-operators/assets/135517502/7b003066-96d9-4155-bd35-6fc8ff0a9de4


# Description

I am making use of two modules of PIL library. 'Image' for working with images and 'ImageDraw' for drawing shapes on images.

![image](https://github.com/neelay-16/Python---Create-an-indian-flag-using-the-slicing-operators/assets/135517502/2d80f972-e192-46bd-9e91-c7de585f23a0)

By setting the width and height of the image here, we define the dimensions of the image as 100 pixels in width and 100 pixels in height.

![image](https://github.com/neelay-16/Python---Create-an-indian-flag-using-the-slicing-operators/assets/13557502/6d3be7e7-11f0-4764-a3b5-7f43961cca7e)


This line creates a new blank image with an RGB color mode. It specifies the image size as 100x100 pixels and fills it with a white background (255, 255, 255 represents white in RGB)

![image](https://github.com/neelay-16/Python---Create-an-indian-flag-using-the-slicing-operators/assets/135517502/6bb30f08-1824-4927-949e-f208aee3db0f)


This line creates a drawing context for the image, allowing you to draw various shapes and text on it

![image](https://github.com/neelay-16/Python---Create-an-indian-flag-using-the-slicing-operators/assets/135517502/b5436d76-dad9-4b87-bece-bb4b07d8ff60)


Here, we calculate the height of the saffron stripe, which is one-third of the total height of the image

![image](https://github.com/neelay-16/Python---Create-an-indian-flag-using-the-slicing-operators/assets/135517502/8a2d8118-3276-4125-8b36-486065162886)


This line draws a rectangle at the top of the image, representing the saffron stripe. The fill parameter specifies the RGB color for the saffron color (255, 153, 51).

![image](https://github.com/neelay-16/Python---Create-an-indian-flag-using-the-slicing-operators/assets/135517502/5930281b-c3d6-4528-885e-dcd5d2d71b8e)


This line draws a white rectangle just below the saffron stripe, representing the white stripe in the flag

![image](https://github.com/neelay-16/Python---Create-an-indian-flag-using-the-slicing-operators/assets/135517502/a5b90621-70b8-464d-a1f6-e0ecd41dd8f9)


This line draws a green rectangle at the bottom of the image, representing the green stripe in the flag.

![image](https://github.com/neelay-16/Python---Create-an-indian-flag-using-the-slicing-operators/assets/135517502/8c10dd74-8ecc-48a0-b186-9ef6e554f937)


These lines draw the Ashoka Chakra (Wheel) at the center of the saffron stripe. It calculates the radius and center position for the chakra and then draws an ellipse filled with the specified color (0, 56, 168 represents the blue color of the chakra).

![image](https://github.com/neelay-16/Python---Create-an-indian-flag-using-the-slicing-operators/assets/135517502/002f65ab-9f51-401a-996c-d8656dd01d92)




Feel free to modify the code and customize the flag's appearance as needed.






















