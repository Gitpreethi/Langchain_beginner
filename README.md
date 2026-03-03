# Langchain_beginner
***
LangChain Practice Repository

This repository contains structured experiments and implementations using LangChain, covering chat models, LLM integrations, embeddings, and prompt engineering concepts.

The project is organised module-wise to separate concerns clearly: chat models, LLMs, embeddings, and prompt templates.

📁 Project Structure
ChatModels/
EmbeddingModels/
LLMs/
prompt/
🔹 ChatModels/

Contains implementations using LangChain's chat model interfaces.

chat_demo.py

Basic chat model integration demonstrating how to:

Initialize a chat model

Send user input

Receive structured responses

chat_demo_gemini.py

Integration with Google Gemini through LangChain.
Covers:

API-based model usage

Chat interaction flow

Response handling

chathf_api.py

Hugging Face hosted an API-based chat model usage.
Includes:

API authentication

Remote inference

Response parsing

chathf_local.py

Local Hugging Face model integration.
Demonstrates:

Loading models locally

Using HuggingFacePipeline

Running inference without external API calls

🔹 EmbeddingModels/

Contains implementations for:

Generating vector embeddings

Understanding how embeddings are used in retrieval

Testing embedding pipelines

Focus:

Text-to-vector transformation

Foundation for RAG systems

🔹 LLMs/
llm_demo.py

Demonstrates usage of standard LLM interfaces in LangChain.
Includes:

Model initialization

Prompt passing

Response generation

Difference between chat models and raw LLMs

🔹 prompt/

Contains experiments related to prompt engineering and template management.

chatbot.py

Basic chatbot implementation using:

Prompt templates

Model invocation

Structured chat interaction

chatprompt_template.py

Demonstrates:

ChatPromptTemplate

Role-based message formatting

Dynamic variable injection

message_placeholder.py

Explores:

MessagesPlaceholder

Maintaining conversation history

Dynamic message insertion

staticprompt.py

Static prompt structure for:

Fixed system + user templates

Controlled generation tasks (e.g., summarization)

template_generate.py

General prompt template experimentation:

Variable-based prompts

Structured generation workflows

chat_history.txt

Stores conversation history for:

Testing context memory

Persistent interaction experiments

🧠 Concepts Covered

Chat Models vs LLMs

Prompt Templates

Role-based Messaging

Hugging Face Local & API Models

Google Gemini Integration

Embeddings

Conversation Memory

Model Invocation Patterns

Streamlit-based Interfaces (where applicable)

🛠 Technologies Used

Python

LangChain

Hugging Face Transformers

Google Generative AI (Gemini)

Streamlit (for UI experiments)

PyTorch

🚀 How to Run

Create virtual environment:

python -m venv venv

Activate:

venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Run any module:

python filename.py

or

streamlit run filename.py
🎯 Purpose of This Repository

Structured experimentation with LangChain

Understanding model interfaces

Comparing API vs local model usage

Building foundation for advanced systems like RAG and AI assistants
