# Multi-Agent-AI-Business-Insights-System
Overview

The Multi-Agent AI Business Insights System is an intelligent data analytics pipeline that automates end-to-end business data analysis using Python and OpenRouter LLMs. It processes raw datasets (CSV/Excel), performs data cleaning, exploratory data analysis (EDA), KPI computation, and generates AI-powered business insights and final reports.
This project simulates a real-world AI-driven Business Intelligence system using multiple AI agents.

## Features
Data Cleaning Agent
- Handles missing values
- Removes duplicate records
- Standardizes data for analysis
EDA Agent (Exploratory Data Analysis)
- Dataset overview (shape, columns, types)
- Statistical summaries
- Correlation analysis
- Pattern detection
KPI Agent
- Revenue calculation
- Customer analysis
- Sales performance metrics
- Business growth indicators
Insight Generator Agent (LLM Powered)
- Converts raw data into business insights
- Detects risks and opportunities
- Explains trends 
Report Generator Agent
- Combines outputs from all agents
- Generates structured business report

## System Architecture
Input Data (CSV / Excel)
        ↓
Data Cleaning Agent
        ↓
EDA Agent
        ↓
KPI Agent
        ↓
AI Insight Agent (OpenRouter LLM)
        ↓
Report Generator Agent
        ↓
Final Business Report
## Tech Stack
Python 
Pandas 
Requests 
OpenRouter API 
LLM Models (GPT-4o-mini / Mistral / others)

## Project Structure
Multi-Agent-AI-System/
│
├── Multi_Agent_AI.py        # Main pipeline script
├── data/
│   └── shopping_trends.csv  # Sample dataset
├── final_report.txt         # Generated output report
├── requirements.txt
└── README.md

## Installation 
- Install dependencies
pip install pandas requests openai
- Add OpenRouter API Key

Replace in code:

API_KEY = "your_openrouter_api_key"
