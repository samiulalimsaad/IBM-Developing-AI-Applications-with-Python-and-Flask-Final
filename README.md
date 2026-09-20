# Final Project - Emotion Detection Application

An AI-based web application deployed using Flask that analyzes customer emotions from text using the Watson NLP library.

## Project Description

This application evaluates customer feedback to detect emotions including anger, disgust, fear, joy, and sadness. It also identifies the dominant emotion among them. The application handles error cases such as blank inputs and is tested using unit tests and static code analysis.

## Features

- Emotion detection using Watson NLP Emotion Predict function
- Identification of the dominant emotion
- Error handling for status code 400 (blank text inputs)
- RESTful API deployment using Flask framework
- Unit testing with Python's unittest module
- Code quality verified with PyLint (10/10 score)

## Project Structure

```text
final_project/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── static/
│   └── mywebscript.js
├── templates/
│   └── index.html
├── test_emotion_detection.py
├── server.py
└── README.md
