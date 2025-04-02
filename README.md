#  AI-Powered Stock Comparison Tool

## Live Demo  
Try the AI Finance Bot here: **[Live Demo](https://ai-finance-chatbot1.streamlit.app/)**

## Overview
The AI Stock Comparison Tool is a financial analysis platform designed to consolidate stock-related data into a single interface, providing investors with a seamless and efficient way to compare multiple stocks. By integrating real-time stock market data, fundamental analysis, and interactive visualizations, this tool enables data-driven investment decision-making. 

## Technologies Used

The AI Stock Comparison Tool is built using a combination of modern technologies to ensure real-time data retrieval, AI-powered insights, and an interactive user experience. The following technologies are utilized in the development of the project:

1.	**Programming Language:** Python – Used for backend logic, API integration, and AI chatbot interaction.
2.	**AI Model:** Google Gemini 2.0 – Powers the AI chatbot for stock-related queries and insights.
3.	**APIs:**
    - **Google Gemini API** – Provides AI-driven financial analysis and responses.
    - **Yahoo Finance API** – Fetches real-time stock prices, historical data, and financial metrics.
    - **Finnhub API** – Supplies market trends, financial statements, and company fundamentals.
4.	**Framework:** Streamlit – Used to build the interactive user interface for stock comparison and visualization.

## Features
- **Real-time stock data:** Fetches stock prices, historical performance, and key financial indicators via financial APIs.
- **AI-powered insights:** Utilizes an AI chatbot to answer queries, provide stock analysis, and generate investment insights.
- **Comparative stock analysis:** Evaluates multiple stocks based on financial fundamentals, valuation metrics, and performance trends.
- **Interactive charts:** Displays historical stock data and market trends for easy visualization.
- **News integration:** Aggregates financial news updates related to selected stocks.  

## Project Structure  
```
AI-Finance-Bot/
│── .env                     # Environment variables for API keys  
│── Finance-App.py            # Main Streamlit application  
│── requirements.txt          # Dependencies  
│── README.md                
```  

## About the AI Model  

The AI Stock Comparison Tool leverages **Google Gemini 2.0 Flash**, a cutting-edge language model optimized for financial analysis. It integrates real-time data retrieval and multimodal processing, enabling dynamic stock comparisons based on fundamental metrics, market trends, and AI-driven insights. With advanced reasoning and streaming capabilities, the model ensures fast, accurate, and context-aware financial recommendations.

## Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Anirudh-sys/AI-Finance-ChatBot.git
   cd AI-Finance-Bot-main
   ```  
2. **Create a virtual environment (optional but recommended)**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```  
3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```  
4. **Run the Streamlit app**  
   ```bash
   streamlit run Finance-App.py
   ```  
## Future Enhancements

**1.Advanced AI Capabilities:**

**AI Sentiment Analysis** – Analyze stock-related news and earnings reports using Natural Language Processing (NLP) to determine market sentiment (positive, neutral, or negative).

**Personalized AI Recommendations** – Allow users to set investment preferences (e.g., risk tolerance, goals) and receive customized stock recommendations from the AI chatbot.

**2.Real-Time Market Monitoring & Alerts:**

**Stock Price Alerts** – Send real-time notifications when a stock reaches a predefined price level, helping users track opportunities.

**3.Expanded Data Integration:**

**More Financial Metrics** – Include additional technical indicators like ROE, ROA, Debt-to-Equity Ratio, RSI, and Moving Averages to enhance stock analysis.
**Global Market Coverage** – Expand the tool to support international stock exchanges, including NASDAQ, London Stock Exchange, and Tokyo Stock Exchange.


