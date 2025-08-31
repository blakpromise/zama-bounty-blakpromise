# zama-bounty-blakpromise
Overview This repository is my submission for the **Zama Bounty Program (Season 9)**.   The goal is to build a **Dollar Cost Averaging (DCA) trading bot** that leverages **Fully Homomorphic Encryption (FHE)** to protect user data and strategy parameters while executing trades.
Features
- Implements a configurable DCA strategy (asset, amount, frequency).  
- Sensitive inputs (amounts, time intervals) are encrypted using Zama’s FHE library.  
- The bot performs computations on encrypted values, ensuring privacy is preserved.  
- Modular design so it can be extended with other strategies in the future.  
Install dependencies:
pip install -r requirements.txt
Configure your strategy in config.json:
  "asset": "ETH",
  "amount": 100,
  "frequency": "weekly"
Run the bot:
python main.py



