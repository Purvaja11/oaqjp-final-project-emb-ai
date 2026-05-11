# Emotion Detection Web Application (Final Project)

## Overview
This project is a Flask-based Emotion Detection web application developed as part of an AI/ML certification final project. The application uses the Watson NLP Emotion Prediction API to analyze input text and detect emotions such as anger, disgust, fear, joy, and sadness. It also identifies the dominant emotion from the text.

---

## Problem Statement
The goal of this project is to build an application that can:
- Accept user input text
- Send the text to an emotion detection API
- Process the response
- Display emotion scores and the dominant emotion in a structured format
- Handle errors and invalid inputs gracefully

---

## Features
- Emotion detection from text input
- Outputs emotion scores:
  - anger
  - disgust
  - fear
  - joy
  - sadness
- Identifies dominant emotion
- Flask-based web interface
- Error handling for invalid or empty input
- Unit testing for validation of functionality
- Static code analysis using pylint (score: 10/10)

---

## Project Structure

EmotionDetection/
│
├── init.py
├── emotion_detection.py
│
templates/
├── index.html
│
static/
├── style.css
│
server.py
test_emotion_detection.py
README.md


---

## Technologies Used
- Python 3
- Flask
- Watson NLP Emotion Detection API
- Requests library
- HTML, CSS
- Pylint (for code quality analysis)

---

## How to Run the Application

### Step 1: Start the Flask server
```bash
python3 server.py
Step 2: Open the application in browser
http://127.0.0.1:5000
Step 3: Enter text input

Example:

I am extremely happy today
Example Output

For the input:

I am extremely happy today

The output will be:

anger: 0.01
disgust: 0.00
fear: 0.02
joy: 0.95
sadness: 0.02
Dominant emotion: joy
Unit Testing

To run unit tests:

python3 test_emotion_detection.py

All test cases should pass successfully.

Error Handling

The application handles:

Empty input
Invalid input
API failure (HTTP 400 response)

Example response:

Invalid text! Please try again!
Static Code Analysis

Pylint was used to ensure code quality and maintainability.

Final score achieved:

10.00/10
Project Status

Completed successfully as part of the final AI/ML certification project. All required tasks including API integration, Flask deployment, testing, error handling, and code analysis have been implemented and verified.

Author

Developed as part of Skills Network / IBM AI Certification Final Project.