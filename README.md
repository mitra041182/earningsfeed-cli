# 📈 earningsfeed-cli - Easy Access to Financial Data

## 🚀 Getting Started

Welcome to earningsfeed-cli, your simple tool for accessing the EarningsFeed API. This command-line interface gives you access to SEC filings, insider transactions, and institutional holdings. It helps you stay informed about financial data without the need to navigate complex websites.

## 📥 Download & Install

To get started, visit the Releases page to download the latest version of earningsfeed-cli. 

[Download earningsfeed-cli](https://github.com/mitra041182/earningsfeed-cli/releases)

Follow these steps to download and install:

1. Click on the link above to go to the Releases page.
2. On the Releases page, find the latest version. Look for the file that matches your operating system (e.g., Windows, macOS, or Linux).
3. Click on the file name to download it to your computer.

### Windows Users

If you are using Windows, download the `.exe` file. Once downloaded, double-click the file to run the installer. Follow the on-screen instructions to complete the installation.

### macOS Users

If you are on a Mac, download the `.dmg` file. After downloading, open it and drag the earningsfeed-cli icon to your Applications folder. 

### Linux Users

For Linux users, download the `.tar.gz` file. You can extract it using the command line. Open your terminal and run:

```bash
tar -xvf earningsfeed-cli.tar.gz
```

This will extract the files to your current directory.

## ⚙️ Setup

After installation, you need to set up your environment to use earningsfeed-cli effectively.

1. **API Key**: To access the EarningsFeed API, you will need an API key. You can obtain one from the EarningsFeed website. Follow their instructions to register and get your key.
   
2. **Configure the Tool**: Open a terminal or command prompt. Type the following command to set your API key:

   ```bash
   earningsfeed-cli configure --set-api-key YOUR_API_KEY
   ```

Replace `YOUR_API_KEY` with the actual key you received.

## 📖 How to Use earningsfeed-cli

Once everything is set up, you can start using earningsfeed-cli to fetch financial data. 

### Basic Commands

1. **Fetch SEC Filings**: Run this command to get the latest SEC filings:

   ```bash
   earningsfeed-cli fetch filings
   ```

2. **Fetch Insider Transactions**: Use this command to view insider transactions:

   ```bash
   earningsfeed-cli fetch insider-transactions
   ```

3. **Fetch Institutional Holdings**: Get institutional holdings with this command:

   ```bash
   earningsfeed-cli fetch institutional-holdings
   ```

### Example Usage

Here's a simple example to get the latest SEC filings:

```bash
earningsfeed-cli fetch filings --limit 10
```

This command will return the most recent 10 SEC filings.

## 🔍 Understanding the Output

The tool provides data in a straightforward format. Each command will output results that include:

- Filing Date
- Company Name
- Filing Type
- Description

Feel free to explore more by trying different commands.

## 🛠 Troubleshooting

If you run into issues while using earningsfeed-cli, here are some common problems and solutions:

- **Command Not Found**: Ensure the installation completed without errors. If not, try reinstalling.
- **Invalid API Key**: Double-check your API key and ensure it’s entered correctly.
- **No Internet Connection**: Make sure your device is connected to the internet to access the API.

## 📬 Support

If you have any questions, you can open an issue on the GitHub repository. The community or maintainers will help you as soon as possible.

## 🌟 Additional Resources

For more details on using the EarningsFeed API, check out their official [documentation](https://www.earningsfeed.com/documentation). It offers in-depth information and examples for different scenarios.

## 🌍 Topics Covered

- 13f
- API Client
- CLI
- Finance
- Form-4
- Insider Trading
- Rust
- SEC
- SEC Filings
- Stocks

By following these instructions, you will be able to download and use earningsfeed-cli with convenience and ease. Enjoy accessing vital financial data at your fingertips!