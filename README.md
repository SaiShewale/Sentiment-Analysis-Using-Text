# 📊 Sentiment Analysis Using Text (n8n + DeepSeek + Google Sheets)

An AI-powered workflow built on n8n that performs sentiment analysis, emotional tone detection, intent recognition, and bias analysis on any incoming text message. Results are stored automatically in categorized Google Sheets based on sentiment.

## 🚀 Features

- 🔄 Real-time trigger on chat message
- 🧠 DeepSeek-powered AI analysis using LangChain:
  - Emotion classification (Positive, Negative, Neutral, Mixed)
  - Intent & tone detection (e.g., request, feedback, neutral, aggressive)
  - Bias detection (gender, political, racial, cultural)
- 📊 Smart classification using AI text classifier
- 📝 Summary generator that condenses multi-agent outputs
- 📤 Sentiment-based Google Sheet logging (Positive / Neutral / Negative)


## 🛠 Tech Stack

- 🧩 **n8n** - Workflow automation tool
- 🧠 **LangChain** - Chain AI agents for natural language tasks
- 🤖 **DeepSeek API** - Large Language Model for inference
- 📊 **Google Sheets API** - Storing sentiment outputs
- 📄 JSON-based dynamic prompts with LangChain
