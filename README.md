# Hand Tracking with OpenCV and Computer Vision

This project demonstrates hand tracking using OpenCV and the `cvzone` Hand Tracking Module. The system detects the position of hands in real time through a webcam, captures 21 hand landmarks, and sends the coordinates to a server using the UDP protocol for further processing.

## Features

- Hand detection with real-time tracking.
- Captures 21 landmark points on each hand.
- Sends hand data via UDP for network applications.

## Screenshots

<img width="1728" alt="Screenshot 2024-09-18 at 06 53 39" src="https://github.com/user-attachments/assets/b2112900-c7e6-453a-b2fd-c5dab1636759">


## Demo

If you've hosted a demo (optional), you can provide the link here:

- [Live Demo](https://drive.google.com/file/d/1lsiiDDB_llLfD5ZNrZKDH6EZli020Mrj/view?usp=sharing)

## Setup and Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Pahinithi/Hand-Tracking-OpenCV.git
    ```

2. **Install the required dependencies**:
    Make sure you have Python installed. Install the necessary libraries by running:
    ```bash
    pip install cvzone opencv-python
    ```

3. **Run the application**:
    ```bash
    python main.py
    ```

## Project Structure

- `main.py`: The main file for hand tracking and sending the UDP data to a server.
- Additional files such as screenshots, configuration files, etc.

## How It Works

1. The webcam captures the video frames, and the `cvzone` HandTrackingModule is used to detect hands and their 21 landmarks.
2. These landmarks are stored in a list, where each landmark contains 3D coordinates (x, y, z).
3. The coordinates of the hand landmarks are then sent to a server via UDP for further analysis or application.

## Dependencies

- Python 3.x
- OpenCV
- cvzone
- Socket



## Contributions

Feel free to contribute to this project by submitting issues or pull requests.

## License

This project is licensed under the MIT License.


## Contact

For any questions or support, please contact:

- **Name**: Pahirathan Nithilan
- **Email**: [nithilan32@gmail.com](mailto:nithilan32@gmail.com)
- **GitHub**: [Pahinithi](https://github.com/Pahinithi)

