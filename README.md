# Real-Time-Color-Detection-Tracking
OpenCV-based real-time and video-based color detection &amp; tracking using Google Colab
This project implements a color detection and tracking system using Python, OpenCV, NumPy, and Google Colab. It identifies a selected color in video frames and tracks the object in real-time or using prerecorded video. The system uses the HSV color model for accurate color segmentation and applies contour detection and morphological operations to ensure clean and reliable tracking.

📝 Abstract

This project focuses on detecting and tracking a colored object in real-time using image processing techniques. By converting video frames to HSV color space and applying thresholding, the system isolates a target color, generates a mask, removes noise, and identifies the object using contour detection. The detected object is then highlighted with an enclosing circle and centroid marker. Due to hardware limitations, the project also supports prerecorded video input for demonstration. This system forms the basis for more advanced computer vision applications in robotics, automation, gesture recognition, and object tracking.

🚀 Features

✔ Detects a specific color in each frame
✔ Tracks object movement with centroid + circle
✔ Works with prerecorded video files
✔ Supports webcam capture through JavaScript (in Colab)
✔ Cleaned detection using morphological operations
✔ Fully implemented in Google Colab (no local installation needed)
✔ Simple, modular, and ready for enhancement

🛠️ Technologies Used

Python – Main programming language

OpenCV – Image processing & contour detection

NumPy – Pixel array operations

Google Colab – Cloud execution environment

HSV Color Space – Accurate color segmentation

Morphological Operations – Noise removal

Contour Detection – Object boundary detection

Video Processing – Frame-by-frame tracking

JavaScript (Browser API) – Webcam frame capture

GitHub – Version control & project hosting

📂 Project Structure
Real-Time-Color-Detection-Tracking/
│
├── color_detection_project.ipynb     # Main project notebook
├── sample-mp4-file.mp4               # Demo video (optional)
├── tracking_output_1.png             # Screenshots
├── tracking_output_2.png
├── Final_Project_Report.pdf          # Project documentation
├── README.md                         # This file
└── other supporting files

🧠 How It Works (Short Explanation)

Each video frame is captured and converted from BGR → HSV.

A color range mask is applied to extract the target color.

Morphological filters remove noise from the mask.

Contours are detected from the clean mask.

The largest contour is selected as the target.

An enclosing circle and centroid are drawn for tracking.

Output is displayed frame-by-frame.

▶️ How to Run the Project in Google Colab

Open the notebook in Colab

Install OpenCV

Upload your video (.mp4) or use webcam

Run all cells

View the tracking results displayed per frame

🎥 Output Example

(Add your screenshots here after uploading them)

Example:

🔮 Future Scope

Multi-color tracking

Gesture control & motion recognition

Integration with robotics

Smart object-following systems

Mobile app implementation

Real-time background removal
