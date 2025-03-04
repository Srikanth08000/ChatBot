# Simple Q&A Chatbot with Ollama (Streamlit App)

## 📖 Project Description
The **Simple Q&A Chatbot** is a conversational AI application built with **Streamlit** and **LangChain**. It leverages **Ollama** to utilize open-source language models like `gemma:2b` for answering user queries in real-time. The app provides an easy-to-use interface with options to adjust the response creativity and token limits. With **Langsmith** integration, users can track and analyze chatbot interactions for better performance insights.

This project serves as a lightweight and flexible solution for information retrieval, educational purposes, and rapid prototyping of conversational AI systems.

---

## ✨ Features
- **Interactive Chat Interface**: Type your question and receive instant responses.
- **Model Customization**: Choose from available open-source models like `gemma:2b`.
- **Adjustable Response Settings**:
  - Creativity level (0.0 to 1.0) for controlling how imaginative the responses are.
  - Maximum token limit for managing response length.
- **Langsmith Integration**: Track and monitor the chatbot's performance and query history.
- **Built with Open-Source Models**: No reliance on proprietary models, ensuring transparency and flexibility.

---

## 🛠️ Technology Stack
- **Streamlit**: For building the web-based interface.
- **LangChain**: Core framework for managing prompts and connecting with the language model.
- **Ollama**: For running open-source language models.
- **Langsmith**: For tracking and analyzing interactions.
- **Python dotenv**: For managing environment variables.

---

## 🚀 How to Run the Application

### Prerequisites
- Python 3.8 or later
- `pip` (Python package manager)

## 🔑 How to Get Your OpenAI API Key
1. Go to the [OpenAI website](https://openai.com).
2. Sign up for an account or log in if you already have one.
3. Navigate to your **API Keys** section by clicking on your profile icon and selecting **API Keys**.
4. Click on **Create new secret key**.
5. Copy the generated API key. This key will be used in your `.env` file as `OPENAI_API_KEY`.

⚠️ **Important:** Keep your API key secure and do not share it publicly. Never hard-code it into your scripts. Always use environment variables to manage it.

---

## 🖥️ Application Interface

### Main Interface:
- **User Input**: Enter your question in the input field.
- **Response Display**: The chatbot responds to your question in real-time.

### Sidebar Controls:
- **Model Selection**: Choose your preferred language model (e.g., `gemma:2b`).
- **Creativity Slider**: Adjust the level of creativity (from straightforward answers to more imaginative ones).
- **Max Tokens**: Set the maximum length of responses.

### Example Usage:
#### Question:  
*"What is LangChain?"*  
**Response:** *"LangChain is a framework for building applications with large language models (LLMs) through composability."*

#### Question:  
*"Summarize the benefits of using open-source language models."*  
**Response:** *"Open-source models provide transparency, flexibility, and control, ensuring data security and reducing dependency on proprietary solutions."*

---

## 📚 Use Cases
- **Information Retrieval**: Get instant answers on a wide range of topics.
- **Educational Demonstration**: Learn how to build and deploy a chatbot using LangChain and open-source models.
- **Rapid Prototyping**: Quickly prototype conversational AI apps with customizable settings.
- **Data Tracking and Analysis**: Use Langsmith to monitor interactions for better performance insights.

---

## 🧩 Customization
- **Change the Language Model**: Modify the Ollama instance to use different open-source models.
- **Enhance Prompt Engineering**: Adjust the prompt template to better suit your use case.
- **Integrate New APIs**: Add external APIs for domain-specific information retrieval.

---

## 🛡️ Security Notes
- Do **not** hard-code API keys in the code. Always use environment variables.
- Avoid exposing sensitive data in logs or during debugging.
