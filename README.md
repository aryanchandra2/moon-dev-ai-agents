AI Trading Agents
Vision
AI agents are clearly the future and the entire workforce will be replaced or at least using AI agents. While I am a quant and building agents for algo trading I will be contributing to all different types of AI agent flows and placing all of the agents here for free, 100% open sourced because I believe code is the great equalizer and we have never seen a regime shift like this so I need to get this code to the people.
Feel free to join our discord if you believe AI agents will be integrated into the workforce.
Live Agents

Trading Agent (trading_agent.py): Example agent that analyzes token data via LLM to make basic trade decisions
Strategy Agent (strategy_agent.py): Manages and executes trading strategies placed in the strategies folder
Risk Agent (risk_agent.py): Monitors and manages portfolio risk, enforcing position limits and PnL thresholds
Copy Agent (copy_agent.py): Monitors copy bot for potential trades
Whale Agent (whale_agent.py): Monitors whale activity and announces when a whale enters the market
Sentiment Agent (sentiment_agent.py): Analyzes Twitter sentiment for crypto tokens with voice announcements
Listing Arbitrage Agent (listingarb_agent.py): Identifies promising Solana tokens on CoinGecko before they reach major exchanges like Binance and Coinbase, using parallel AI analysis for technical and fundamental insights
Focus Agent (focus_agent.py): Randomly samples audio during coding sessions to maintain productivity, providing focus scores and voice alerts when focus drops (~$10/month, perfect for voice-to-code workflows)
Funding Agent (funding_agent.py): Monitors funding rates across exchanges and uses AI to analyze opportunities, providing voice alerts for extreme funding situations with technical context
Liquidation Agent (liquidation_agent.py): Tracks liquidation events with configurable time windows (15min/1hr/4hr), providing AI analysis and voice alerts for significant liquidation spikes
Chart Agent (chartanalysis_agent.py): Looks at any crypto chart and then analyzes it with AI to make a buy/sell/nothing recommendation
Funding Rate Arbitrage Agent (fundingarb_agent.py): Tracks the funding rate on Hyperliquid to find funding rate arbitrage opportunities between HL and Solana
RBI Agent (rbi_agent.py): Uses DeepSeek to research trading strategies based on the YouTube video, PDF, or words you give it, then sends to its AI friend who codes out the backtest
Twitter Agent (tweet_agent.py): Takes in text and creates tweets using DeepSeek or other models
Video Agent (video_agent.py): Takes in text to create videos by creating audio snippets using ElevenLabs and combining with raw video footage
New or Top Tokens Agent (new_or_top_agent.py): Looks at the new tokens and the top tokens from CoinGecko API
Chat Agent (chat_agent.py): Monitors YouTube live stream chat, moderates & responds to known questions
Clips Agent (clips_agent.py): Helps clip long videos into shorter ones for upload to YouTube
Phone Agent (phone_agent.py): AI agent that can take phone calls for you
Sniper Agent (sniper_agent.py): Watches for new Solana token launches and will then analyze them and maybe snipe
Transaction Agent (tx_agent.py): Watches transactions made by my copy list and then prints them out with an optional auto tab open
Solana Agent (solana_agent.py): Looks at the sniper agent and the transaction agent to select which memes may be interesting

IMPORTANT: This is an experimental project. There are NO guarantees of profitability. Trading involves substantial risk of loss.
Critical Disclaimers
There is no token associated with this project and there never will be. Any token launched is not affiliated with this project, I will never DM you. Be careful. Don't send funds anywhere.
PLEASE READ CAREFULLY:

This is an experimental research project, NOT a trading system
There are NO plug-and-play solutions for guaranteed profits
We do NOT provide trading strategies
Success depends entirely on YOUR:
Trading strategy
Risk management
Market research
Testing and validation
Overall trading approach


NO AI agent can guarantee profitable trading
You MUST develop and validate your own trading approach
Trading involves substantial risk of loss
Past performance does not indicate future results

Shipped Features

