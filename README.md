# drowsiness-detetction
Driver Drowsiness Detection System using Python and OpenCV enhances road safety by monitoring real-time video feeds to detect signs of driver fatigue. Employing facial detection with OpenCV and Dlib, it calculates metrics like the Eye Aspect Ratio (EAR) and analyses blink frequency and yawning.
The proposed Driver Drowsiness Detection System is designed to improve road safety by monitoring and detecting signs of driver fatigue in real-time. Utilizing Python and OpenCV libraries, the system processes video input from an onboard camera to analyze the driver's facial features and eye movements. The core components of the system include video capture, facial feature detection, EAR calculation, blink and yawn detection, an alert mechanism, real-time processing, and adaptability through machine learning.
Video capture is achieved using a camera positioned inside the vehicle, continuously feeding live footage of the driver's face. OpenCV’s Haar cascade classifiers detect the driver’s face and eyes within these frames, enabling accurate tracking of eye and mouth movements. The Eye Aspect Ratio (EAR), calculated from eye contours, serves as a crucial metric for determining eye openness. A low EAR over a sustained period indicates potential drowsiness, triggering the system's alert mechanism.
The system also monitors blink frequency and duration, using these parameters to detect drowsiness. Additionally, yawning is identified by analyzing mouth movements, providing an extra layer of fatigue detection. When drowsiness is detected, the system activates an alert mechanism, which can include auditory warnings, visual signals, or haptic feedback to prompt the driver to take corrective action. Designed for real-time operation, the system ensures immediate detection and response. Efficient algorithms and optimizations enable low latency and high performance, even under varying lighting conditions and different driving environments. Machine learning techniques enhance the system's adaptability, allowing it to learn from individual driver behavior and environmental factors, thereby improving accuracy and reliability over time.
