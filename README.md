# Not Your Type

**Not Your Type** is a web application for prediction markets and social polling, where users are rewarded for thinking differently. Built with Next.js, TypeScript, and thirdweb, it lets you participate in or create polls, vote, and earn rewards for picking the least popular option.
## Demo 



https://github.com/user-attachments/assets/79607bad-a0b5-4eda-aae7-42b64029fc33




## Screenshots
![image](https://github.com/user-attachments/assets/21224168-3aff-4629-8334-fdf1c78a4942)
![image](https://github.com/user-attachments/assets/53b717c5-739b-4d0f-b132-9e31e6ba892c)
![image](https://github.com/user-attachments/assets/86197679-bb67-4d31-9621-223a83f0367b)
![image](https://github.com/user-attachments/assets/f84e8591-6e3b-4180-b592-a834a491ee40)
![image](https://github.com/user-attachments/assets/baa0d1c5-a14f-468d-831f-bfee778093d6)
![image](https://github.com/user-attachments/assets/151fbc45-fc6a-4d8d-ae60-08dbbcfece7e)


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
