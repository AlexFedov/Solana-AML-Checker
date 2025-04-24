A lightweight Python tool to detect suspicious transactions on the Solana blockchain. For educational and demo purposes.

Telegram Bot
License: MIT

🌟 Repository Description
This demo showcases a simplified Anti-Money Laundering (AML) checker for Solana transactions. It includes mock risk analysis (blacklists, large transfers) and serves as an educational example. The full-featured version is available via @AMLSol_bot on Telegram.

🚀 Features
✅ Basic address blacklisting

✅ Large transfer detection (>1000 SOL)

✅ Risk scoring (Low/Medium/High)

🧩 Modular design (easy to extend with real APIs)

📦 Installation
bash
git clone https://github.com/yourusername/Solana-AML-Checker.git
cd solana-aml-checker-demo
pip install requests  # Only dependency for this demo
🛠 Usage
Run the demo with a test transaction:

python
python aml_checker.py
Output Example:

plaintext
🔎 Transaction Risk: HIGH  
📌 Reason: Blacklisted address involved
🔗 Integrations (Potential)
Replace mock data with Solana RPC (solana-py).

Add Chainalysis/TRM Labs API hooks (for real-world AML data).

📜 Disclaimer
This is a proof-of-concept demo. For production-grade Solana AML checks, use:
👉 [@AMLSol_bot](https://t.me/AMLSol_bot) (Telegram bot with real-time analysis)

💡 How to Contribute
Fork the repository.

Add enhancements (e.g., Solana RPC integration).

Submit a PR!


📌 Keywords
#Solana #AML #Blockchain #Crypto #Security #TelegramBot #Python #Web3
