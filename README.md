# AI_Driven_IoT_project
This is the repository of AI driven IoT based project
The project aims to develop a smart, automated solution for maintaining the efficiency of photovoltaic (PV) solar panels by integrating Artificial Intelligence (AI) and Internet of Things (IoT) technologies. Dust accumulation on solar panels significantly reduces their energy output. To address this issue, the proposed system detects dusty panels in real-time using AI-based image classification and initiates an automatic cleaning process without human intervention.

The core of the system involves a camera module that periodically captures images of solar panels. These images are analyzed using a pre-trained Convolutional Neural Network (CNN) model that classifies the panels as either ‘Clean’ or ‘Dusty’. The AI model is trained on a labeled dataset of PV module images and optimized to run directly on an ESP32 microcontroller, making the system cost-effective and suitable for remote locations without needing constant cloud connectivity.

Upon detecting a dusty panel, the ESP32 activates a cleaning mechanism—through GPIO-controlled relays or motor drivers. This automation ensures regular cleaning, improving the panel’s overall efficiency and lifespan.

Technologies Used:

~Artificial Intelligence (AI): Image classification using CNN models (TensorFlow/Keras)

~IoT Hardware: ESP32 microcontroller for control and connectivity

~Sensors: Camera module (e.g., USB/Webcam) for image capture

~Cloud/Edge: Model deployment on edge device (ESP32)

~Python: For model development and training

~OpenCV: Image pre-processing and analysis

~Flask/Streamlit (optional): For visualization/dashboard interface

~Platforms: Jupyter Notebook , Arduino IDE
