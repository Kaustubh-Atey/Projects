
# Object Detection and Localization using OpenCV
To detect, count and localize the moving ants in the given video.
<p align="left">
  <img src="https://github.com/Kaustubh-Atey/Projects/blob/master/Object%20Detection%20(OpenCV)/Images/Pipeline.png" width="1000" alt="accessibility text">
</p>

## STEP 1 <br>
Convert the **input RGB frames into Grayscale.**
<p align="left">
  <img src="https://github.com/Kaustubh-Atey/Projects/blob/master/Object%20Detection%20(OpenCV)/Images/Step%201.png" width="500" alt="accessibility text">
</p>

## STEP 2 <br>
**Background subtraction** on the Grayscale frame.
<p align="left">
  <img src="https://github.com/Kaustubh-Atey/Projects/blob/master/Object%20Detection%20(OpenCV)/Images/Background%20subtraction.png" width="300" alt="accessibility text">
</p>

## STEP 3 <br>
**Noise Reduction** using the Erosion technique.
<p align="left">
  <img src="https://github.com/Kaustubh-Atey/Projects/blob/master/Object%20Detection%20(OpenCV)/Images/Noise%20reduction%20-%20Erosion.png" width="300" alt="accessibility text">
</p>

## STEP 4 <br>
**Dilation.**
<p align="left">
  <img src="https://github.com/Kaustubh-Atey/Projects/blob/master/Object%20Detection%20(OpenCV)/Images/Dilation.png" width="300" alt="accessibility text">
</p>

## STEP 5 <br>
**Thresholding**.
<p align="left">
  <img src="https://github.com/Kaustubh-Atey/Projects/blob/master/Object%20Detection%20(OpenCV)/Images/Thresholding.png" width="300" alt="accessibility text">
</p>

## STEP 6 <br>
**Drawing Contours** on the threshold frame.
<p align="left">
  <img src="https://github.com/Kaustubh-Atey/Projects/blob/master/Object%20Detection%20(OpenCV)/Images/Contours.png" width="300" alt="accessibility text">
</p>

## Final Results<br>
The **moment** is the centroid of the contours. <br>
Compute and show the **position** of each ant. <br>
Calculating and Displaying the **distance of each ant from the center of the frame.** <br>
Displaying the **number of ants.** <br>

<p align="left">
  <img src="https://github.com/Kaustubh-Atey/Projects/blob/master/Object%20Detection%20(OpenCV)/Images/Final%20Result.png" width="500" alt="accessibility text">
</p>
