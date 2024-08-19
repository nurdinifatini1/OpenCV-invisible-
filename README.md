# OpenCV-invisible-

# Invisible Cloak using OpenCV

This project creates an "Invisible Cloak" effect using OpenCV and your webcam. The effect makes a specific color (green in this case) appear transparent by replacing it with a pre-captured background image. This creates the illusion that the object of that color is invisible.

## How It Works

The script works by:
1. Capturing a static background image without any foreground objects.
2. Detecting the specified color (green) in each frame captured by the webcam.
3. Creating a mask that identifies the pixels corresponding to the specified color.
4. Replacing the masked pixels with the corresponding pixels from the static background image, making the object of that color appear invisible.

## Prerequisites

Make sure you have the following installed:
- Python 3.x
- OpenCV (`cv2`)
- NumPy (`numpy`)


