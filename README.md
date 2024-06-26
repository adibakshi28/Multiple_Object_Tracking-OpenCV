# Multiple Object Tracking with OpenCV py
## Overview

This repository contains an implementation of multiple object tracking using OpenCV. The project includes several demo videos to showcase the tracking capabilities on various types of footage.

## Report

For a detailed report of the project refer to this report [Report](Final%20Report.pdf)

## Visuals

### Video Demonstrations

Below are links to the demo videos of the project:

- [Final Algos Comparison](https://github.com/adibakshi28/Multiple_Object_Tracking-OpenCV/raw/main/Demo/Final.mp4)
- [Los Angeles](https://github.com/adibakshi28/Multiple_Object_Tracking-OpenCV/raw/main/Demo/los_angeles.mp4)
- [Nascar](https://github.com/adibakshi28/Multiple_Object_Tracking-OpenCV/raw/main/Demo/nascar.mp4)
- [Soccer_01](https://github.com/adibakshi28/Multiple_Object_Tracking-OpenCV/raw/main/Demo/soccer_01.mp4)
- [Soccer_02](https://github.com/adibakshi28/Multiple_Object_Tracking-OpenCV/raw/main/Demo/soccer_02.mp4)

## Features

- **Multiple Object Tracking:** Uses OpenCV to track multiple objects in video sequences.
- **Demo Videos:** Includes several sample videos demonstrating the tracking algorithm.

## Prerequisites

- Python 3.x
- OpenCV
- Numpy

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/adibakshi28/Multiple_Object_Tracking-OpenCV.git
    ```

2. Navigate to the project directory:

    ```sh
    cd Multiple_Object_Tracking-OpenCV
    ```

3. Install the required dependencies:

    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Run the tracking script:

    ```sh
    python track_objects.py --video path_to_your_video_file
    ```

    Replace `path_to_your_video_file` with the path to the video you want to use for tracking.

## Demo Videos

- The Demo folder contains several sample videos. You can test the tracking algorithm using these videos.
- Example:

    ```sh
    python track_objects.py --video Demo/Final.mp4
    ```

## Code Structure

### track_objects.py

- **Object Detection:** Uses pre-trained models to detect objects in each frame.
- **Tracking:** Implements tracking algorithms to follow detected objects across frames.
- **Visualization:** Draws bounding boxes and labels on tracked objects for visualization.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push the branch and create a pull request.

## Contact

For any questions or feedback, please open an issue in the repository.

Enjoy using Multiple Object Tracking with OpenCV!

