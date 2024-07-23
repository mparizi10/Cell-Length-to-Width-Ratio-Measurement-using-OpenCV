Loading and Processing the Image:
                        Load the image using OpenCV.
                        Convert the image to grayscale.
                        Create a mask to detect red lines.
                        Find contours in the mask.
                        
Annotating the Image:
                        Loop through the detected contours.
                        Calculate the bounding box for each contour.
                        Measure the length and width.
                        Annotate the image with circles and text.

Saving and Displaying the Annotated Image:
                        Save the annotated image to a specified path.
                        Display the annotated image using matplotlib.

Saving the Measurements:
                        Save the cell measurements to an Excel file.
                        Display the DataFrame containing the measurements.
