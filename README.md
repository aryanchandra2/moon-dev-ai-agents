AI Trading Agents
Overview
I'm a quant building AI agents for algorithmic trading, shared here as free, open-source tools. Code is a great equalizer, and this project aims to make AI-driven trading accessible during this transformative shift.
Agents

Trading Agent (trading_agent.py): Analyzes token data via LLM for trade decisions.
Strategy Agent (strategy_agent.py): Executes strategies from the strategies folder.
Risk Agent (risk_agent.py): Manages portfolio risk with position and PnL limits.
Copy Agent (copy_agent.py): Tracks copy bot for trade opportunities.
Whale Agent (whale_agent.py): Detects and announces whale market activity.
Sentiment Agent (sentiment_agent.py): Analyzes Twitter sentiment for crypto tokens.
Listing Arbitrage Agent (listingarb_agent.py): Finds promising Solana tokens pre-listing.
Focus Agent (focus_agent.py): Tracks coding productivity with audio sampling (~$10/month).
Funding Agent (funding_agent.py): Monitors funding rates and alerts on opportunities.
Liquidation Agent (liquidation_agent.py): Tracks liquidations with AI analysis.
Chart Agent (chartanalysis_agent.py): Analyzes crypto charts for buy/sell/hold calls.
Funding Rate Arbitrage Agent (fundingarb_agent.py): Finds arbitrage between Hyperliquid and Solana.
RBI Agent (rbi_agent.py): Researches strategies and codes backtests.
Twitter Agent (tweet_agent.py): Creates tweets using DeepSeek or other models.
Video Agent (video_agent.py): Generates videos from text and audio snippets.
New/Top Tokens Agent (new_or_top_agent.py): Analyzes CoinGecko's new/top tokens.
Chat Agent (chat_agent.py): Manages YouTube live stream chat.
Clips Agent (clips_agent.py): Clips long videos into short segments.
Phone Agent (phone_agent.py): Handles calls for support or sales.
Sniper Agent (sniper_agent.py): Analyzes new Solana token launches.
Transaction Agent (tx_agent.py): Tracks copy list transactions.
Solana Agent (solana_agent.py): Identifies interesting meme tokens.

Important: This is experimental. No profitability guaranteed. Trading carries high risk.
Disclaimers

No token is or will be associated with this project. Any claiming affiliation is fraudulent.
This is a research project, not a trading system.
No guaranteed profits or strategies provided.
Success depends on your strategy, risk management, and testing.
Trading involves substantial risk of loss.
Past performance does not predict future results.
I am not a financial advisor or broker-dealer.

Features

2/9: Solana agent filters new launches and copy bot lists, opens top picks.
2/8: Sniper agent analyzes new Solana token launches.
2/7: Phone call agent for support/sales with Twilio.
2/6: Added Ollama for local DeepSeek, Gemma, LLaMA 3.2.
2/5: Clips agent for short video clips.
2/4: Code-running agent completed.
2/3: Self-executing AI agent enabled.
2/1: Built self-executing AI with debugger for code/backtest improvement.
1/31: Added o3-mini; updated chat agent for live streams.
1/30: Created chat agent; added Groq, Gemini to model interface.
1/29: Hosted DeepSeek locally on Lambda Labs.
1/27: Built tweet and video agents.
1/23: RBI agent for strategy research and backtesting.
1/20: Funding rate arbitrage agent for Hyperliquid-Solana.
1/17: Chart analysis agent for buy/sell/hold recommendations.
1/16: Liquidation agent with time windows; updated whale, funding agents.
1/15: Released API for liquidation, funding, Solana, ETH/BTC data.
1/14: Funding rate agent with AI analysis and alerts.
1/12: Listing arbitrage agent for Solana tokens.
1/10: CoinGecko agent; focus agent for productivity tracking.
1/9: Sentiment agent with Twitter tracking; improved whale agent.
1/8: Risk agent with balance protection; CopyBot analyzer.
1/7: CopyBot agent for portfolio decisions.
1/6: Market data API for liquidations, funding, open interest.
1/5: Documentation video with GitHub walkthrough.
1/4: Strategy agent for final strategy approval.
1/3: Risk agent for portfolio management.
1/2: First trading agent built.
1/1: First code written.

Quick Start
Uses Python 3.10.9.

Star and fork the repo to your GitHub.
Clone to your machine; use Cursor or Windsurfer IDE.
Set .env variables (see .env.example): Anthropic, trading API keys. Never share keys.
Customize agent prompts in /agents folder.
Add strategies to /strategies folder; test thoroughly.
Run via main.py; monitor logs.

Built by Aryan Chandra
Disclaimer
For educational purposes only, not financial advice. Trading is risky; consider your objectives and risk tolerance. Past performance does not guarantee future results. CFTC: Trading commodities/derivatives carries substantial risk. I am not a licensed financial advisor or broker-dealer.
