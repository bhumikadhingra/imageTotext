# imageTotext
This python code converts Image to text based on the pixel values of the image and character density.


Steps:
We are performing below actions to generate the ascii art from image.

- Provide an image path. 
- Open the image from provided path.
- Calculate the aspect ratio.
- Resize the image. Here we are taking new width as 120 pixels. Adjusting the new height as per aspect ratio.
- Convert the image into greyscale format.
- Get all the pixels of image. Replace pixles with intentsity in a defined range with a character from list.
- Print image and save to text file.

