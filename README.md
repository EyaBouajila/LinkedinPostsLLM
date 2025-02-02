# LinkedIn Post Generator
![Screenshot 2025-02-02 181408](https://github.com/user-attachments/assets/29f2e73a-3194-4bb6-8005-945b885ea17c)

## Overview
The LinkedIn Post Generator is a Streamlit-based application designed to generate engaging LinkedIn posts. The tool utilizes a few-shot learning approach to create content based on predefined examples, allowing users to customize the length, language, and topic of the post.

## Features
- User-friendly UI: Streamlit-powered interface for easy selection of options.
- Customizable Posts: Users can choose topic, post length (Short, Medium, Long), and language (English, Hinglish).
- Few-shot Learning: Uses previously collected LinkedIn posts to guide the language model in generating better content.
- LLM-powered Generation: Utilizes langchain_groq with the llama-3.3-70b-versatile model for generating high-quality posts.
- Preprocessing Pipeline: Cleans, enriches, and categorizes LinkedIn posts before they are used as examples for generation.

## Technologies Used
- Streamlit: For the user interface.
- LangChain: To structure prompts and interact with the LLM.
- Groq API: For leveraging the llama-3.3-70b-versatile model.
- Pandas: For data processing.
- JSON: For storing and handling processed LinkedIn posts.
- Python: Core language for implementation.

