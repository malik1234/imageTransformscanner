this is a simple document scanner project which I intend to use for another application that allows you to scan your lecture whiteboards and turn them into top down views. It converts the selected image to greyscale then utilises Gaussian blurring for cleaning , then Canny edge detection.

the document scanner works on the assumption that you're using recatangular whiteboards and documents, as it takes the largest contour image with precisely 4 points as your scannable object.

I then take the 4 outline points and apply perspective transformation for the scan type image.