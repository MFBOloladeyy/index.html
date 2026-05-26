Arc Counter — On-Chain dApp
A live Web3 dApp that reads and writes to a smart contract deployed on the Arc Testnet. Built with vanilla JavaScript and ethers.js — no framework, no build step.
Live Demo · View on Arc Explorer
What It Does
Reads the current counter value live from the Arc Testnet blockchain
Connects to MetaMask or Rabby wallet
Sends real on-chain transactions to increment the counter
Links every transaction to the Arc block explorer
Auto-switches your wallet to Arc Testnet if needed
Smart Contract
The Counter contract is deployed on Arc Testnet at:
Code
Solidity
Network Details
Parameter
Value
Network
Arc Testnet
Chain ID
5042002
RPC
https://rpc.testnet.arc.network
Gas token
USDC
Explorer
testnet.arcscan.app
Run Locally
No setup needed:
Bash
You'll need a browser wallet (MetaMask or Rabby) and testnet USDC from faucet.circle.com to send transactions.
Built With
Vanilla HTML, CSS, JavaScript
ethers.js v6 — wallet connection and contract interaction
Remix IDE — contract deployment
Arc Testnet — EVM-compatible L1 with USDC as gas token
Google Fonts — Space Mono + Syne
Made by @mfbololadeyy
