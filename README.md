# Sketch-Based-Property-Area-Calculator

## Description
This project is a **Sketch-Based Property Area Calculator** that allows users to draw a rough sketch of their property layout, detect vertices, input dimensions, and compute the area using the **Shoelace formula**. It utilizes **Tkinter** for the interactive drawing canvas, **OpenCV** for contour detection, and **Matplotlib** for visualization.

## Features
- **Interactive drawing canvas** using Tkinter.
- **Contour detection** to extract the shape of the property.
- **Vertex labeling** for better identification of dimensions.
- **Manual dimension input** to scale the sketch accurately.
- **Shoelace formula implementation** for precise area calculation.
- **Matplotlib-based visualization** for user-friendly output.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/A4xMimic/Sketch-Based-Property-Area-Calculator.git
   cd Sketch-Based-Property-Area-Calculator
   ```
2. Install dependencies:

## Dependencies
Ensure you have the following Python libraries installed:
```sh
pip install numpy opencv-python matplotlib pillow
```

## Usage
Run the script to start drawing:
```sh
python sketch_area_calculator.py
```
1. **Draw the layout** of your property using the canvas.
2. Click **"Save Sketch"** to process the drawing.
3. **Vertices will be detected**, and you will be prompted to enter dimensions between points.
4. The **scaled layout will be displayed** with the calculated area.

## Project Structure
```
├── sketch_area_calculator.py  # Main script
├── requirements.txt           # Dependencies
├── README.md                  # Project documentation
```

## Example Output
- Detected vertices labeled on the sketch.
- User-input dimensions incorporated.
- Scaled visualization with computed area displayed.



