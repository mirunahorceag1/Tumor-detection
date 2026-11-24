# Tumor-detection
Academic Python project comparing contrast enhancement, thresholding, and morphological operations for segmenting lung tumor regions in medical images.
# Lung Tumor Image Analysis

This academic project explores how classical image processing techniques affect the visibility and segmentation of lung tumor regions in selected medical images.

## Methods

- Compared power-law, exponential, and logarithmic intensity transformations for contrast enhancement.
- Converted RGB images to grayscale and applied intensity thresholding to generate segmentation masks.
- Tested morphological opening and closing with six structuring elements to compare their effect on the masks.
- Visualized original and processed images side by side using Matplotlib.

## Findings

In the examples discussed in the report, the exponential transformation made the tumor region more distinct. Thresholding followed by morphological opening produced clearer contours in selected examples.

## Technologies

Python, NumPy, SciPy, and Matplotlib.

## Project files

- [Python script](Detectare%20tumori-cod.py)
- [Full project report (PDF, in Romanian)](1435a_Detectarea%20tumorilor.pdf)
