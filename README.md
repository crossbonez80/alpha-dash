AlphaDash - Trading Competition Analytics Terminal

AlphaDash is a sophisticated, data-driven dashboard designed to help traders track, analyze, and optimize their performance in trading competitions. Built with a local-first architecture, it runs entirely in your browser, ensuring your data remains private while providing powerful insights.

✨ Key Features

Real-time Dashboard:

Live Status: Instantly see if your volume is "Safe" (leading the threshold) or "At Risk" (lagging).

Threshold Tracking: Monitor the current leaderboard cutoff volume.

Reward Estimation: Calculate estimated rewards based on live token prices (CoinGecko integration).

Predictions: AI-assisted prediction for the next day's volume target based on linear trends.

Countdown: Visual countdown timer for competition start and end times.

AI Integration (Gemini-Powered):

Screenshot Recognition: Upload a screenshot of a leaderboard, and the AI will automatically extract volume, rank, and date data.

Strategy Insights: Generate personalized trading strategies, risk assessments, and actionable advice based on your historical data.

Data Management:

Multi-Track Support: Manage multiple competitions (e.g., Midnight, Bitcoin, Solana) with customizable themes and icons.

History Snapshots: Detailed daily records with visual safe/risk indicators.

Manual Entry: Easy-to-use interface for manually logging your daily volume and costs.

Import/Export: Backup your data to JSON or restore it on another device.

User Experience:

Responsive Design: Fully optimized for both desktop and mobile devices.

Theme Support: Seamless switching between Dark and Light modes.

Multi-Language: Native support for English and Chinese (CN).

Privacy Focused: All API keys and competition data are stored locally in your browser's LocalStorage.

🚀 Getting Started

Prerequisites

A modern web browser (Chrome, Edge, Safari, Firefox).

(Optional) A Google Gemini API Key for AI features.

Installation

AlphaDash is a single-file HTML application. No complex build process is required.

Download the UserVolumeMonitor.html file.

Open the file directly in your web browser.

Setting Up AI Features

To use the Screenshot Recognition and Strategy Insight features:

Click the Settings (gear icon) in the top right corner.

Enter your Google Gemini API Key.

Click Save Settings.

📖 Usage Guide

1. Managing Competitions

Click the competition name (e.g., "NIGHT DASHBOARD") in the header to open the switch menu.

Use the "+" button to add a new competition track.

Customize the symbol, dates, and color theme.

2. Logging Data

Manual: Click the "Manual Input" button in the History card. Enter the date, threshold volume, and your volume.

AI Scan: Click the "Screenshot" button (camera icon) and upload an image of the leaderboard. The AI will parse the data for you.

3. Analyzing Performance

View the Market Intelligence HUB for a visual curve of the threshold vs. your volume.

Click "AI Analysis" to get a generated report on the current market phase and suggested strategies.

🛠 Technologies Used

React 18: UI Component library.

Tailwind CSS: Utility-first styling.

Recharts: Data visualization.

Lucide React: Iconography.

Google Gemini API: AI capabilities (Vision & Text).

CoinGecko API: Real-time crypto pricing.

📄 License

This project is open-source. Feel free to modify and distribute it for personal use.

Developed with ❤️ for the trading community.
