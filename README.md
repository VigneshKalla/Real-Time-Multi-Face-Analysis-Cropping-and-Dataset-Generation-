# Real-Time-Multi-Face-Analysis-Cropping-and-Dataset-Generation-


⚙️ Requirements
To run this script, you will need Python 3 and the following libraries
- opencv-python
- mediapipe 
- yt-dlp

This Python script offers a robust, real-time computer vision solution for detecting, visualizing, tracking, and saving multi-face data from live video streams. It uses OpenCV and Google's MediaPipe Face Mesh to provide high-fidelity face analysis and is engineered for stability and data quality.

✨ Key Features
- Multi-Face Analysis: Detects and applies the 468-point face mesh to up to 10 faces simultaneously in real-time.
- Flexible Input Source: Seamlessly handles streams from your local webcam or complex YouTube URLs (via yt-dlp).
- Dual-Output Data Generation: Creates high-quality data for training or analysis by saving two distinct file types:
- Face Crops: Individual cropped images of each detected face.
- Original Frames: The corresponding clean, original video frame (saved to the annotated_frames directory) for ground truth/clean dataset creation.
- Performance Control: Includes a configurable SAVE_EVERY_N_FRAMES setting to control disk I/O load and an accurate FPS counter for monitoring processing speed.
- User Experience: Features a resizable live display window (cv2.WINDOW_NORMAL) for flexible viewing.
