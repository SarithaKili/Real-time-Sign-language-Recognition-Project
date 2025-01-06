## Real-time-Sign-language-Recognition-Project

#Project Structure:

model.py: Contains the CNN architecture (ASLNet)
train.py: Contains training code and dataset handling
real_time_detection.py: Implements real-time webcam detection
main.py: Entry point to run the project


#Key Features:

Custom CNN architecture built from scratch
Data augmentation with random flips and rotations
Real-time webcam integration
On-screen prediction display with confidence scores
Model checkpointing to save the best model


#To run the project:
Make sure your data is organized in folders as described
Install required packages: torch, torchvision, opencv-python, pillow
Run python main.py
