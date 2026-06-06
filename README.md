# ai-market-update-agent
An automated AI-powered market briefing system built using n8n.

## Overview
This workflow:

- Retrieves financial news from Alpha Vantage
- Fetches SPY and QQQ market data
- Generates market context
- Uses OpenAI to create concise market briefings
- Delivers results automatically through Telegram

## Workflow architecture 
Schedule Trigger
→ News Feed
→ Market Data (SPY + QQQ)
→ Data Formatting
→ Market Context Generation
→ AI Analysis
→ Telegram Delivery

## Tech Stack
- n8n
- OpenAI API
- Alpha Vantage API
- Telegram Bot API
- JavaScript

## Features
- Automated daily market briefings
- AI-powered financial news analysis
- Market context integration
- Telegram notifications
- Modular workflow design

## Future Improvements
- Bitcoin and crypto tracking
- VIX integration
- Historical sentiment database
- Portfolio watchlists
- Web dashboard
- Additional market indicators

## Example Output
Macro
AI & Tech
Markets
Risks

Generated automatically each day using live market data and AI analysis.
