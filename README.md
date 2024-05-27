# 🚗✨ Lane_Detection_for_Autonomous_Vehicles and Video Comparison Tool
- Welcome to the Lane Detection and Video Comparison Tool! This repository features a sophisticated lane detection pipeline using OpenCV and a futuristic, user-friendly Tkinter GUI to compare input and processed videos side-by-side. Perfect for developers and researchers working on autonomous driving and advanced driver-assistance systems (ADAS).

# 🌟 Features:
- 🔍 Lane Detection: Efficiently detect and highlight lane lines in video frames using advanced image processing techniques.
- 📹 Video Comparison: Display original and processed videos side-by-side for easy visual comparison.
- 📏 Curvature Calculation: Accurately calculate and display the curvature of detected lanes.
- ⏩ Speed Control: Adjust the playback speed of the video to analyze lane detection performance.
- 🌙 Dark Mode: Toggle dark mode for a comfortable viewing experience, especially in low-light environments.
- 🖥️ Interactive GUI: Sleek and user-friendly interface with various control options for a seamless experience.

# Flowchart:
                                                         +---------------------------+
                                                        | Start the Application     |
                                                        +-------------+-------------+
                                                                      |
                                                                      v
                                                        +---------------------------+
                                                        | Read Video Frame (Input)  |
                                                        +-------------+-------------+
                                                                      |
                                                                      v
                                                        +---------------------------+
                                                        | Convert to Grayscale      |
                                                        +-------------+-------------+
                                                                      |
                                                                      v
                                                        +---------------------------+
                                                        | Apply Gaussian Blur       |
                                                        +-------------+-------------+
                                                                      |
                                                                      v
                                                        +---------------------------+
                                                        | Detect Edges (Canny)      |
                                                        +-------------+-------------+
                                                                      |
                                                                      v
                                                        +---------------------------+
                                                        | Mask Region of Interest   |
                                                        +-------------+-------------+
                                                                      |
                                                                      v
                                                        +---------------------------+
                                                        | Detect Lane Lines (Hough) |
                                                        +-------------+-------------+
                                                                      |
                                                                      v
                                                        +---------------------------+
                                                        | Separate Left and Right   |
                                                        +-------------+-------------+
                                                                      |
                                                                      v
                                                        +---------------------------+
                                                        | Draw and Fill Lane Area   |
                                                        +-------------+-------------+
                                                                      |
                                                                      v
                                                        +---------------------------+
                                                        | Overlay on Original Frame |
                                                        +-------------+-------------+
                                                                      |
                                                                      v
                                                        +---------------------------+
                                                        | Display in GUI (Original  |
                                                        | vs Processed)             |
                                                        +-------------+-------------+
                                                                      |
                                                                      v
                                                        +---------------------------+
                                                        | End the Application       |
                                                        +---------------------------+

# How big Tech like TESLA are incorporating this:
- Tesla's autonomous vehicles use a computer vision system called Tesla Vision to detect lane lines and other environmental variables. Tesla's Model 3 has cameras mounted on the front, rear, left, and right sides of the car to monitor the surrounding area. These cameras can detect road markings, obstacles, pedestrians, and other vehicles. Tesla's Vision system also uses Hydranets to only use what's needed by the system, and runs at least 50 neural networks simultaneously.

