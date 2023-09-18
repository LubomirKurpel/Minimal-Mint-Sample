# Minimal Mint Sample - Minting NFT's with simple Web3Modal popup

This repo holds bare minimum code for minting NFTs via Web3Modal popup. 

Functionality consists of 3 parts:
- Basic HTML page with JS scripts in head to load web3modal library + scripts.js file
- Scripts.js file which calls solidity functions to mint with user wallet (metamask or mobile phone wallet via wallet connect)
- Solidity file with bare minimum functions to save wallet in mapping and load wallet from mapping. You can call some other functions in similar / same fashion - mostly mint() function or so.
