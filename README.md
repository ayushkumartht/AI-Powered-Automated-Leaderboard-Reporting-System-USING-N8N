# AI-Powered-Automated-Leaderboard-Reporting-System-USING-N8N
An intelligent AI-driven automated workflow built with n8n that generates daily leaderboard reports with insights and delivers them via Telegram, Email, and Google Drive. School Exhibition Project demonstrating automation and AI integration.


# AI-Powered Automated Leaderboard Reporting System

## 📋 Project Description

This project is an **AI-driven automated workflow** developed using **n8n**, a powerful workflow automation tool. The system automatically fetches data, analyzes it using Artificial Intelligence, generates insightful leaderboard reports, and delivers them through multiple channels without any manual intervention.

The workflow fetches statistics of top creators and workflows, processes the data, uses AI models (OpenAI + Google Gemini) to generate meaningful insights and trends, creates professional Markdown reports, stores them in Google Drive, and sends notifications via Telegram and Email.

This project demonstrates the practical implementation of automation, intelligent data processing, and AI integration in real-world reporting systems.

## ✨ Key Features

- Fully automated daily scheduled execution
- Dual AI integration with fallback mechanism (OpenAI GPT-4o-mini + Google Gemini)
- Intelligent analysis and insight generation using LLM
- Automatic creation of well-structured Markdown reports
- Multi-channel delivery system (Telegram, Gmail, and Google Drive)
- Robust data processing pipeline with sorting, filtering, and merging
- Comprehensive error handling for reliability

## 🛠️ Technologies Used

- **n8n** - Workflow Automation Platform
- **OpenAI** (GPT-4o-mini)
- **Google Gemini** (Flash Experimental)
- **Google Drive API**
- **Gmail API**
- **Telegram Bot API**
- Advanced n8n nodes: HTTP Request, AI Agent, SplitOut, Sort, Merge, ConvertToFile, Markdown

## 📁 Project Structure

- `n8n-ai-leaderboard-workflow.json` → Main n8n Workflow File
- `README.md` → Project Documentation

## 🚀 How to Setup and Run

1. Open n8n (Cloud or Self-hosted)
2. Create a new workflow
3. Import the workflow file (`n8n-ai-leaderboard-workflow.json`)
4. Configure the following credentials:
   - OpenAI API Key
   - Google Gemini API Key
   - Google Drive OAuth2
   - Gmail OAuth2
   - Telegram Bot Token & Chat ID
5. Set the Schedule Trigger according to your requirement
6. Activate the workflow

## 📊 Workflow Functionality

The system performs the following steps automatically:
1. Fetches latest statistics using HTTP requests
2. Parses and processes the data
3. Sorts and ranks top creators and workflows
4. Uses AI Agent to generate comprehensive analysis and insights
5. Converts output into professional Markdown format
6. Saves reports to Google Drive
7. Sends formatted reports via Telegram and Email

## 🎯 Objectives

- To understand and implement workflow automation using n8n
- To integrate Artificial Intelligence in automated systems
- To build a complete end-to-end reporting pipeline
- To learn scheduling, error handling, and multi-service integration

## 👨‍💻 About the Developer

- **Name**: Ayush  
- **Program**: B.Tech Computer Science (1st Year)  
- **Institution**: KIET Group of Institutions  
- **Project Type**: n8n Automation Project

## 📈 Future Scope

- Extending support to other domains (YouTube Analytics, E-commerce, Recruitment, Finance)
- Adding PDF report generation with visualizations
- Building a web dashboard for report viewing
- Implementing predictive analytics using AI

---

  
**KIET Group of Institutions**  
**March 2026**
