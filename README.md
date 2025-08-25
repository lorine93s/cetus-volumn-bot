# 🚀 CETUS Volumn Bot

The **CETUS Volumn Bot** is an automated trading system built to perform **continuous buy-and-sell swaps** on **CETUS DEX**. It is designed to boost **trading volume, liquidity, and maker activity** while minimizing gas costs for maximum efficiency.

### 🔔 Important Note

This repository contains a **compiled demo version** of the project. The **original source code** is written in TypeScript.
👉 For access to the **full version**, please contact me on **Telegram**.

---

## 🌟 Key Features

* ✅ **Automated SUI Distribution** – Seamlessly distributes SUI across new wallets.
* ✅ **Continuous Buy & Sell Swaps** – Maintains liquidity and trading volume automatically.
* ✅ **Gas Fee Optimization** – Smart fee calculations to minimize transaction costs.
* ✅ **Customizable Parameters** – Configure trade size, intervals, and wallet distribution.
* ✅ **Multi-Wallet Support** – Spreads trades across multiple wallets for greater impact.
* ✅ **Native CETUS DEX Integration** – Works seamlessly with CETUS liquidity pools and AMM mechanics.

---

## ⚙️ How It Works

1. The bot **distributes SUI** among multiple wallets.
2. It executes **buy and sell swaps simultaneously** to sustain volume.
3. Transactions are **optimized for gas efficiency**.
4. The bot **monitors market activity** and adjusts parameters in real time.

---

## 📋 Configuration

Before running the bot, configure the required environment variables:

1. Rename the `.env.copy` file to `.env`.
2. Set the following variables:

```plaintext
PRIVATE_KEY=your_wallet_private_key_here
RPC_ENDPOINT=https://fullnode.mainnet.sui.io
CETUS_POOL_ID=pool_id_here
BUY_AMOUNT=10   # SUI amount per buy order
SELL_AMOUNT=10  # SUI amount per sell order
INTERVAL=5      # Time interval between swaps (seconds)
NUM_WALLETS=5   # Number of wallets to distribute trades across
```

---

## 🛠️ Installation & Setup

1. **Clone the Repository**

```sh
git clone https://github.com/T-rustdev/cetus-volume-booster-sui.git
cd cetus-volume-booster-sui
```

2. **Install Dependencies**

```sh
yarn install  # or npm install
```

3. **Run the Bot**

```sh
yarn start    # or npm start
```

---

## 📊 Performance Highlights

* Leverages **CETUS swap routing** for optimal trade execution.
* Implements **priority fee management** for faster processing.
* Supports **multiple RPC endpoints** for reliability.
* Dynamically adapts **trade size and frequency** to market conditions.

---

## 📞 Contact

For full access and support, reach out via:

* **Telegram:** [@lorine93s](https://t.me/lorine93s)

---

⚡ **Disclaimer:** This bot is intended for increasing trading volume and liquidity. Always conduct thorough testing in a safe environment before deploying on mainnet.

---

Would you like me to also **add some badges (GitHub stars, version, license, etc.)** at the top to make it look even more professional?
