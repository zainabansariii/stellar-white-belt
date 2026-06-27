# Stellar White Belt

A lightweight Stellar Testnet payment app built for the White Belt level. Connect Freighter, check your balance, send XLM with a short memo, and review past activity — all on testnet.

**Live app:** [https://stellar-white-belttt.vercel.app](https://stellar-white-belttt.vercel.app)

## What it does

This project covers the basics of building on Stellar:

- Link and unlink a **Freighter** wallet on **Stellar Testnet**
- Pull and show the wallet's **XLM balance**
- **Transfer XLM** on testnet with clear success or error feedback and a transaction hash
- Load transaction history from Stellar Horizon

Signing happens inside Freighter. The app never sees or stores private keys.

## White Belt checklist

| Item | Done |
|---|---|
| Freighter wallet setup | ✅ |
| Stellar Testnet | ✅ |
| Wallet connect | ✅ |
| Wallet disconnect | ✅ |
| Fetch XLM balance | ✅ |
| Display balance in UI | ✅ |
| Send XLM on testnet | ✅ |
| Transaction success/failure feedback | ✅ |
| Transaction hash / confirmation | ✅ |
| Error handling | ✅ |
| Public GitHub repository | ✅ |
| README with setup instructions | ✅ |

## Stack

- **Frontend:** Vanilla JavaScript + Vite
- **Blockchain:** Stellar SDK
- **Wallet:** Freighter (`@stellar/freighter-api`)
- **Network:** Stellar Testnet

## Run locally

### 1. Clone the repo

```bash
git clone https://github.com/zainabansariii/stellar-white-belt.git
cd stellar-white-belt/stellar-white-belt
```

### 2. Install packages

```bash
npm install
```

### 3. Start the dev server

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### 4. Set up Freighter

1. Install the [Freighter Wallet](https://www.freighter.app/) extension
2. Set the network to **TESTNET**
3. Top up your account with [Stellar Laboratory Friendbot](https://laboratory.stellar.org/#account-creator?network=test)

## Features

1. **Connected wallet** — Address, Testnet badge, and session status in one bar
2. **Live balance** — XLM balance from Stellar Testnet Horizon
3. **Send payment** — Recipient, amount, optional memo; sign in Freighter and submit
4. **Result screen** — Success or failure with transaction hash and an explorer link

## Important

- **Testnet only** — no mainnet funds
- Freighter browser extension required
- Every transaction needs approval in Freighter
- Secret keys stay in the wallet, not in this app

## Deployment

Hosted at: [https://stellar-white-belttt.vercel.app](https://stellar-white-belttt.vercel.app)

screenshots:
<img width="1637" height="882" alt="image" src="https://github.com/user-attachments/assets/768062a6-66c9-4bf6-83e3-f8011b94d9ef" />

<img width="1220" height="861" alt="image" src="https://github.com/user-attachments/assets/e8fedf49-05ed-4347-80d6-bc389054e903" />
