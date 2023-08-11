# Exercise-Correction-System


## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Contributing](#contributing)

## Introduction

Bicep Curl Counter is a project that uses computer vision to count bicep curl repetitions by analyzing the angles of the user's arm during the exercise. This project combines technologies such as Python, OpenCV, Mediapipe, Flask, and HTML to provide real-time tracking and counting of bicep curl movements.



## Features

- Real-time video feed from the webcam.
- Pose estimation to detect user's arm angles.
- Automatic counting of bicep curl repetitions.
- Start and stop the counter using a user-friendly web interface.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.7 or higher installed.
- A webcam or camera connected to your computer.
- Git installed (for cloning the repository).

## Installation

1. Clone this repository to your local machine:
   ```sh
   git clone https://github.com/your-username/bicep-curl-counter.git
  ## Usage
Start the Flask web application by running:

sh
Copy code
python app.py
Open your web browser and go to http://127.0.0.1:5000/ to access the user interface.

Click the "Start Bicep Curl Counter" button to begin tracking and counting your bicep curls.

When done, click the same button (now labeled "Stop Bicep Curl Counter") to stop the counting.

## How It Works
The project uses Mediapipe's pose estimation module to detect key landmarks of the user's arm during a bicep curl exercise. The angles between these landmarks are calculated to determine the position of the arm. The web interface provides an interactive way to start and stop the counter, utilizing Flask to communicate with the Python script.

Contributing
Contributions are welcome! If you want to contribute to this project, feel free to submit pull requests.

License
This project is licensed under the MIT License.

Project developed by Your Name

bash
Copy code

This template provides a structured and informative README that should help users understand your project and how to use it effectively.





