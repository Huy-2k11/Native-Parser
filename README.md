<img width="576" height="825" alt="image" src="https://github.com/user-attachments/assets/11e57fd3-d694-4dee-a73d-073587ff0d7f" />


Balance Checker for Multi-Chain Wallets

A Python script that checks native token balances (ETH, BNB, POL) across 6 blockchains: Ethereum, Optimism, Arbitrum, Base, BSC, Polygon — using multiple RPCs and optional proxies. Outputs results to balances.xlsx.Required Packages (install via pip)bash

pip install web3 pandas openpyxl requests

No external repositories needed — all via PyPI.
Files to Preparewallet.txt — one wallet address per line  
proxy.txt (optional) — one proxy per line (format: http://user:pass@ip:port or http://ip:port)

How to Runbash

python main.py

Logs saved to debug.log
Results saved to balances.xlsx
Features  Auto RPC fallback  
Proxy rotation  
Checksum address validation  
Excel export with wallet labels

Made for airdrop hunters & wallet auditors!

