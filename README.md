# Text-Question-Answering

A Python application that performs question answering on text using the DistilBERT model.

# Description

The Question Answering with DistilBERT application is a Python program that allows you to input a text and a related question. It utilizes the DistilBERT model from the Hugging Face Transformers library to predict the answer to the question within the given text.

# Features

> **Question Answering:** The application performs question answering on text using the DistilBERT model. It allows you to input a text and a related question and predicts the answer based on the model's analysis of the text.

> **DistilBERT Model:** The TextQA class uses the DistilBERT model, which is a smaller and faster variant of the original BERT model. It has been pretrained on a large corpus of text and fine-tuned for question answering tasks.

> **Streamlit Interface:** The application provides a user-friendly interface using Streamlit, allowing you to enter the text and question interactively and view the predicted answer.


# Installation

**Clone the repository:**

     https://github.com/AdopleAIOrg/Text-Question-Answering.git

**Install the required dependencies:**

     pip install -r requirements.txt


# Usage

1. Run the application:

       !streamlit run app.py & npx localtunnel --port 8501

2. Access the application by opening the provided URL in your web browser.

3. Enter the text in the text area.

4. Write a question related to the text in the question input box.

5. The application will predict the answer based on the text and question using the DistilBERT model.

6. The predicted answer will be displayed below the question input.

# Contact

If you have any questions or feedback, feel free to contact me at ceo@adopleai.com.
