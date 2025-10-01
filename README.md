# Tic-Tac-Toe AI

A simple Tic-Tac-Toe game with an unbeatable AI using the Minimax algorithm. Play in your browser and challenge the computer on a 3x3 board.

## Features
- Human vs AI gameplay
- Unbeatable Minimax AI with optional depth pruning
- Responsive UI, works on desktop and mobile
- Reset/restart controls
- No dependencies, just open index.html

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

## How It Works
- The AI evaluates the board using Minimax to choose the optimal move.
- Scores terminal states: win (+10), loss (-10), draw (0) relative to AI.
- Optionally limits depth for faster play while remaining strong.

## Project Structure
```
.
├── index.html
├── icon.png
├── splash.png
├── favicon.ico
└── README.md
```

## Roadmap
- [ ] Difficulty levels (Easy/Medium/Hard)
- [ ] Animated move transitions
- [ ] Sound effects and accessibility improvements
- [ ] PWA support with offline caching

## Contributing
Contributions are welcome! Please open an issue or submit a pull request with improvements or bug fixes.

## License
This project is licensed under the MIT License.

## Contributors
- Deepak Teenwal
