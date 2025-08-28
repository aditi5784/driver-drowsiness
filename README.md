# Driver Drowsiness Detection

##  Overview
This project detects driver drowsiness in real time using facial landmarks.  
It monitors the driver’s eye state through a webcam and triggers an alarm if signs of sleepiness or drowsiness are detected.  
The system is built with Python, OpenCV, dlib, and Pygame.

---

##  Features
1. Real-time face and eye detection using **dlib**’s 68-point facial landmark model.  
2. Calculates **eye aspect ratio (EAR)** to classify states:
   - **Active**  
   - **Drowsy**  
   - **Sleeping**  
3. Triggers an **alarm sound** when the driver appears to be sleeping.  
4. Displays detection status on the video feed.

---

##  Tech Stack
- **Programming Language:** Python  
- **Libraries:**  
  - OpenCV → image and video processing  
  - dlib → face detection and landmark extraction  
  - imutils → easier handling of dlib landmarks  
  - numpy → mathematical calculations  
  - pygame (mixer) → play alarm sound  
