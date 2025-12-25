## AI Document Scanner using OpenCV

A Python-based document scanning application that automatically detects document edges, corrects perspective, and enhances image clarity — replicating the functionality of popular mobile scanning apps like CamScanner.

## Features

Automatic edge detection using Canny and contour analysis

Perspective correction with OpenCV’s getPerspectiveTransform

Noise reduction and image enhancement using Gaussian Blur

Converts captured images into high-quality, flattened documents

Implemented entirely in Python and OpenCV

 ## Tech Stack

Python 3.x

OpenCV

NumPy

Matplotlib (for visualization)

 ## Project Workflow

Load an input image (bill.jpg or any document).

Convert to grayscale and apply Gaussian blur.

Detect edges and locate the largest quadrilateral contour.

Apply a perspective transform to extract the document region.

Display the scanned and enhanced version of the document.


