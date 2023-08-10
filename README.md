# Air Canvas A-Virtual Pen Application

This project is an interactive paint application that allows you to draw on a canvas using hand gestures captured by your webcam. The application utilizes the Mediapipe library for hand tracking and OpenCV for image processing, providing an engaging and creative way to produce colorful artwork.

## Key Features

- Real-time hand tracking using the powerful Mediapipe library.
- Four distinct brush colors: blue, green, red, and yellow.
- Adjustable brush size via a user-friendly trackbar interface.
- Convenient "Clear" button to reset the canvas and start anew.
- Clearly marked color selection buttons on the screen.
- Dynamic line rendering that corresponds to your hand movements.

## Installation and Setup

Follow these straightforward steps to set up and run the project:

1. **Install Python**: If you haven't already, download and install Python from the [official Python website](https://www.python.org/downloads/).

2. **Install Required Libraries**: Open a terminal or command prompt and execute the following commands to install the necessary libraries:

   ```bash
   pip install opencv-python
   pip install numpy
   pip install mediapipe
    ```
   
3. **Download the Project**: Download the project code and save it to a directory of your choice.

4. **Run the Application**: Navigate to the project directory in your terminal or command prompt, and run the application using the command:
```bash
 python aircanvas.py
```
# How to Use

1. Running the application activates your webcam, and you'll see two windows: "Output" and "Paint."

2. Position your hand in front of the webcam for detection.

3. Use your index finger to control the brush. Move your finger to create drawings on the canvas.

4. Adjust the brush size by manipulating the trackbar within the "Output" window.

5. Select a brush color by touching the corresponding color area:
- Blue: Interact with the blue rectangle.
- Green: Interact with the green rectangle.
- Red: Interact with the red rectangle.
- Yellow: Interact with the yellow rectangle.

6. Clear the canvas by touching the "CLEAR" area.

7. Press the 'q' key to exit the application.

# Tips for Optimal Use

- Ensure Adequate Lighting: Good lighting enhances hand tracking accuracy.
- Smooth Hand Movements: Maintain steady and smooth hand movements for better drawing results.
- Explore and Experiment: Try different brush sizes and colors to unleash your creativity.

# Contributing

Contributions to this project are welcome! Feel free to submit pull requests for bug fixes or new features.
