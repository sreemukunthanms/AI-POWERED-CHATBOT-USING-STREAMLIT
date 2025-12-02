#  🤖 AI-Powered Chatbot Using Streamlit

An intelligent chatbot application built using Streamlit as the user interface and Ollama’s LLaMA Large Language Model for generating natural language responses. The chatbot enables users to interact smoothly and receive accurate, conversational answers to their queries. 
 
 #  📌 Project Overview

This project integrates a modern LLM-based backend and an interactive web UI to deliver a smart conversational experience.
The chatbot uses:

Streamlit for front-end UI

Ollama for running LLaMA3.1 locally

LangChain for prompt management

StrOutputParser for clean output extraction

It aims to make AI interactions accessible, intuitive, and scalable across use cases like customer support, education, and information retrieval. 


# 🎯 Features  
Feature	Description  
💬 User-friendly UI	Streamlit-based clean chatbot interface  
🧠 LLaMA-powered responses	Intelligent AI understanding and reply generation  
🔄 Real-time interaction	Instant output on each user prompt  
🔌 Extendable Architecture	Can integrate with APIs, memory, domain expertise  
📈 Structured Data Flow	Query → Processing → Response model   
  


# 🏗 System Design

The system includes the following core entities:

User Profile

Queries & Responses

Chatbot Model Instance

Interaction Sessions
Descriptions based on ER diagram and database design from pages 8–9. 



# 📌 ER Diagram (simplified representation)

User → submits → Query → processed by → Chatbot → generates → Response  
User → engages in → Interaction Session  
User → provides → Feedback  

# 🧩 Tech Stack
Component	Technology  
LLM	Ollama — LLaMA3.1  
Frontend UI	Streamlit  
Prompt Orchestration	LangChain  
Parsing	StrOutputParser  
Language	Python 3.8+  

# 📦 Installation & Setup  


1. Install dependencies
pip install -r requirements.txt

2.Ensure Ollama is installed and running

Download + setup from:
https://ollama.ai/

Pull the model used in project:

ollama pull llama3.1

3. Run the chatbot
streamlit run chatbot.py

# 🧠 Code Overview

✔ Uses a chain: Prompt → LLM → Output Parser    
✔ Triggered when the user submits a query  
✔ Response appears instantly in UI  

Refer to complete code in: chatbot.py  
(Explained in detail on page 7 of your report)   


#  📌 Results

Fully functional chatbot tested successfully

Produces accurate responses for general knowledge queries

Simple interface allows instant user interaction
Screenshots included in report pages 10–11. 



📚 References

1️⃣ Streamlit Docs — https://docs.streamlit.io

2️⃣ LangChain Docs — https://langchain.readthedocs.io

3️⃣ Python Docs — https://docs.python.org/3

4️⃣ Ollama Guide — https://ollama.ai/




# 🏅 Credits
  
👨‍💻 Developed by: Sree  
📍 AI-Powered Chatbot Internship Project — Blend Vidya EdTech, Bengaluru
(Approved by AICTE, New Delhi) 

