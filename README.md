# 🛒 AI Agent to Answer E-commerce Data Questions

An AI-powered agent that converts **natural language questions** into SQL queries, executes them on a **MySQL database**, and returns **human-readable answers** — with optional **visualizations** and **live-typing** responses.

📌 *Developed as part of a technical interview assignment for a GenAI internship opportunity.*


## 🎯 Objective

The goal of this project is to build a robust AI agent capable of:

- 🧠 Understanding natural language queries  
- 🧾 Translating them into SQL  
- 📊 Querying the database and returning accurate, human-readable responses  
- 📈 (Bonus) Generating graphs for data insights  
- 💬 (Bonus) Simulating real-time interaction using streamed text responses  


## 🗂️ Dataset

This project uses three e-commerce related datasets:

1. **Product-Level Ad Sales and Metrics**  
2. **Product-Level Total Sales and Metrics**  
3. **Product-Level Eligibility Table**


## 🔧 Steps & Implementation

1. **Convert CSV datasets** into **SQL tables** using MySQL.  
2. **Select a local LLM** (Large Language Model) capable of running offline.  
3. **Develop a codebase** to connect:
   - The LLM  
   - The SQL tables  
   - API endpoints for receiving and responding to user questions  
4. **Implement query handling logic**:
   - Understand user questions  
   - Generate and execute SQL queries  
   - Return results in clear, human-readable format  
5. *(Bonus Features)*:
   - Visualize responses for applicable queries using graphs  
   - Stream results with a live-typing effect for enhanced UX

---

## 🚀 Getting Started

To launch the AI chatbot locally: http://127.0.0.1:7865

