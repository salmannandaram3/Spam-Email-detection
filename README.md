
# AI-Based Email Classification System

## Project Overview

The **AI-Based Email Classification System** is a Python-based web application designed to classify email messages as **Spam** or **Not Spam**.

The application allows users to enter an email message and receive a classification result. It uses keyword-based classification to identify predefined spam-related words.

## Objectives

- Identify spam and legitimate email messages.
- Reduce the manual effort involved in checking unwanted emails.
- Provide a simple and user-friendly interface.
- Display classification results quickly.
- Provide a foundation for future machine learning enhancements.

## Technologies Used

- **Python** – Application development
- **Flask** – Backend web framework
- **HTML** – Web page structure
- **Regular Expressions (re)** – Optional text processing

## Features

- Email message input form
- Spam email identification
- Not Spam email identification
- Classification result display
- Input validation
- Option to classify another email

## Project Structure

```text
AI-Email-Classification/
│
├── app.py
└── README.md
```

## Installation and Setup

### Step 1: Install Python

Download and install Python from:

https://www.python.org/downloads/

### Step 2: Install Flask

Open the terminal in your project folder and run:

```bash
pip install flask
```

### Step 3: Run the Application

Execute the following command:

```bash
python app.py
```

### Step 4: Open the Application

Open your web browser and visit:

http://127.0.0.1:5000/

## How to Use

1. Open the application in your browser.
2. Enter an email message in the text area.
3. Click the **Classify Email** button.
4. View the classification result.
5. Click **Check Another Email** to classify another message.

## Classification Logic

The application uses a simple keyword-based approach.

- If the email contains predefined spam-related keywords such as "win", "free", "prize", or "lottery", it is classified as **Spam**.
- If no predefined spam keyword is found, it is classified as **Not Spam**.

**Note:** This version does not use a trained machine learning model. The classification result depends on the predefined keywords.

## Future Enhancements

- Integrate machine learning algorithms such as Naive Bayes.
- Use TF-IDF for text vectorization.
- Train the system using a labeled email dataset.
- Integrate Gmail API for automatic email classification.
- Add a database to store classification history.
- Improve classification accuracy using advanced NLP techniques.

## Conclusion

The AI-Based Email Classification System demonstrates the use of Python and Flask to develop a simple email classification web application. It provides a foundation for future improvements using machine learning and advanced text processing techniques.
