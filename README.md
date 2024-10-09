# AI Chatbot

This repository contains an **intent-based chatbot** built using **NLTK** and **Deep Learning** models. The chatbot is integrated with APIs and supports interaction through a web-based UI.

## Features
- **Intent Recognition**: Using Natural Language Processing to understand user queries.
- **Deep Learning Model**: Implements a Feedforward Neural Network (FNN) to predict intents.
- **API Integration**: Supports weather, movie APIs, and Wikipedia data parsing.
- **Web Interface**: A simple user interface built with JavaScript, HTML, and ReactJS.
- **Flask API Endpoint**: Flask framework is used to create an API for chatbot communication.

## Setup Instructions

1. Clone the repository: `git clone https://github.com/Tyron-Barnard/AI-Chatbot.git` and `cd AI-Chatbot`
2. Create a Python virtual environment: `python -m venv venv` and activate it using `venv\Scripts\activate`
3. Install dependencies: `pip install -r requirements.txt`
4. Train the chatbot model: `python train.py`
5. Run the chatbot: `python chat.py`
6. Run the Flask API: `python app.py`

## API Integration
This chatbot supports integration with external APIs like the **Weather API** and **Movie API**. It fetches real-time data based on user queries. To start using these APIs, install the required packages (`requests`) and replace the API keys in the `chat.py` file with your own.

## Model Training
The chatbot uses a Feedforward Neural Network (FNN) implemented in **PyTorch** for intent recognition. The training process includes tokenization, stemming, and Bag of Words processing.

## License
This project is licensed under the MIT License.
