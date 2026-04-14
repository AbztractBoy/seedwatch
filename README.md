# SeedWatch - Advanced Wallet Security Scanner

Advanced tool for monitoring weak seed phrases and checking balances of derived addresses from known-weak mnemonic phrases.

⚠️ **For defensive research only. Never use this tool to access or move funds.**

## Features

- **Weak Seed Phrase Detection**: Scans for known-weak seed phrases
- **Address Derivation**: Derives Ethereum addresses using BIP44 path
- **Balance Checking**: Checks ETH balances on-chain
- **Batch Processing**: Processes multiple seeds efficiently
- **Import/Export**: Import/export seed phrases and scan results
- **Password Protection**: Secure access with "seed369" password

## How to Use

1. Enter or import 12 or 24-word seed phrases
2. Click "START SCAN" to begin monitoring
3. View derived addresses and their balances
4. Use "EXPORT RESULTS" to save findings

## Security Warning

This tool is designed for **research and security auditing purposes only**. 
Do not use it to access or transfer funds from any wallet.

## Technical Details

- Uses Ethers.js for wallet derivation and RPC communication
- Supports multiple blockchain networks (Ethereum, Polygon, BSC)
- Implements BIP44 HD wallet derivation
- Real-time balance checking via RPC endpoints

## Password Protection

Access requires password: `seed369`

## Repository Structure

