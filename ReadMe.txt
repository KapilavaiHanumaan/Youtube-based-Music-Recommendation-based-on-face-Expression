 Project Overview
This system intelligently recommends music by detecting the user’s facial expressions in real time. Using a webcam and deep learning techniques, it identifies emotions like Happy, Sad, Angry, or Surprised, and then searches YouTube to play songs that match the detected mood.

 Methodology
1.Facial Emotion Detection
Utilizes MediaPipe and OpenCV for real-time face tracking.
Key facial landmarks are extracted and analyzed to classify emotions.

2.Emotion Classification
A pre-trained TensorFlow/Keras model predicts the emotional state from landmark data.
Emotions detected include: Happy, Sad, Angry, Surprise, and Neutral.
Music Recommendation Engine
Based on the detected emotion, the system queries YouTube for a suitable playlist or track using automation and opens it in a web browser.

3.User Interface
A simple and interactive Streamlit web app displays live emotion results and controls music search.
Easy to use and runs directly in the browser.

4.Tech Stack
Python 3.8+
OpenCV + MediaPipe (Facial Landmark Detection)
TensorFlow/Keras (Emotion Classification)
NumPy
Streamlit (Web UI)
Web Browser Automation

 Output: A seamless system that understands how you feel — and finds the right song to match your mood.
 Ideal For: AI enthusiasts, music lovers, and anyone exploring emotion-aware systems.


