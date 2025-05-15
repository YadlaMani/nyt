# Not Your Type

**Not Your Type** is a web application for prediction markets and social polling, where users are rewarded for thinking differently. Built with Next.js, TypeScript, and thirdweb, it lets you participate in or create polls, vote, and earn rewards for picking the least popular option.
## Demo 


https://github.com/user-attachments/assets/ccb297fb-8013-4b49-8bb3-f6d8e135a8d2


## Features

- **Live Prediction Markets:** Browse and join active polls.
- **Real-Time Voting:** See live stats and trends as users vote.
- **Reward System:** Earn rewards for voting against the crowd.
- **Create Custom Polls:** Launch your own polls with custom options and rewards.
- **Wallet Integration:** Connect with MetaMask, Coinbase, and more via thirdweb.
- **Responsive UI:** Built with Tailwind CSS and Radix UI for a modern, accessible experience.

## Getting Started

1. **Install dependencies:**
   ```sh
   npm install
   ```
2. **Set up environment variables:**

- Copy .env.example to .env and fill in your NEXT_PUBLIC_THIRDWEB_CLIENT_ID and any other required values.

3. Run the development server:

```bash
npm run dev
```

Open http://localhost:3000 in your browser.

## Project Structure

```
src/
  app/            # Next.js app directory (pages, layout, styles)
  components/     # UI and feature components (Appbar, MarketCard, etc.)
  lib/            # Utility functions (e.g., className helpers)
  utils/          # Blockchain and API utilities (thirdweb client, dbConnect)
public/           # Static assets
```

- Key Components:
  - **PredictionMarketDashboard**: Main dashboard for browsing and filtering markets.
  - **MarketCard**: Displays individual market details and voting interface.
  - **MarketBuyInterface**: Handles voting and approval transactions.
  - **Appbar**: Navigation and wallet connection.

## Technologies Used

- Next.js
- TypeScript
- thirdweb (Web3 wallet and contract integration)
- Tailwind CSS
- Radix UI
- Lucide Icons
