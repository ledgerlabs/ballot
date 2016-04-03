# Ballot dApp

A simple Ballot dApp using jQuery, Semantic and web3.js. 

### Installation

0. Install <a href="https://github.com/ethereum/go-ethereum/wiki/Building-Ethereum">geth</a>, create an account:

		geth account new
		
1. Copy the new account address, paste it in the ZeroGox faucet, click "Gimme Wei":

		https://zerogox.com/ethereum/wei_faucet

1. Run an Ethereum testnet geth node:

		geth --testnet --unlock "0" --shh --rpc --rpcapi="db,eth,net,web3,shh" --rpcaddr="0.0.0.0" --rpccorsdomain="*"
		
2. Open the dApp.html in Chrome

### Usage

- Create a Ballot with a Number of Proposals

- Give Right to Vote/Delegate or Vote on Proposals

- Check The Winning Proposal

### Starding A Simple Python Server

Note the directory you start your server in, is the directory is will serve the files at. So you will want to "cd ballot" over to the Ballot dApp folder.

0. Open Terminal

1. Start a Simple Python Server

		python -m SimpleHTTPServer 8000
		
2. Open "http://localhost:8000/dApp.html" in Chrome