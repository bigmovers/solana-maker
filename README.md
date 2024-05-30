# Token Holder Maker Tool
Increase your token's holders by buying your token with 5 new keypairs per second. Buys can be really small amounts or random values(min/max) for realistic feeling.
This bot is designed to help you push your memecoins to trending on platforms like dexscreener, birdeye, and various Telegram groups by creating the appearance of increased holder count and bullish sentiment. Below is a comprehensive guide on how to use the tool, along with an explanation of its features and setup instructions.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

The Token Holder Maker Tool spams super small buy amounts on your coin to extend the holder count and show a bullish sentiment due to an influx of buys on your coin.

Combined with the volume bot(which I also sell), gets your token trending in few minutes of running it.

## Features

- 💊 **Seamless UI**: Like all our products.
- 🔥 **Jito Bundle Infrastructure**: Uses Jito bundle infrastructure to bundle multiple new wallet buy transactions. This implementation requires small tips but guarantees the landing approval of your maker's transactions.
- 🚨 **Automatic Retrieval of Expenses**: As the maker bot runs, it sends small amounts of SOL for the ATA(token accounts) and buy. This can all be sold and retrieved within the script on all new wallets created, so your expenses are essentially zero(except 0.25% which is Raydium's pool fee)!
- 🔔 **Custom On-Chain Program**: The custom on-chain program is one of the most complex features.

## Requirements

- Node.js
- Free RPC

## Installation

1. **Get the code from https://t.me/benoriz0:**


2. **Install dependencies:**

    ```bash
    npm install
    ```


## Usage

1. **Start the bot:**

    ```bash
    npx ts-node main.js
    ```

2. **Configure the bot:**

    Update the configuration settings in `config.js` to match your requirements.



