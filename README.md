![Screenshot (74)](https://github.com/user-attachments/assets/8217fa8e-30b9-40cf-bfb8-87c3ceb1a20e)

# Face Detector with Python

This project demonstrates a simple face detection application built using Python. The application uses computer vision techniques to detect faces in real-time from a video feed.

## Features

- Real-time face detection
- Press `0` to terminate the program manually
- Automatic shutdown if no face is detected within 10 seconds

## Installation

To get started, you'll need to have Python installed on your machine. You will also need to install a few dependencies. You can do this by running:

```bash
pip install opencv-python
```

## Usage

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/Mansiiiiiiiiiiiiiiiii/Face-detector.git
    ```

2. Navigate to the project directory:

    ```bash
    cd face-detector
    ```

3. Run the face detection script:

    ```bash
    python face_detector.py
    ```

4. The script will start capturing video from your webcam. It will display a window showing the live feed with detected faces highlighted.

## Code Explanation

- **Face Detection**: The script uses OpenCV's pre-trained Haar cascade classifier for detecting faces.
- **Real-time Processing**: The video feed is processed frame-by-frame to detect faces in real-time.
- **Termination**: The program listens for the `0` key to end the execution and automatically terminates if no faces are detected within 10 seconds.

## Requirements

- Python 3.x
- OpenCV (`opencv-python`)

## Contributing

If you would like to contribute to this project, please fork the repository and create a pull request with your proposed changes. Make sure to follow the existing code style and write clear commit messages.

## Contact

If you have any questions or suggestions, feel free to reach out to me at [mansi15094@gmail.com](mailto:mansi15094@gmail.com).

---

Happy coding! 🚀
