# Autonomous Financial Research Analyst

A LangChain/LangGraph agent that automates investment research by gathering real-time financial data, analyzing sentiment, and synthesizing multi-source insights — replacing the manual analyst workflow.

## What it does

Investment analysts spend 60–70% of their time on data gathering rather than analysis. This agent automates that pipeline:

- **Real-time data retrieval** — stock prices, financial news, analyst reports from live sources
- **Sentiment analysis** — classifies news and report tone per company
- **Charter-driven autonomy** — goal, tools, and constraints defined as an agent charter (proactiveness, actuators, reactivity)
- **Multi-source synthesis** — aggregates signals into a structured research output
- **Scalable** — designed to analyze multiple companies concurrently

## Architecture

```
Research Charter → Data Retrieval Agents → Sentiment Analyzer → Synthesis Agent → Report
```

Implements the four core agentic design principles: **Proactiveness**, **Actuators**, **Autonomy**, and **Reactivity**.

## Stack

- LangChain / LangGraph
- OpenAI API (gpt-4o-mini)
- Python 3.10+

## Setup

```bash
pip install -r requirements.txt
cp .env.example .env
# Add your API keys to .env
jupyter notebook autonomous_financial_analyst.ipynb
```

## Environment variables

See `.env.example`.
