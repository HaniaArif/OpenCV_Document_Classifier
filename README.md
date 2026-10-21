# Document_Color_Classifier
This project had been developed for TCPC Japan. The goal of this project is to classify colored documents to mono color, rich black, colored and special color. This utility has enabled the company to save more than 80% of the ink that was wasted especially if a rich black document was sent to a color printer instead of a black ink printer. 

An accuracy of 100% was achieved using Python, OpenCV, Camelot, PyPDF2 and Ghostscript on a Linux OS.

## Workflow:
### Main workflow:
PDF ingestion → image processing → classification
### Subflow (Image processing): 
Crop-mark removal → color-channel extraction → CMYK channel separation → Channel conversion to numpy → **Classification** 

## Dataset:
The current folder contains only a few sample files in the folder called `full_color` as the actual files are under NDA.

## Required Libraries:
      PyPDF2
      pdf2image
      poppler-utils
      ghostscript
      camelot-py[cv]
      excalibur-py
      ghostscript python3-tk
      opencv-python
      numpy

**Note:** Dependencies had been added in the jupyter notebook for easy run.
     
