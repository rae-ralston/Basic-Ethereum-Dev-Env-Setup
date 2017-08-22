# Ethereum Development Environment Setup


This assumes you have [node](https://nodejs.org/en/) & [homebrew](https://brew.sh/) already installed on your machine.

## Install Everything

#### 1. Install Solidity

- [Solidity Documentation](http://solidity.readthedocs.io/en/develop/installing-solidity.html)

Solidity is the language you use to develop smart contracts on the ethereum network.

To install solidity onto your machine

install via NPM
```bash
npm install -g solc
```

or homebrew
```
brew update
brew upgrade
brew tap ethereum/ethereum
brew install solidity
brew linkapps solidity
```


#### Install testrpc

- [testrpc Documentation](https://github.com/ethereumjs/testrpc)

`testrpc` is a Node.js based Ethereum client for testing and development. It uses ethereumjs to simulate full client behavior and make developing Ethereum applications much faster.

Install globally with NPM:
```
npm install -g ethereumjs-testrpc
```


#### Truffle

- [Truffle Documentation](http://truffleframework.com/docs/)

Truffle is a world class development environment, testing framework and asset pipeline for Ethereum, aiming to make life as an Ethereum developer easier.

```
npm install -g truffle
```


#### Web3

- [Web3 Documentation](https://web3js.readthedocs.io/en/1.0/getting-started.html)
- [Web3 Github](https://github.com/ethereum/web3.js/)
- [Ethereum Javascript API & Web3 Docs](https://github.com/ethereum/wiki/wiki/JavaScript-API)

The web3.js library is a collection of modules which contain specific functionality for the ethereum ecosystem. You install Web3 directly into your project.

The `web3-eth` is for the ethereum blockchain and smart contracts
The `web3-shh` is for the whisper protocol to communicate p2p and broadcast
The `web3-bzz` is for the swarm protocol, the decentralized file storage
The `web3-utils` contains useful helper functions for Dapp developers.

```
npm install --save web3-eth
```


#### Metamask Chrome Plugin

- [Metamask](https://metamask.io/)

MetaMask is a bridge that allows you to visit the distributed web of tomorrow in your browser today. It allows you to run Ethereum dApps right in your browser without running a full Ethereum node.

MetaMask includes a secure identity vault, providing a user interface to manage your identities on different sites and sign blockchain transactions.

We’re initially building MetaMask as a Chrome plugin, but eventually plan to support Firefox and beyond. If you’re a developer, you can start developing with MetaMask today.

Our mission is to make Ethereum as easy to use for as many people as possible.
