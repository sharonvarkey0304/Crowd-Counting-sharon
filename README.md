# Crowd-Counting using Python

This project is a Python-based application designed to automatically detect and count the number of people in static photographs. It utilizes computer vision techniques to provide accurate population estimates for high-density images.

## Project Overview
The primary goal of this tool is to automate crowd analysis, which is essential for urban planning, event security, and public health monitoring. By processing an input image, the system identifies individual human figures and outputs a total numerical count.



## Key Features
* **Automated People Counting:** Rapidly identifies individuals in photos without manual input.
* **Image Preprocessing:** Includes custom filters to improve detection accuracy in low-light or low-resolution images.
* **Visualization:** Generates an output image where each detected person is highlighted with a bounding box or point.
* **Accuracy Reporting:** Provides a final numerical count and a confidence score for the analysis.

## Project Structure
* `main.py`: The entry point for the application to handle image input and display results.
* `detector.py`: Contains the core logic for the counting algorithm.
* `utils/`: Helper scripts for image scaling and data cleaning.
* `requirements.txt`: Lists all necessary Python libraries.
