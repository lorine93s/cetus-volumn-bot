# 🚀 SUI Volume Bot (CETUS-DEX)

The **SUI Volume Bot** is an automated trading bot designed to execute **continuous buy and sell swaps** on the **CETUS DEX**. It helps increase **trading volume and maker activity** while optimizing gas fees for maximum efficiency.

### 🔥 Note:
The **original project is written in TypeScript**. This repository contains a **compiled demo version**. For access to the **full version**, please contact me on **Telegram or Twitter**.

---

## 🌟 Key Features
✅ **Automated SUI Distribution** – Distributes SUI to new wallets automatically.<br>
✅ **Endless Buy and Sell Swaps** – Executes continuous transactions to maintain liquidity and trading volume.<br>
✅ **Optimized Gas Fees** – Uses smart fee calculation to keep costs minimal.<br>
✅ **Customizable Trading Parameters** – Allows users to adjust **trade amount, intervals, and wallet distribution**.<br>
✅ **Multi-Wallet Support** – Spreads volume across multiple wallets for enhanced trading impact.<br>
✅ **CETUS DEX Integration** – Fully compatible with CETUS DEX liquidity pools and AMM mechanics.<br>

---

## ⚙️ How It Works
1️⃣ The bot **distributes SUI** among multiple wallets.<br>
2️⃣ It performs **simultaneous buy and sell swaps** to increase volume.<br>
3️⃣ All transactions are **optimized for gas efficiency**.<br>
4️⃣ The bot continuously **monitors trading activity and adjusts parameters dynamically**.<br>

---

## 📋 Environment Variables
Before running the bot, configure the required **environment variables**.

1. **Rename the `.env.copy` file to `.env`.**
2. **Set the required variables:**

```plaintext
PRIVATE_KEY=your_wallet_private_key_here
RPC_ENDPOINT=https://fullnode.mainnet.sui.io
CETUS_POOL_ID=pool_id_here
BUY_AMOUNT=10  # SUI amount per buy order
SELL_AMOUNT=10 # SUI amount per sell order
INTERVAL=5     # Time interval between swaps (in seconds)
NUM_WALLETS=5  # Number of wallets to distribute volume across
```

---

## 🛠️ Installation & Setup

1️⃣ **Clone the Repository**
```sh
git clone https://github.com/your-repo/sui-volume-bot.git
cd sui-volume-bot
```

2️⃣ **Install Dependencies**
```sh
yarn install  # or npm install
```

3️⃣ **Run the Bot**
```sh
yarn start  # or npm start
```

---

## 📊 Performance Optimization
- Uses **CETUS DEX swap routing** for efficient trades.
- Implements **priority fee management** for fast execution.
- Supports **multiple RPC endpoints** for reliability.
- Dynamically adjusts **buy/sell sizes** based on market conditions.

---

## 📞 Contact
📩 For full access, reach out via:
- **Telegram:** [T-rustdev](https://t.me/T_rustdev)

---

⚡ **Use responsibly! This bot is designed for increasing volume and liquidity. Always test in a safe environment before deploying on the mainnet.** 🚀
