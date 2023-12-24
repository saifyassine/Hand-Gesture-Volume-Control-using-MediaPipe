# Hand Gesture Volume Control using OpenCV and MediaPipe

This Python script utilizes the MediaPipe library to control system volume based on hand gestures detected via a camera feed. It processes the live video stream, recognizes hand landmarks, and maps specific gestures to modify the system's audio volume accordingly.

## Prerequisites

Use the requirement text file

## Usage

1. Ensure you have installed the necessary dependencies.
2. Run the Python script.
3. Use hand gestures in front of the camera to control the system volume.
4. Press 'q' to quit the video feed and end the script.

### Functionality

- The script uses the MediaPipe library to detect hand landmarks and recognize specific gestures.
- Maps recognized gestures to actions for modifying the system volume.
- Adjusts the system's audio volume based on the detected hand gestures.
- Displays the live camera feed with drawn rectangles indicating the current volume level using OpenCV.

## Notes

- Ensure proper lighting and camera visibility for accurate hand gesture recognition.
- It controls the system's volume, so it may affect the actual volume of your operating system.

## Compatibility

- This script was primarily developed for Windows systems due to its dependency on Pycaw, which is Windows-specific. But it can work for others operating systems such as Linux and macOS, by using sounddevice library.
- 
## Acknowledgments

- Utilizes the MediaPipe library for hand tracking and gesture recognition.
- Draws rectangles indicating the current volume level using OpenCV.
- Relies on Sounddevice, Pycaw, and Comtypes libraries for audio control.
