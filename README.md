<div align="center">
  <h1>🚀 Pocket Option Analyzer</h1>
  <p><strong>Advanced Trading Analysis Tool for Pocket Option</strong></p>
  <img src="https://github.com/Rufus011/Pocket-option-Analyzer/raw/main/screenshot.png" alt="Pocket Option Analyzer Screenshot" width="600"/>
</div>

---

## 📖 Overview

**Pocket Option Analyzer** is a powerful, author-developed tool designed for traders using the Pocket Option platform. This software provides real-time market data analysis, technical indicators, and AI-driven trading recommendations to help you make informed decisions. Built with Python and Tkinter, it connects to live market feeds via WebSocket, processes data, and delivers actionable insights through an intuitive GUI.

This is an **original, authorial product** created by **@romis_111**. The tool is tailored for traders who want to enhance their strategies with data-driven insights, featuring a sleek interface with a blue-to-purple gradient design.

---

## ✨ Features

- **Real-Time Market Data**: Connects to live market feeds via WebSocket to fetch and display data for the GBPCAD symbol.
- **Candle Buffer**: Tracks and buffers candlestick data for analysis.
- **Technical Indicators**: Displays key indicators to help identify market trends.
- **AI Trading Recommendations**: Provides AI-driven signals with confidence levels and expiration times.
- **Market Hours Tracking**: Shows active trading sessions for New York, London, and Tokyo.
- **Performance Monitoring**: Logs and displays latency, analysis time, and GUI update performance.
- **Customizable Interface**: Compact design with a blue-to-purple gradient for a visually appealing experience.

---

## 🖼️ Screenshot

<div align="center">
  <img src="https://github.com/Rufus011/Pocket-option-Analyzer/raw/main/screenshot.png" alt="Pocket Option Analyzer Interface" width="500"/>
</div>

---

## 🛠️ Installation

### Prerequisites

- Python 3.8+
- Required Python packages:
  - `tkinter` (usually included with Python)
  - `websocket-client`
  - `pytz`
  - `dataclasses` (included in Python 3.7+)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/Rufus011/Pocket-option-Analyzer.git
   cd Pocket-option-Analyzer
   ```

2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:
   - Windows:
     ```bash
     venv\Scripts\activate
     ```
   - macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

4. Install required packages:
   ```bash
   pip install websocket-client pytz
   ```

5. Launch the application:
   ```bash
   python main.py
   ```

---

## 🔧 Configuration

The tool comes pre-configured for the GBPCAD symbol, but you can modify the following settings in the `config.py` file:

- Trading pair/symbol
- Technical indicator parameters
- WebSocket connection details
- UI appearance and layout
- Animation settings and transitions

The interface features smooth animations for data updates, signal alerts, and market transitions that enhance the visual experience without compromising performance.

---

## 💡 Usage Guide

1. **Launch the application**: Run `main.py` to start the analyzer.
2. **Monitor real-time data**: The main display shows current market data for GBPCAD.
3. **Check indicators**: Review the technical indicators section for trend analysis.
4. **Trading signals**: Look for AI-generated trading recommendations in the signals panel.
5. **Market sessions**: Track which major market sessions are currently active.
6. **Performance metrics**: Monitor system performance in the bottom section.

---

## 📊 Technical Indicators Explained

- **RSI (Relative Strength Index)**: Measures the magnitude of recent price changes to evaluate overbought or oversold conditions.
- **MACD (Moving Average Convergence Divergence)**: Shows the relationship between two moving averages of a security's price.
- **Bollinger Bands**: Indicates volatility with upper and lower bands that represent standard deviations from a simple moving average.
- **Support & Resistance**: Identifies key price levels where the market historically reverses direction.

---

## 📈 AI Signal System

The AI signal system analyzes multiple factors including:

- Recent price action patterns
- Technical indicator convergence
- Historical performance under similar conditions
- Market volatility and liquidity

Signals include direction (UP/DOWN), confidence level (percentage), and recommended expiration time.

---

## 🎮 Animated UI Elements

The interface features several dynamic animations that enhance user experience:

- **Signal Animations**: Visual pulse effects when new trading signals are generated
- **Price Movement Animations**: Smooth transitions for price updates with color-coding
- **Loading Animations**: Elegant loading indicators during data processing
- **Session Transition Effects**: Visual cues when market sessions open and close
- **Alert Animations**: Attention-grabbing effects for important notifications
- **Gradient Shifts**: Subtle background gradient shifts based on market conditions

All animations are optimized for performance and can be adjusted or disabled in the settings.

---

## 🔄 Updates & Maintenance

- The tool automatically checks for updates on startup.
- Regular updates are provided to improve performance and add new features.
- Bug reports and feature requests can be submitted via GitHub issues.

---

## ⚠️ Disclaimer

This tool is provided for informational purposes only and should not be considered financial advice. Trading involves significant risk of loss. Always do your own research and consider your financial circumstances before making trading decisions.

---

## 📞 Support & Contact

For support, bug reports, or feature requests, please contact:
- GitHub: [github.com/Rufus011](https://github.com/Rufus011)
- Email: tervernikson@gmail.com
- Telegram: [@romis_111](https://t.me/romis_111)
- Discord: rufus_011

---

## 📜 License

© 2023 @romis_111. All rights reserved.
This software is provided for personal use only. Redistribution or commercial use without permission is prohibited.

---

<div align="center">
  <p><strong>Pocket Option Analyzer</strong> — Trade Smarter, Not Harder</p>
</div>
