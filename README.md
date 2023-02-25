# NFT
This is source code for NFT minting test website. <br />
Please note:  <br />
1, I removed node_modules because it's too big. <br />
2, I removed private key cuz of security problem. <br />
3, I attached user manual for briefing how to use the website. <br />

My developing steps is as below: <br />
1, Create a new CRA applition. <br />
2, Write smart contract code using solidity. <br />
3, Deploy the contract to goerli testnetwork using hardhat. <br />
4, make it readable and verify the contract on https://goerli.etherscan.io/ <br />
5, Devoplop frontend using react and chakra UI <br />
6, Use ethers.js to communicate with ethernet  <br />
7, Test some features for the website. <br />

All packages need to install is below list: <br />
npx create-react-app mint-website <br />
npm i -D hardhat  <br />
npm i @openzeppelin/contracts  <br />
npm i @chakra-ui/react @emotion/react @emotion/styled framer-motion <br />
npm i @nomicfoundation/hardhat-toolbox <br />
npm i @nomiclabs/hardhat-etherscan  <br />
npm i @quant-finance/solidity-datetime <br />
npm i -D dotenv <br />
npm install --save-dev react-app-rewired crypto-browserify stream-browserify assert stream-http https-browserify os-browserify url buffer process <br />

Some command lines: <br />
1, Generate hadhat config file: npx hardhat <br />
2, Deploy the contract to goerli network: npx hardhat run scripts/deploySimpleNFT.js --network goerli <br />
3, Verification for readable contract: npx hardhat verify --network goerli 0x32911006c849a923F99e1bE627BBA48eb0C15799 <br />

All tools used in development: <br />
1, Alchemy <br />
2, Metamask <br />
3, Etherscan for goerli <br />
4, Pinata <br />
5, Goerli Faucet <br />
6, Mining tool: https://goerli-faucet.pk910.de/ <br />



