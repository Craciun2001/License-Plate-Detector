This project is a License Plate Detection and Recognition system developed using Python, OpenCV, and EasyOCR. It was implemented in VS Code as a practical exercise in computer vision and optical character recognition (OCR).

Key Features:

Image Preprocessing:

Resizes input images for consistent processing.

Converts images to grayscale and applies bilateral filtering to reduce noise while preserving edges.

Edge and Contour Detection:

Uses the Canny Edge Detection algorithm to identify prominent edges.

Extracts the top contours and filters them to detect potential license plate regions based on their geometric shape.

License Plate Extraction:

Creates a binary mask to isolate the detected license plate region.

Crops the plate region for further text recognition.

OCR with EasyOCR:

Performs text recognition on the cropped license plate using EasyOCR.

If no plate contour is detected, OCR is applied to the entire image as a fallback.

Visualization:

Displays intermediate results such as detected contours and final license plate localization using Matplotlib.

Annotates the detected license plate text on the image for easy visualization.
