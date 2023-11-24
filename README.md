# Table-detection-and-text-extraction

STEP - 1 - This step involves converting the input image to gray level and apply canny edge detector on it.
STEP - 2 - Morphological operations are performed on the image obtained from Step 1.
STEP - 3 - The next step is to detect all the lines present in the image.
STEP - 4 - This step involves separating the horizontal and vertical lines from the lines obtained in Step 3.
            (There may be some overlapping lines or same lines which are very close by.)
STEP - 5 - This step involves drawing the detected horizontal and vertical lines in an blank image.
STEP - 6 - This step involves detecting the contours, i,e,cells in a table.
STEP - 7 - Plotting the results.
<img width="929" alt="Screenshot 2023-11-25 at 12 27 10 AM" src="https://github.com/ndvHareesh/Table-Detection-and-Text-Extraction/assets/89001360/86e62ea1-a565-4cb6-8122-4176892efa1b">
