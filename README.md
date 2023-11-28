# Data Driven Chatbot - AI Assistant
Have a seamless human like conversation with chatbot and get the queries resolved !!!
## Overview
The AI Query Bot is an interactive chatbot designed to assist users with queries related to the custom dataset uploaded by the user. It utilizes advanced natural language processing (NLP) techniques, vector embeddings, and external APIs to provide intelligent responses.

Please have a look how the application is running!

![chat1](https://github.com/venkateshyeturi904/Data-Driven-chatbot---AI-Assistant/blob/main/Images/chatbot_1.png)
![chat2](https://github.com/venkateshyeturi904/Data-Driven-chatbot---AI-Assistant/blob/main/Images/chatbot_2.png)
![chat3](https://github.com/venkateshyeturi904/Data-Driven-chatbot---AI-Assistant/blob/main/Images/chatbot_3.png)

*AI chatbot answering queries*

## Implementation
- **Vector Database:** Utilizes Pinecone as a vector database to store and retrieve embeddings efficiently.
- **Language Models:** Integrates OpenAI's GPT-3.5-turbo and LangChain for powerful language understanding and conversation generation.
- **User Interface:** Implements a user-friendly interface using Streamlit for a seamless interaction experience.
## Project Structure
- **`main.py`:** Contains the main Streamlit app code for the query bot.
- **`utils.py`:** Includes utility functions for refining queries, managing conversations, and interfacing with external APIs.
## Getting Started
Follow these steps to run the project locally:
### 1. Clone the Repository
```bash
git clone https://github.com/venkateshyeturi904/Data-Driven-chatbot---AI-Assistant.git
```
### 2. Create a virtual environment (If unable to run streamlit application)
#### On Unix/Linux/Mac
```bash python3 -m venv venv```
#### On Windows
```bash python -m venv venv```
### 3. Activate the virtual environment
#### On Unix/Linux/Mac
```bash source venv/bin/activate```
#### On Windows
```bash venv\Scripts\activate```
### 4. Install Dependencies
```bash pip install -r requirements.txt```
### 5. Run the streamlit app
```bash streamlit run main.py```

Note : In place of API keys, please enter your own API keys to run this project. For the security reasons these links have been hidden
