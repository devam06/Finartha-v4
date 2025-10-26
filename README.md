# FinArtha 💸  
**Your AI-Powered Indian Financial Buddy**  

FinArtha is a conversational financial assistant built to simplify money management for Indian users.  
It combines AI-powered insights, real-time stock data, and an intuitive chat-first interface to make finance **simple, contextual, and personalized**. 


Pitch deck for FinArtha:
https://pitch.com/v/finartha-r8258q


---

## 🚀 Team African Embassy
- **Kanchi Aditya** – 22K91A6674  
- **Devam Dubey** – 22K91A6638   

---

## 📖 Project Overview  

Managing finances is often tedious, especially when tools are not built for the Indian context.  
FinArtha solves this problem by providing:  
- A **conversational finance buddy**  
- Real-time budgeting and expense tracking  
- Income forecasting & visualizations  
- Indian stock market integration (NSE/BSE)  
- Tax-saving tips and personalized recommendations  

---

## 🛠️ Tech Stack  

- **Frontend**: Streamlit (chat-first UI, dynamic sidebar, light/dark mode)  
- **AI Backend**: Gemini 1.5 + Granite 3.3 (via Hugging Face Spaces)  
- **Data**: yFinance for NSE/BSE stock data  
- **Visualization**: Pandas + Matplotlib  

---

## ⚡ Features  

- 💸 **Live Budgeting** – Track expenses dynamically  
- 📈 **Income Forecasting** – AI-driven predictions  
- 📊 **Visualization** – Graphs for spendings, savings, and trends  
- 📉 **Stock Market Integration** – Real-time quotes from Indian markets  
- 🧾 **Tax-Saving Insights** – Contextual to Indian financial system  
- 🔄 **Conversational UI** – Simple chat-based interactions  

---

## 🔑 API Key Integration  

HF Spaces for granite : https://huggingface.co/spaces/ad1xya/granite-api

We integrated our API key using **Streamlit’s `secrets.toml`** file.  
This allows secure access to the AI models and prevents direct exposure of keys in the codebase.  

```toml
# .streamlit/secrets.toml
[api_keys]
GOOGLE_API_KEY = "your_api_key_here"




