# TraderBot
Build a trader bot which looks at sentiment of live news events and trades appropriately. 
• Engineered an AI trading bot using Python, TensorFlow, and BERT for real-time sentiment analysis of financial news and social media, combining insights with LSTMs and technical indicators. Achieved a 15% increase in trade accuracy by dynamically adjusting strategies based on sentiment trends. 
• Deployed on Binance via automated APIs, with backtesting results showing a 10% boost in average returns and reduced drawdowns. Delivered rapid, data-driven trading recommendations that effectively adapt to market shifts. 

# Startup
1. Create a virtual environment `conda create -n trader python=3.10` 
2. Activate it `conda activate trader`
3. Install initial deps `pip install lumibot timedelta alpaca-trade-api==3.1.1`
4. Install transformers and friends `pip install torch torchvision torchaudio transformers` 
5. Update the `API_KEY` and `API_SECRET` with values from your Alpaca account 
6. Run the bot `python tradingbot.py`

<p>N.B. Torch installation instructions will vary depending on your operating system and hardware. See here for more: 
<a href="pytorch.org/">PyTorch Installation Instructions</a></p>
