# Fourier Transform Mixer

## Description
**Fourier Transform Mixer** is a desktop program designed to illustrate the relative importance of magnitude and phase components in a 2D signal, specifically images. The program allows users to open and view grayscale images, customize Fourier Transform components, mix images with adjustable weights, and more.

## GUI
![Screenshot (393)](https://github.com/RanaHany10/Signal_Blend_Pro/assets/115092108/6409449d-37ee-4b9e-9ff0-615f1c6642aa)

## Key Features

### Image Viewers

- Open and view up to four grayscale images.
- Convert colored images to grayscale.
- Unified sizing for opened images.
- Display FT components: Magnitude, Phase, Real, Imaginary.

### Output Viewports

- Two output viewports identical to input image viewports.
- Switch between viewports to view the mixer result.

### Brightness/Contrast Adjustment

- Adjust image brightness/contrast with mouse dragging.
- Applicable to all four FT components.

### Component Mixer

- Customize weights of each image's FT components using sliders.
- Calculate mixer result using weighted average of FTs.

### Regions Mixer

- Draw rectangles on each FT to select inner or outer regions.
- Customize region size or percentage with sliders.
- Unified region selection for all four images.

### Realtime Mixing

- Display progress bar during ifft operations.
- Thread handling for lengthy operations.
- Cancel previous operation if a new request is made.

https://github.com/RanaHany10/Signal_Blend_Pro/assets/115092108/bedecb42-b93c-4f5d-a8f7-4c09e1aa23c5

## Getting Started
To run the application, make sure you have Python and the required libraries (including PyQt and any additional libraries) installed. 
### Libraries

- **scipy.fft**
- **scipy.signal**
- **numpy**
- **pandas**
- **os**
- **scipy.interpolate**
- **pyqtgraph**
- **matplotlib.figure**
- **PyQt5.QtWidgets**
- **matplotlib.backends.backend_qt5agg**
- **sys**

Execute the main Python script to launch the application.

Doing this by:

1. Install python any version

2. In the cmd write the following commands to satisfy the compile requirment:
   - install pyqt by the command "pip install pqyt5"
   - install numpy by the command "pip install numpy"
   - install pyqt graph by the command "pip install pyqtgraph"

3. Put the files index.py and main.ui in same location that containg the downloaded python package

4. To determine the location write this command in the cmd "pip show pyqt5"

5. Open the index.py by any ide with python interpreter and run the code

## Team Members
* Rana Hany Mahmoud Tawfiq
* Sarah Ibrahim Abdelfattah
* Basmala Tarek Mohamed
