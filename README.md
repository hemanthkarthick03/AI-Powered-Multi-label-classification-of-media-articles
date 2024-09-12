# 📰 Media Monitoring Multilabel Classification: Multi-label classification of printed media articles to topics

## Table of Contents
- [📖 Overview](#overview)
- [📚 Project Description](#project-description)
- [⭐ Features](#features)
- [🚀 Getting Started](#getting-started)
  - [📋 Prerequisites](#prerequisites)
  - [⚙️ Installation](#installation)
    - [🛠️ Django Backend](#django-backend)
    - [🌐 React Frontend](#react-frontend)
- [📂 Usage](#usage)
- [💻 Technologies Used](#technologies-used)

## 📖 Overview

This project aims to create a data-driven solution for media monitoring companies to efficiently categorize printed media articles into multiple relevant topics. By leveraging machine learning techniques, including Natural Language Processing (NLP) and image analysis, the system automates the time-consuming manual classification process, enhancing efficiency and effectiveness.

## 📚 Project Description

Media monitoring companies often analyze a large volume of printed media articles from newspapers, magazines, and other sources to extract valuable insights. Automating the classification process using machine learning techniques can significantly enhance efficiency and effectiveness. The primary objective of this project is to develop a multi-label classification system capable of accurately classifying printed media articles into relevant topics. The key steps of the project include:

- 🗂️ Data collection and preprocessing
- 🛠️ Feature engineering
- 🧠 Model selection and training
- ⚙️ Hyperparameter tuning
- 🧪 Model evaluation
- 🌐 Web interface development
- 📊 Data-driven classification

## ⭐ Features

- 🏷️ Multilabel classification of printed media articles into relevant topics.
- 🖼️ Support for three types of input: Text, Image, and URL.
- 🔑 Automatic extraction of keywords, sentiment analysis, and entity recognition.
- 📝 Generation of concise article summaries.
- 💻 User-friendly web interface for input and result visualization.

## 🚀 Getting Started

### 📋 Prerequisites

- 🐍 Python 3.x
- 🌍 Django
- ⚛️ React.js
- 📷 OpenCV
- 🕸️ BeautifulSoup
- 🤖 BERT models (for multi-label classification)

### ⚙️ Installation

#### 🛠️ Django Backend

1. Clone the repository: `git clone [repository_url]`
2. Navigate to the Django backend directory: `cd [backend_directory]`
3. Create a virtual environment (optional but recommended): `python -m venv venv`
4. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS and Linux: `source venv/bin/activate`
5. Install Django and other dependencies: `pip install -r requirements.txt`
6. Apply database migrations: `python manage.py migrate`
7. Start the Django development server: `python manage.py runserver`

#### 🌐 React Frontend

1. Navigate to the React frontend directory: `cd [frontend_directory]`
2. Install project dependencies: `npm install`
3. Start the React development server: `npm start`

## 📂 Usage

1. Ensure both the Django backend and React frontend servers are running.
2. Access the web interface to provide input and view the classification results.

## 💻 Technologies Used

- 🐍 Python
- 🌍 Django
- ⚛️ React.js
- 📷 OpenCV
- 🕸️ BeautifulSoup
- 🤖 BERT (Bidirectional Encoder Representations from Transformers)
- ☁️ IBM Watson Studio : To create the Multi-Label Classifier model
- 💾 IBM COS : To store the training dataset

---
