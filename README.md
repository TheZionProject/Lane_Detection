# Lane Detection Model for Self-Driving Cars

## Overview
This Jupyter Notebook implements a computer vision-based lane detection system for self-driving cars using OpenCV (cv2). The notebook contains step-by-step implementation and visualization of lane detection algorithms, making it ideal for both learning and implementation purposes.

## Features
- Interactive lane detection pipeline with visualizations
- Step-by-step explanation of the algorithm
- Real-time parameter tuning
- Detailed markdown explanations with theory
- Visual output at each processing stage

## Prerequisites
- Python 3.7+
- Jupyter Notebook/JupyterLab
- Required Python packages:
```bash
pip install jupyter opencv-python numpy matplotlib ipywidgets
```

## Installation
1. Clone the repository
```bash
git clone https://github.com/TanmayS707/Lane-Detection.git
cd lane-detection
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook
```bash
jupyter notebook
```

4. Open `lane_detection.ipynb` in your browser



## Usage
Run all cells in sequential order



## Key Parameters
Adjust these variables in the parameter cell:
```python
# Image preprocessing
CANNY_LOW_THRESHOLD = 50
CANNY_HIGH_THRESHOLD = 150

# Hough transform
rho=2,
theta=np.pi/180,
threshold=100,
min_line_len=40,
max_line_gap=5
```

## Troubleshooting Common Issues
1. **Kernel Crashes**
   - Restart kernel and run all cells
   - Check memory usage
   - Clear output of heavy computation cells


2. **Widget Issues**
   - Restart kernel
   - Reinstall ipywidgets: `pip install --upgrade ipywidgets`


## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgments
- OpenCV community
- Jupyter development team
- Test dataset providers

## Contact
Your Name - tanmays707@gmail.com
Project Link: https://github.com/TanmayS707/Lane-Detection
