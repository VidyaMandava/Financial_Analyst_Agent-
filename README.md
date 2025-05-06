# Financial Analyst Agent

A comprehensive AI-powered financial analysis system that helps investors make data-driven decisions by providing up-to-date market information, stock analysis, and investment insights.

## Overview

This project implements a Tool-Use Agentic AI System that functions as a Financial Analyst and Advisor. The system can:

- Analyze specific stocks and provide detailed metrics (price, fundamentals, news)
- Provide general market insights and trends
- Identify potentially valuable investment opportunities
- Present data in a clear, professional format

## Architecture

The system is built using:

- **LangGraph**: For orchestrating the agent's workflow
- **OpenAI GPT-4o-mini**: As the core reasoning engine
- **OpenBB Platform**: For accessing financial data

The architecture follows a directed graph pattern where:
1. User input is processed and validated
2. Appropriate financial tools are selected and executed
3. Data is retrieved from reliable sources
4. A comprehensive response is generated

## Features

- **Stock Symbol Lookup**: Find ticker symbols for company names
- **Price Metrics**: Get current prices, historical data, and performance metrics
- **Fundamental Analysis**: Access key ratios and financial indicators
- **News Integration**: Get the latest news related to specific stocks
- **Market Overview**: View most active stocks, top gainers, and losers
- **Web Search**: Find additional information when needed

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/financial-analyst-agent.git
cd financial-analyst-agent

# Install dependencies
pip install -r requirements.txt
