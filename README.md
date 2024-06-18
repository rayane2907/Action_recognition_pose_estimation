# Action Recognition from Pose Estimation

This project focuses on recognizing human actions using pose estimation techniques. The goal is to analyze human poses from video or image inputs and classify the actions being performed.
The Whole code attached in the section of **"Joint_2D_and3D_Pose_Estimation_and_Action_Recognition.ipynb"**

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)

## Introduction
Pose estimation is a computer vision technique that detects human joints and maps them to a human skeleton model. This project leverages pose estimation to recognize and classify human actions. It is useful in various applications, such as sports analytics, human-computer interaction, and video surveillance.

## Features
- Detect human poses from images or videos.
- Classify actions based on detected poses.
- Pre-trained models for pose estimation.
- Easy to extend for custom action recognition tasks.

## Installation
To get started with this project, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/action-recognition-pose-estimation.git
    cd action-recognition-pose-estimation
    ```

2. **Create a virtual environment and activate it:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To use the action recognition system, follow these steps:

1. **Prepare your input data:**
    - Ensure your images or videos are in the correct format and placed in the appropriate directories.

2. **Run pose estimation:**
    ```bash
    python pose_estimation.py --input path_to_your_input --output path_to_output
    ```

3. **Run action recognition:**
    ```bash
    python action_recognition.py --input path_to_pose_data --output path_to_action_results
    ```

## Examples
Here are some example commands and their expected outputs:

1. **Pose Estimation Example:**
    ```bash
    python pose_estimation.py --input sample_video.mp4 --output poses.json
    ```
    This will generate a JSON file containing the detected poses for each frame in the video.

2. **Action Recognition Example:**
    ```bash
    python action_recognition.py --input poses.json --output actions.json
    ```
    This will generate a JSON file containing the classified actions based on the detected poses.

## Contributing
Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.
