# Invisibility-cloak
## Harry Potter’s Invisibility Cloak using OpenCV Python.

## Description: 
Python program to create a invisibility cloak using image processing techniques such as saturation and segmentation with the help of opencv library. 

## How it works:
This technique is opposite to the Green Screening. In green screening, we remove background but here we will remove the foreground frame.
Capture and store the background frame
Detect the defined color using color detection and segmentation algorithm.
Segment out the defined colored part by generating a mask.
Generate the final augmented output to create a magical effect. [output.avi]

## Instruction to run code:
Python must be installed in system.
download and run the program using terminal, 
then webcam will open first frame will be captured as background and then you can show red colored things and it will create a mask over it to give invisibilty cloak effect. 
