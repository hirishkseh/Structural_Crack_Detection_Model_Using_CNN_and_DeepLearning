# Structural_Crack_Detection_Model

## Summary

This project presents a structural crack detection model utilizing deep learning techniques, specifically Convolutional Neural Networks (CNN), implemented in Python. The model is designed to accurately identify and classify cracks in various structures, aiding in the maintenance and safety assessment of buildings, bridges, and other infrastructure.

### Key Features:
- **Dataset**: Divided into positive (crack) and negative (no crack) categories to facilitate supervised learning.
- **Deep Learning Approach**: Employs a Convolutional Neural Network (CNN) for high accuracy in crack detection.
- **Data Augmentation**: Uses TensorFlow's data augmentation techniques to enhance the training dataset and improve model robustness.
- **Model Training**: Utilizes TensorFlow for building and training the CNN model.
- **Model Optimization**: Optimized using TensorFlow Lite for efficient deployment on edge devices.
- **Backend Server**: Built using FastAPI to handle model inference requests and serve the results.
- **Frontend**: Developed with ReactJS, providing a user-friendly interface for uploading images and displaying detection results.
- **Deployment**: The website is deployed on localhost for demonstration and testing purposes.

### Installation and Usage:
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/hirishkseh/Structural_Crack_Detection_Model_Using_CNN_and_DeepLearning

2. **Navigate to the Project Directory**:
   ```bash
   cd Structural_Crack_Detection_Model

3. **Install Required Dependencies**:
   ```bash
   pip install -r requirements.txt
   cd frontend
   npm install
   cd ..

4. **Run the Backend Server**:
   ```bash
   uvicorn main:app --reload

4. **Run the Frontend**:
   ```bash
   cd frontend
   npm run start

### Future Enhancements:
- **Dataset Expansion**: Incorporate more diverse images to improve model robustness.
- **Real-Time Detection**: Develop capabilities for real-time crack detection using video feeds.
- **Model Optimization**: Further optimize the model for faster inference and lower latency on various devices.
- **Cloud Deployment**: Deploy the backend and frontend on cloud platforms for wider accessibility.

This project aims to provide a reliable tool for structural health monitoring, contributing to the prevention of potential structural failures through early crack detection.


### Collaborator:
This project is made in collabrations with my friends/team-mates Atharva Kawalkar and Kartik Giri.