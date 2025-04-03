# SIGN_LANGUAGE_RECOGNITION
Sign Language Recognition is an Python-based that translates hand gestures into text with speech using computer vision, and machine learning algorithms. It enhances communication for the deaf by recognizing gestures via cameras  and mapping them to meaningful words.

# Final Result
![image](https://github.com/user-attachments/assets/4bf94395-6268-439f-934b-121c23f8a938)
                 This is the output we got after running the code
![image](https://github.com/user-attachments/assets/cab01b86-7985-4438-9acb-bc92a6c72f53)
                 Recognition of Hand gesture: In the above image it classifies the hand gesture as Letter – “L” 
![image](https://github.com/user-attachments/assets/b014246d-eb69-43ce-a85c-e76d7ddc1fa1)
                                          Recognition of Hand gesture: In the above image it classifies the hand gesture as Letter – “W”
                
# Table of Contents
[Overview](#overview)  
[Dataset](#dataset)  
[Installation](#installation)  
[Limitations](#limitations)  
[Project Structure](#project-structure)  
[Data Preprocessing](#data-preprocessing)  
[Model Training](#model-training)  
[Contributing](#contributing)  
[License](#license)  
[Contact](#contact)  
  

# Overview 
Sign Language Recognition is an python-based that translates hand gestures into text with speech, enabling communication for the deaf and hard-of-hearing. This project uses Convolutional Neural Networks (CNNs) to recognize and classify sign language gestures based on image or video input, improving accessibility and interaction.

# Dataset
 The dataset used in this project includes Hand gestures such as:
- Hand shape and finger positions  
- Movement and orientation of the hands  
- Background conditions and lighting variations  
- Gesture sequences for dynamic signs  
- Other relevant features  

The dataset contains features for accurately recognizing and classifying sign language gestures.
Datasets :
![image](https://github.com/user-attachments/assets/13e1fc62-8c43-41bc-b782-3bf834847841)
![image](https://github.com/user-attachments/assets/27e9a19a-dc08-420d-a878-0817343ad16b)

# Installation
To run this project locally, follow these steps:  

1. Clone the repository: 
git clone https://github.com/RithikaReddyPeram/SIGN_LANGUAGE_RECOGNITION.git
2. Install the required packages: pip install -r requirements.txt

# Limitations
- Covering all the alphabets from A-Z and two more are Space and Nothing hand gestures.

# Project-Structure
- code/: Contains the main Python scripts for sign language recognition  
- datasets/: Contains image datasets used for training and testing  
- app.py: Main Flask application for running the model  
- model.h5: Trained machine learning model for recognizing sign language gestures  
- gesture's.jpg: Sample image of sign language gestures  
- README.md: Project documentation  
- LICENSE: License information for the project  
- requirements.txt: List of required Python packages 

# Data Preprocessing
The data preprocessing steps include:  

- Image resizing and normalization  
- Data augmentation to improve model generalization  
- Converting images to grayscale for better feature extraction  
- Splitting the dataset into training and testing sets

# Model-Training
A Convolutional Neural Network (CNN) is trained for sign language recognition: Gesture Recognition Model--Classifies hand gestures into corresponding sign language symbols.  

The training process involves:  

- Splitting the dataset into training and testing sets  
- Data augmentation to enhance model robustness
- Initializing the CNN architecture for feature extraction
- Training the model using labeled gesture images
- Fine-tuning hyperparameters to improve accuracy  
  
## Contributing  
Contributions are welcome! If you have any ideas, suggestions, or bug fixes, please open an issue or submit a pull request.

# License
This section states that the Realtime Sign Language Recognition project is released under the MIT License.

# Contact
For any questions or inquiries, feel free to contact me at geethikareddy105@gmail.com







