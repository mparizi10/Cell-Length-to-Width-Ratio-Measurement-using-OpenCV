# Cell Length-to-Width Ratio Measurement using OpenCV

This repository contains a Python script that automates the process of measuring the length-to-width ratio of cells in microscope images. The script uses OpenCV to identify and annotate cells, measure their dimensions, and save the results in an Excel file.

## Features

- Load and preprocess high-resolution microscope images.
- Isolate and identify red lines drawn to represent cell dimensions.
- Measure the length and width of cells.
- Calculate the length-to-width ratio for each cell.
- Annotate cells with their measurements.
- Save the annotated image and measurement data to an Excel file.

## Requirements

- Python 3.x
- OpenCV
- Matplotlib
- Pandas
- NumPy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cell-length-width-ratio.git
   cd cell-length-width-ratio
