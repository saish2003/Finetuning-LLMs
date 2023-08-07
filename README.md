# Finetuning-LLMs

## 🩺 Medical Query Assistant | MedGPT-2

Welcome to the Medical Query Assistant project! This application utilizes a fine-tuned GPT-2 model to provide answers to medical queries, symptoms, and mental health-related questions. Users can enter their queries and receive informative responses generated by the fine tuned GPT-2 model aka MedGPT-2. 

## 📋 Project Outline

This project consists of the following main components:

1. **Data Collection**: Gather a diverse and representative dataset of medical queries, symptoms, and mental health data. This may involve scraping online forums, medical websites, or using pre-existing datasets.

2. **Data Preprocessing**: Clean and preprocess the collected data to ensure it's in a suitable format for training the GPT-2 model. This includes removing irrelevant information, handling missing data, and formatting the data appropriately.

3. **Fine-tuning GPT-2**: Use the preprocessed data to fine-tune the GPT-2 model. This involves training the model on your specific dataset to adapt it to medical queries, symptoms, and mental health data. You can utilize frameworks like Hugging Face's Transformers library to facilitate this process.

4. **Model Execution**: Once the fine-tuning is complete, save the trained GPT-2 model for later use.

5. **Front-End Development**: Create a user-friendly interface using a web framework like Streamlit. Design a form where users can enter their medical queries and submit them.

6. **Backend Integration**: Connect the Streamlit front end to your fine-tuned GPT-2 model. Pass the user's input to the model and retrieve the generated answer.

7. **Display Answer**: Present the generated answer from the MedGPT model on the Streamlit interface for the user to view.


## 👏 Acknowledgments

I would like to acknowledge the developers behind the Hugging Face's Transformers library, which greatly facilitated the fine-tuning process.

## 🚀 Roadmap

Future improvements for this project include:

- Enhancing the accuracy and responsiveness of the generated answers.
- Expanding the dataset to include more diverse medical queries and symptoms.
- Implementing user feedback mechanisms to improve the application over time.
