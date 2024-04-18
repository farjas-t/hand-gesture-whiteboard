# Hand Gesture Controlled Whiteboard

This project allows you to control a virtual whiteboard using hand gestures. It utilizes the MediaPipe library for hand tracking and OpenCV for image processing.

## Features

- **Draw Freely:** You can draw using your ☝ and cut the drawing line using ✌.
- **Switch Tools:** Raise your ✌ index and middle finger together and hover to the pen icons to choose pen color.
- **Record Drawing Sessions:** Capture your artistic process by hovering ✌ to the record icon.

## Requirements

- Python 3.6 or higher
- OpenCV
- MediaPipe

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/farjas-t/hand-gesture-whiteboard.git
   ```

2. Navigate to the project directory:

   ```bash
   cd hand-gesture-whiteboard
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the `hand_write.py` script:

   ```bash
   python hand_write.py
   ```

2. Use your index finger ☝ to draw on the whiteboard.
3. Use your ✌ fingers to cut the drawing.
4. Switch between colors and tools using ✌.
5. Press 'Q' to quit the application.

## Recording

- The application allows you to record your drawing sessions.
- Recorded videos are saved in the `recordings` directory.

## Contributing

If you would like to contribute to the project, feel free to fork the repository and submit a pull request. We welcome any improvements or additional features.

## License

This project is licensed under the [MIT License](LICENSE).
