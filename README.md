
# Line Detection and Following

This project implements a line detection and following system using ROS (Robot Operating System) and OpenCV. The system uses a camera to capture images, detects a line in the image using color-based segmentation and contour detection, and controls the robot's movement to follow the detected line.

## Prerequisites

- ROS2 (Robot Operating System)
- OpenCV
- Python 3

## Installation

1. Clone the repository into your ROS workspace:

```bash
git clone <repository_url> <workspace_dir>/src/line_detection
```

2. Colcon build in the workspace

```bash
colcon build --symlink-install
```

3. launch car_on_track.launch.py file:

```bash
ros2 launch prius_line_following car_on_track.launch.py
```

4. Run the nodes

```bash
./line_following.py
```