2/9: Created a Solana agent to parse through new Solana launches and the copy bot list and applies filters to them before picking their top picks and opening in my browser
2/8: Created the sniper agent that watches for new Solana token launches and will then analyze them and maybe snipe
2/7: Created a phone call agent that can be used for customer support, onboarding, or sales with a Twilio number
2/6: Added Ollama to allow for local DeepSeek R1, Gemma, and LLaMA 3.2 and any other Ollama or Hugging Face model
2/5: Clips agent to make money completed by clipping my streams into short digestible videos /clips_agent.py
2/4: Code running agent is complete and put in the agents folder
2/3: Self-executing now works, game changer
2/1: Working on getting a self-executing AI agent to work with a debugger AI to autonomously improve my code and trading backtests
1/31: Added o3-mini to the model factory
1/31: Updated the chat agent, this is the agent I will use for all live streams to manage chat with AI
1/30: Created the chat agent to manage the live stream chat
1/30: Groq added & Gemini added. New interface for handling the ever-growing amount of AIs we have access to. src/models/README.md
1/29: DeepSeek hosted locally on Lambda Labs, see the API script if you want to launch your own src/scripts/deepseek_api.py. How to call it src/scripts/deepseek_local_call.py
1/27: Built a tweet agent and video agent
1/23: Built an RBI agent that codes backtests based on trading strategy videos, PDFs, or words
1/20: Built the funding rate arbitrage trading agent to announce when there is a funding rate arbitrage between Hyperliquid tokens and spot Solana tokens. Later we can update this to place the trades
1/17: Built Chuck the chart analysis agent that reads in any crypto chart and then analyzes it to get a buy/sell/nothing recommendation
1/16: Built Luna the Liquidation Agent with configurable time windows (15min/1hr/4hr)
Updated Whale Agent to use new OI data format
Fixed Funding Agent to handle new API structure
All agents now using consistent API v2
1/15: Released comprehensive API access with detailed documentation
Historical liquidation data endpoints
Real-time funding rate monitoring
New Solana token launch tracking
Detailed & combined ETH/BTC open interest historical data
CopyBot data access for reference (follow list & their recent transactions)
1/14: Added Funding Rate Agent that monitors and announces extreme funding rates
Uses AI to analyze funding opportunities with technical context
Provides voice announcements for significant funding events
Tracks historical funding data for better analysis
1/12: Built a Listing Arbitrage Agent that identifies promising Solana tokens before they reach major exchanges
Uses parallel AI analysis with technical and fundamental agents
Filters by market cap and volume criteria
Saves analysis results and buy recommendations to CSV
1/10: Built a CoinGecko agent conversation between 2 AI agents and all of CoinGecko's data
1/10: Added a focus agent that will take random samples of my voice to ensure I'm always locked in. My KPI is 200 AI uses per day which is hard when I yap so this is the solution
1/9: Added Sentiment Analysis Agent with voice announcements and historical tracking
Monitors Twitter sentiment for major tokens
Tracks sentiment changes over time
Announces significant sentiment shifts
Updated the whale agent as well to work better
1/8: Added minimum balance protection to Risk Agent with configurable AI consultation
Completed CopyBot portfolio analyzer with position sizing
V0 of the whale agent launched
1/7: CopyBot Agent: Added AI agent to analyze CopyBot portfolio and decide on whether it should take a position on their account
1/6: Market Data API: Added comprehensive API for liquidations, funding rates, open interest, and CopyBot data
1/5: Created a documentation training video with a full walkthrough of this GitHub
1/4: strategy_agent.py: An AI agent that has last say on any strategy placed in strategies folder
1/3: risk_agent.py: Built out an AI agent to manage risk
1/2: trading_agent.py: Built the first trading agent
1/1: First lines of code written

Quick Start Guide
Python 3.10.9 is what was used during dev

Star the Repo
Click the star button to save it to your GitHub favorites


Fork the Repo
Fork to your GitHub account to get your own copy
This lets you make changes and track updates


Open in Your IDE
Clone to your local machine
Recommended: Use Cursor or Windsurfer for AI-enabled coding


Set Environment Variables
Check .env.example for required variables
Create a copy of above and name it .env file with your keys:
Anthropic API key
Other trading API keys


Never commit or share your API keys!


Customize Agent Prompts
Navigate to /agents folder
Modify LLM prompts to fit your needs
Each agent has configurable parameters


Implement Your Strategies
Add your strategies to /strategies folder
Remember: Out-of-box code is NOT profitable
Thorough testing required before live trading


Run the System
Execute via main.py
Toggle agents on/off as needed
Monitor logs for performance




Built by Aryan Chandra
Detailed Disclaimer
The content presented is for educational and informational purposes only and does not constitute financial advice. All trading involves risk and may not be suitable for all investors. You should carefully consider your investment objectives, level of experience, and risk appetite before investing.
Past performance is not indicative of future results. There is no guarantee that any trading strategy or algorithm discussed will result in profits or will not incur losses.
CFTC Disclaimer: Commodity Futures Trading Commission (CFTC) regulations require disclosure of the risks associated with trading commodities and derivatives. There is a substantial risk of loss in trading and investing.
I am not a licensed financial advisor or a registered broker-dealer. Content & code is based on personal research perspectives and should not be relied upon as a guarantee of success in trading.
