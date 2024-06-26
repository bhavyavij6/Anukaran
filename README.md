# Sign Language Communication System

A system for two-way communication between deaf and dumb individuals and normal persons using sign language and speech.

## Introduction

This project establishes a two-way communication system between a deaf and dumb person and a normal person. The system translates sign language into text and speech for the normal person to understand. Conversely, it converts the normal person's speech into sign language for the deaf and dumb person to understand.

## Objective

To develop a communication system that bridges the gap between deaf and dumb individuals and normal persons by facilitating seamless interaction using machine learning and natural language processing techniques.

## Features

- **Sign Language to Text and Speech**: The system captures sign language gestures and translates them into text and speech.
- **Speech to Sign Language**: The system converts spoken language into corresponding sign language gestures.

## Tech Stack

- **Programming Language**: Python
- **Libraries**:
  - **Data Processing**: Pandas, NumPy
  - **Computer Vision**: OpenCV, Mediapipe
  - **Machine Learning**: TensorFlow/Keras
  - **Natural Language Processing**: NLTK, SpeechRecognition
  - **Text-to-Speech**: gTTS
  - **Speech-to-Text**: SpeechRecognition

## Project Structure

- `notebooks/`: Jupyter notebooks containing exploratory data analysis and model development.
- `src/`: Source code for the application.
- `models/`: Pretrained models for sign language detection and speech recognition.
- `data/`: Directory containing datasets used for training and testing.
- `README.md`: Project documentation.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Sign-Language-Communication-System.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Sign-Language-Communication-System
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the application:
    ```bash
    python src/app.py
    ```

## Results

- The system effectively translates sign language into text and speech, and vice versa, enabling smooth communication between deaf and dumb individuals and normal persons.

## Future Work

- Improve the accuracy of the sign language detection model.
- Extend support for more sign languages.
- Enhance the real-time performance of the system.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
