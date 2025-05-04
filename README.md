✍️ Air Canvas
Air Canvas is a virtual drawing application that lets you draw on screen using just your hand gestures, captured through a webcam. It uses OpenCV and MediaPipe to track hand movements in real time.

🖼️ Features
✋ Draw on a virtual canvas with your index finger

🎨 Choose from 7 vibrant colors

🧽 Erase by switching to eraser mode

🔄 Reset the canvas with a single button

📷 Uses your webcam — no mouse, no touchscreen, just air gestures!

🛠️ Requirements
Python 3.7+

OpenCV

MediaPipe

NumPy

Install dependencies:
pip install opencv-python mediapipe numpy

🚀 How to Run
Clone or download this repository.



🎯 Controls
Action -	How to Do It
Draw	- Extend index finger only
Change Color	- Hover your fingertip over a color box
Erase-	Hover over the "Eraser" button
Reset- Canvas	Hover over the "Reset" button
Exit-	Press q key

🧠 How It Works
Uses MediaPipe Hands to detect your hand and track finger landmarks.

Tracks the index fingertip to draw lines on a virtual canvas.

UI buttons are embedded into the OpenCV window and respond to fingertip position.

Drawing is overlaid using a transparent canvas on top of the camera feed.

🖌️ Color Palette
The color options available at the top of the screen:

-Blue
-Green
-Red
-Cyan
-Magenta
-Yellow
-White

Note: Black is used internally for the eraser and not included in the palette.

📎 Notes
Works best in good lighting conditions.

For better accuracy, keep your hand clearly visible to the webcam.

The canvas background is black, so "erasing" is done by drawing black lines.
