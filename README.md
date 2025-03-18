# Sign Language Detection

## Introduction
This project is a **Real-Time Sign Language Detection System** that translates sign language gestures into text. It utilizes **Machine Learning and Computer Vision** to bridge communication gaps for individuals who rely on sign language. The system captures hand gestures, processes them in real-time, and converts them into readable text using a trained model.

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - OpenCV (Image Processing)
  - MediaPipe (Hand Landmark Detection)
  - Scikit-learn (Random Forest Classifier)
  - Pickle (Model Saving & Loading)
- **Machine Learning Model:** Random Forest Classifier
- **Framework:** Flask (for web-based deployment)

## Features
- Real-time sign language detection
- Converts ASL hand gestures into text
- High accuracy using machine learning techniques
- Robust hand landmark detection with MediaPipe
- Supports multiple gesture classes

## Project Architecture
1. **Data Collection:** Capture images of ASL gestures.
2. **Preprocessing:** Extract hand landmarks using MediaPipe.
3. **Model Training:** Train a Random Forest classifier using extracted features.
4. **Real-Time Detection:** Deploy the model to recognize gestures in live video feeds.
5. **Web Application:** Use Flask to display predictions in a user-friendly interface.

## Challenges & Solutions
- **Gesture Variability:** Addressed by collecting diverse training samples.
- **Real-Time Processing:** Optimized MediaPipe and model inference for low latency.
- **Accuracy Improvement:** Used feature selection and hyperparameter tuning.
- **Error Handling:** Implemented robust error handling for API failures and processing issues.

## Future Enhancements
- Expand ASL gesture vocabulary
- Improve UI and user experience
- Mobile application support
- Implement deep learning models (e.g., CNNs, Transformers)
- Add voice output for detected gestures

## Setup Instructions
```bash
# Clone the repository
git clone https://github.com/yourusername/sign-language-detection.git
cd sign-language-detection

# Install dependencies
pip install -r requirements.txt

# Run the Flask application
python app.py
```

## License
This project is licensed under the **MIT License**.
