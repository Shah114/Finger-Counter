## Finger-Counter
This project is a Finger Counter built using OpenCV and a Hand Tracking Module inspired by Murtaza's YouTube Channel. The model detects a hand in the frame and counts the number of fingers being held up, displaying the count in real time. <br/>
<br/>

## Features
* Real-Time Finger Counting: Detects and counts the number of fingers raised in the camera feed.
* Hand Detection: Utilizes a Hand Tracking Module to efficiently detect hands in the frame.
* OpenCV Integration: Uses OpenCV for image processing and video capture. <br/>
<br/>

## Usage
1. Ensure your webcam is connected or use a video file.
2. Run the finger_counter.py script to start the application.
3. The program will display the video feed with the finger count overlayed on the screen. <br/>
<br/>

## How It Works
The Finger Counter uses a Hand Tracking Module based on MediaPipe, which is inspired by Murtaza's tutorial. The steps involved include: <br/>
* Hand Detection: The module detects the hand landmarks in the video frame.
* Finger Identification: Based on the positions of the detected landmarks, the script identifies which fingers are open.
* Counting: The number of open fingers is counted and displayed on the screen <br/>
<br/>

## Acknowledgements
This project was inspired by Murtaza’s tutorial on hand tracking, available on his YouTube channel. <br/>
* https://youtu.be/p5Z_GGRCI5s?si=kY08mdNKthfY8ioE
* https://youtu.be/NZde8Xt78Iw?si=5hNuebMVbjFL4fHm <br/>
<br/>

## Contributing
Contributions are welcome! Please open an issue or submit a pull request.
