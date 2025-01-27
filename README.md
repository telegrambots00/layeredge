# LayerEdge Automation Bot

An automation tool designed to help users manage their LayerEdge light nodes efficiently with a convenient terminal-based dashboard interface.



## Requirements

Before running the bot, make sure you have:

- Node.js (v16 or higher)
- npm (Node Package Manager)
- A LayerEdge account (register with referral code: `u9NH68wt`)
- Wallet private keys for activation

## Registration

1. Visit [LayerEdge Dashboard](https://dashboard.layeredge.io)
2. Enter the referral code: `u9NH68wt`
3. Connect your wallet and complete the registration
4. Start earning points by running a light node!

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Not-D4rkCipherX/Layer-Edge.git
```

2. Navigate to the project directory:

```bash
cd Layer-Edge
```

3. Install dependencies:

```bash
npm i
```

4. Configure your wallets:
   - Edit `data.txt` file in the root directory
   - Add your wallet private keys (one per line)`
     
## Usage

1. Start the bot:

```bash
node main.js
```
## How to use Auto Refer:

```bash
nano utils/config.js
```
Put your refer code and refer amount on ref_code:xxxxx & num_ref:100
Then Run the script..
```bash
node autoref.js
```
All Done..
## Controls:
   - ↑/↓: Navigate between wallets
   - ←/→: Change pages
   - Ctrl+C: Exit program

## Features Explained

### Secure Key Management

- Reads private keys from data.txt
- Automatically derives wallet addresses
- Secure signing for node activation

### Node Activation & Ping

- Automatic node status checking
- Signature-based node activation
- Continuous ping to maintain node status
- Configurable ping interval
