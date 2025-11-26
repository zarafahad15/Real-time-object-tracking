Real-Time Object Tracking using YOLOv8 and OpenCV

This project provides a real-time computer vision system capable of detecting and tracking multiple objects in video streams such as webcam feeds or video files. It uses the YOLOv8 deep learning model along with OpenCV for fast and efficient video processing. The system is suitable for applications in surveillance, robotics, autonomous systems, vehicle monitoring, and general video analytics.

⸻

Features
	•	Real-time object detection using the YOLOv8 model
	•	Multi-object tracking with labels and confidence scores
	•	Supports both webcam and video file inputs
	•	Clean, modular structure for easy customization
	•	Designed to be extendable, including advanced tracking enhancements

⸻

Technology Stack
	•	Python 3.8 or higher
	•	YOLOv8 (Ultralytics)
	•	OpenCV
	•	NumPy

⸻

Project Structure

real-time-object-tracking/
│
├── yolo_tracker.py        # Main application file
├── requirements.txt       # Required Python packages
├── README.md              # Project documentation
└── assets/                # Optional folder for visuals, screenshots, videos


⸻

Installation Instructions
	1.	Clone or download the project repository.
	2.	Install the required dependencies using the provided requirements file.
	3.	Ensure that your system has a functional webcam if you plan to run live detection.

⸻

Usage Guide
	1.	Run the main application to launch the object tracking interface.
	2.	Press the designated exit key to stop the program and close the display window.
	3.	To use a video file instead of a webcam, adjust the video input parameter in the script.

⸻

Customization Options
	•	The model can be swapped for larger or smaller YOLOv8 variants depending on performance needs.
	•	Additional tracking algorithms such as DeepSORT, ByteTrack, or OC-SORT can be added for more stable multi-object ID tracking.
	•	The system can be adapted to record detection logs, generate analytics, or save annotated video outputs.

⸻

Example Applications
	•	Security and surveillance systems
	•	Retail store analytics and behavior tracking
	•	Autonomous vehicle perception
	•	Sports performance analysis
	•	Robotics object detection
	•	Traffic monitoring and vehicle counting

⸻

Contributing

Contributions are welcome. Please submit issues or pull requests for improvements, bug reports, or feature requests.

⸻

License

This project is licensed under the MIT License.

⸻
