# Ai-agent
🧠 AI-Powered Scientific Study Assistant
An intelligent multi-agent system that helps users study scientific topics by generating personalized reports based on user-defined topic and difficulty level. The system dynamically performs web searches, extracts high-quality information, and generates a concise, level-appropriate report with reference links — all wrapped in a downloadable PDF.

## 📌 Features
🔍 Input: Topic and Knowledge Level (e.g., Beginner, Intermediate, Expert)

🤖 Multi-agent architecture powered by Crew AI

🧠 Uses Gemini LLM to understand user needs and generate educational reports

🌐 Live web search via Tavily API

🕸️ Smart web scraping using ScrapeGraph AI

📄 Generates a clean HTML report and converts it to PDF using pdfkit

## 🚀 How It Works
The system is composed of four cooperative agents:

| Agent Role               | Description                                                                             |
| ------------------------ | --------------------------------------------------------------------------------------  |
| **1. Keyword Extractor** | Uses Gemini LLMAnalyzes the topic and level input to generate focused search queries.   |
| **2. Web Search Agent**  | Uses Tavily API to search the web for relevant, up-to-date resources.                   |
| **3. Web Scraper**       | Extracts structured content from top sources using ScrapeGraph AI.                      |
| **4. Report Generator**  | Uses Gemini LLM to write a comprehensive and readable report with links.                |


## 🛠️ Tech Stack
| Tool               | Purpose                                           |
| ------------------ | ------------------------------------------------- |
| **Python**         | Core programming language                         |
| **Crew AI**        | Multi-agent orchestration and task flow           |
| **Gemini**         | Large Language Model (LLM) for content generation |
| **Tavily API**     | Real-time web search                              |
| **ScrapeGraph AI** | Semantic scraping of online sources               |
| **pdfkit**         | HTML-to-PDF conversion                            |



## 📎 Example Output
Input:
-- Topic: text classification using NLP

--  Level: Beginner

Output:

-- 3–5 page PDF with:

-- Abstract

-- Introduction

-- Findings

-- Analysis

-- Conclusion

-- Recommendation

Curated links to original sources

## FlowChart 
![Editor _ Mermaid Chart-2025-05-29-040509](https://github.com/user-attachments/assets/3e9b3a7b-b34b-49ff-abd1-da15714703d9)



## 🙋‍♀️ Author
Mena Allah Ahmed — Data Scientist & AI Developer

Feel free to connect or ask questions!
