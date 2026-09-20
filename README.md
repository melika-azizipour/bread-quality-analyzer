# Bread Quality Analyzer

A computer vision project for automated bread quality assessment using image processing and color analysis.

## Features

- Automatic bread segmentation from the background using rembg
- Burnt area detection based on CIELAB lightness values
- Color comparison with reference bread samples
- Quality evaluation using Delta E 2000 color difference
- Visualization of segmentation and burnt regions

## Supported Bread Types

- Lavash
- Taftoon
- Sangak
- Barbari

## Technologies

- Python
- OpenCV
- NumPy
- Matplotlib
- rembg
- scikit-image

## Workflow

1. Load bread image
2. Remove background
3. Extract bread mask
4. Detect burnt regions
5. Compare color with reference samples
6. Calculate Delta E 2000
7. Generate quality assessment

## Installation

```bash
pip install -r requirements.txt
