#  AI Hiring Assistant - AWS Bedrock & LangChain

This project is an **AI-powered Hiring Assistant** that conducts **technical interviews** for candidates based on their skills and experience. It uses **AWS Bedrock**, **LangChain**, **ChromaDB**, and **Streamlit** to generate and evaluate interview questions dynamically.


##  Features

- **Candidate Information Form:** Collects name, email, phone, experience, and desired role.
- **Dynamic Question Generation:** Uses Mistral LLM to generate interview questions based on the candidate's tech stack.
- **Conversational Memory:** Maintains chat history to ensure contextual responses.
- **Real-time Interview Evaluation:** Displays progress and collects answers from the candidate.
- **Clean & Modern UI:** Built using **Streamlit**, with enhanced styling.



##  Project Setup

### 1️⃣ Prerequisites

- Python (3.10)
- AWS Account with **Bedrock enabled**
- Streamlit
- Boto3
- LangChain
- ChromaDB

### 2️⃣ Install Dependencies:

```bash
pip install streamlit boto3 langchain-aws langchain-community chromadb
```

### Install AWS CLI:
```
https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
```
### Add Credential on AWD CLI:
```
aws configure 
```

### To run streamlit app:
```
streamlit run main.py
```