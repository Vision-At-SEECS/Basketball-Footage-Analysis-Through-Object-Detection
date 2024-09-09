# Football-Footage-Analysis-Through-Object-Detection
Football Footage Analysis Through Object Detection

![track](https://github.com/user-attachments/assets/c2e1dd3b-8610-4b9e-8904-b5925542ac0e)

## Overview

This project performs object detection on football footage to analyze player movement, ball tracking, and game strategy. The system uses deep learning models to detect objects such as players, the ball, and field lines in football videos, extracting insights and generating key metrics.

The project is divided into the following major components:
- **Preprocessing**: Preparing football video footage for analysis.
- **Object Detection**: Detecting players, ball, and field objects in the video using pre-trained deep learning models.
- **Post-Processing**: Extracting and visualizing relevant insights from detected objects.
- **Tracking**: Tracking object trajectories across video frames.

## Features

- Player detection and tracking
- Ball tracking and event detection
- Field and line detection for positioning
- Extraction of game metrics (e.g., player distance, speed, ball possession)
- Visualization of player movement and heat maps
- Exporting data in CSV format for further analysis

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Model Information](#model-information)
- [Results and Visualization](#results-and-visualization)
- [Contributing](#contributing)
- [License](#license)

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Vision-At-SEECS/Football-Footage-Analysis-Through-Object-Detection.git
   '''

2. Navigate into the project directory:

   ```bash
   cd football-footage-analysis
   '''

3. Install the required dependencies:

  ```bash
  pip install -r requirements.txt
  '''

Dependencies include:

- opencv-python
- tensorflow
- pytorch
- numpy
- matplotlib
- pandas
- scikit-learn
