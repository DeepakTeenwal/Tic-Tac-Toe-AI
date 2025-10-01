# Tic-Tac-Toe AI

A Farcaster Mini App featuring Tic-Tac-Toe with unbeatable AI powered by the Minimax algorithm. Built with Farcaster SDK, WAGMI/Viem for wallet authentication, and optimized for web3 gameplay.

## Features

- **Farcaster SDK Integration**: Native Farcaster Mini App with frame support and splash screen
- **Wallet Authentication**: Connect and authenticate with Ethereum wallets using WAGMI/Viem
- **Blockchain-Ready**: Built with `@wagmi/core` and Viem for seamless web3 interactions
- **Unbeatable Minimax AI**: Challenge an AI opponent that uses optimal strategy
- **Real-time Haptic Feedback**: Native haptics for success, failure, and draw states
- **Social Sharing**: Post game results directly to Farcaster
- **Score Tracking**: Persistent score counter for wins, losses, and draws
- **Responsive Design**: Modern UI that works on desktop and mobile
- **PWA Metadata**: Optimized meta tags for Farcaster frame display with custom icons

## Tech Stack

- Farcaster SDK (`@farcaster/miniapp-sdk`)
- WAGMI Core (`@wagmi/core`) with Farcaster connector
- Viem for Ethereum utilities
- Pure HTML/CSS/JavaScript (no build tools required)
- ESM imports from esm.sh CDN

## Getting Started

1. Clone the repo
   ```bash
   git clone https://github.com/DeepakTeenwal/Tic-Tac-Toe-AI.git
   cd Tic-Tac-Toe-AI
   ```

2. Open index.html in your browser, or host via any static server
   ```bash
   # Python
   python -m http.server 8000
   
   # Node
   npx serve .
   ```

3. For Farcaster Mini App testing, deploy to Vercel or your preferred hosting service

## How It Works

- The AI evaluates the board using Minimax to choose the optimal move.
- Scores terminal states: win (+10), loss (-10), draw (0) relative to AI.
- Optionally limits depth for faster play while remaining strong.
- Farcaster SDK enables user context, wallet connection, and social features.
- WAGMI/Viem handle all blockchain interactions for wallet authentication.

## Wallet Features

- Connect wallet via Farcaster-compatible Ethereum provider
- Authenticate to unlock premium gameplay features
- Wallet address display in game status
- Built-in error handling and retry logic

## Project Structure

```
.
├── .well-known/
│   └── farcaster.json      # Farcaster frame configuration
├── index.html              # Main game file with SDK integration
├── icon.png                # App icon (192x192)
├── splash.png              # Splash screen image
├── favicon.ico
├── vercel.json             # Deployment configuration
└── README.md
```

## Roadmap

- [ ] Difficulty levels (Easy/Medium/Hard)
- [ ] Animated move transitions
- [ ] Sound effects and accessibility improvements
- [ ] Smart contract integration for on-chain betting
- [ ] Multiplayer mode via Farcaster
- [ ] Leaderboard system

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with improvements or bug fixes.

## License

This project is licensed under the MIT License.

## Contributors

- Deepak Teenwal
- [CryptoExplor](https://github.com/CryptoExplor)
