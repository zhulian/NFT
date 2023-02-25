# NFT
This is source code for NFT minting test website.
Please note: 
1, I removed node_modules because it's too big.
2, I removed private key cuz of security problem.
3, I attached user manual for briefing how to use the website.

My developing steps is as below:
1, Create a new CRA applition.
2, Write smart contract code using solidity.
3, Deploy the contract to goerli testnetwork using hardhat.
4, make it readable and verify the contract on https://goerli.etherscan.io/
5, Devoplop frontend using react and chakra UI
6, Use ethers.js to communicate with ethernet 
7, Test some features for the website.

All packages need to install is below list:
npx create-react-app mint-website
npm i -D hardhat 
npm i @openzeppelin/contracts 
npm i @chakra-ui/react @emotion/react @emotion/styled framer-motion
npm i @nomicfoundation/hardhat-toolbox
npm i @nomiclabs/hardhat-etherscan 
npm i @quant-finance/solidity-datetime
npm i -D dotenv
npm install --save-dev react-app-rewired crypto-browserify stream-browserify assert stream-http https-browserify os-browserify url buffer process

Some command lines:
1, Generate hadhat config file: npx hardhat
2, Deploy the contract to goerli network: npx hardhat run scripts/deploySimpleNFT.js --network goerli
3, Verification for readable contract: npx hardhat verify --network goerli 0x32911006c849a923F99e1bE627BBA48eb0C15799

All tools used in development:
1, Alchemy
2, Metamask
3, Etherscan for goerli
4, Pinata
5, Goerli Faucet
6, Mining tool: https://goerli-faucet.pk910.de/



