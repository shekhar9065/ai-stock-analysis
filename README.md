# 📈 AI-Powered Weekly Stock Analysis Workflow

Get comprehensive, data-driven stock insights delivered straight to your inbox—every week!  
This workflow combines technical analysis, market sentiment, and AI-powered pattern detection  
to provide actionable investment insights.

---

## 🚀 Overview

This automated workflow performs weekly analysis on selected stocks using a combination of financial data, technical indicators, and sentiment analysis. You’ll receive a fully styled, responsive HTML email in **Hebrew** (including RTL layout) with detailed stock recommendations and insights.

### 🔍 Key Features

- **Multi-source Data Aggregation**  
  Retrieves stock data from:
  - Chart-img API
  - Twelve Data API
  - Alpha Vantage API

- **Advanced Technical Analysis**  
  Calculates indicators such as:
  - RSI (Relative Strength Index)
  - MACD (Moving Average Convergence Divergence)
  - Bollinger Bands
  - Resistance & Support Levels

- **Sentiment Analysis**  
  Scans financial news from Alpha Vantage to assess market sentiment.

- **AI-Powered Pattern Recognition**  
  Utilizes OpenAI’s GPT-4o to identify:
  - Trading opportunities
  - Market trends
  - Technical pattern interpretations

- **Automated HTML Email Delivery**  
  Sends fully formatted, responsive HTML reports in **Hebrew RTL layout** via email on a weekly basis.

---

## 🧰 Setup Instructions

### ⏱️ Estimated Setup Time
**~15 minutes**

### 🔐 Required API Credentials

You will need:

- OpenAI API Key — [Get one](https://platform.openai.com/)
- Chart-img API Key — [Sign up](https://chart-img.com)
- Twelve Data API Key — [Sign up](https://twelvedata.com)
- Alpha Vantage API Key — [Sign up](https://www.alphavantage.co/support/#api-key)
- SMTP Email Credentials (e.g., Gmail, Outlook)

---

### 🔧 Installation Steps

1. **Import the Template**  
   Import this workflow into your [n8n](https://n8n.io) instance.

2. **Set Credentials**  
   Navigate to the **Credentials** tab in n8n and enter:
   - OpenAI API key
   - Chart-img API key
   - Twelve Data API key
   - Alpha Vantage API key

3. **Configure Email (SMTP) Node**  
   In the SMTP node, set:
   - `Host`: `smtp.gmail.com` (or your email provider)
   - `Port`: `465` or `587`
   - `Username`: your email address
   - `Password`: an app-specific password or login credential

4. **Activate the Workflow**  
   Turn on the workflow to enable weekly execution.

5. **Complete Input Form**  
   Provide stock symbols and any custom settings as needed.

6. **Check Your Inbox**  
   Your report will arrive weekly! *(Check your Spam folder if you don’t see it.)*

---

## ⚠️ Disclaimer

This report is generated automatically using AI and external data sources.  
It **does not constitute investment advice or recommendations**.  
Please consult a **licensed investment advisor** before making financial decisions.

---

## 👤 Who Is This For?

- 🧑‍💼 Investors seeking data-backed insights  
- 💹 Traders analyzing technical indicators  
- 📊 Financial analysts automating research

---

## 📩 Questions or Feedback?

Contributions and issues are welcome! Feel free to [open an issue](#) or submit a pull request.

---

**Enjoy smarter investing with AI-powered insights!**
