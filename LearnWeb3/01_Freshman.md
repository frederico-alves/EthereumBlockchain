🚀 FRESHMAN 🚀
https://learnweb3.io

1.=================
      LEVEL 1
=================

❓ What is Blockchain?
📝 A distributed database running on a peer to peer network of nodes

❓ What is a genesis block?
📝 The initial state of the blockchain

❓ Where are your cryptocurrency assets stored?
📝 In your digital wallet

❓ What is a miner?
📝 A node responsible for verifying and auditing transactions

❓ Why do miners do hard work to secure the network?
📝 For block rewards

❓ What is a node in a blockchain network?
📝 A computer running the blockchain software

Use Cases of Decentralized Network (Web 3):
✅ Cryptocurrency
✅ Smart Contracts
✅ Decentralized Finance
✅ Gaming
✅ Supply Chain Tracking
✅ Counterfeiting Protection
✅ Data Privacy
✅ Decentralized Governance
✅ Verifiable ownership of assets

2.=================
      LEVEL 2
=================

❓ What is Ethereum?
📝 Ethereum is a decentralized blockchain that supports smart contracts.

💎 ETHEREUM & dAPPS 💎

dApps = decentralized applications, which can be executed on the Ethereum Virtual Machine (EVM).

dApps are built on Ethereum using it's programming language, Solidity

Ethereum was originally proposed by Vitalik Buterin in 2014. He proposed the development of a new blockchain platform with a Turing-complete programming language (Solidity).

❓ What is the native currency of Ethereum?
📝 ETH

❓ What are Smart Contracts?
📝 Smart contracts are small computer programs that are replicated and processed on all the computers on the Ethereum network without a central coordinator. Smart Contracts allow you to program contracts that can be automatically enforced by computer code.

8.=================
      LEVEL 8
💡 Cryptocurrency Tutorial (ERC20)
=================

Remix IDE
--> It's good practice to use a license identifier
--> pragma solidity ^0.8.0;

--> OpenZepplin documentation is very important ❗️
🔗 https://docs.openzeppelin.com
--> import OpenZepplin file - it's the stander used by the community. Very secure.

Use Standard ERC20
🔗 https://docs.openzeppelin.com/contracts/4.x/erc20

--> Write contract LW3Token is ERC20 {
    constructor(string memoru _name, string memory _symbol) ERC20 (...)
    ...
}

--> Deploy & Run transactions


9.=================
      LEVEL 9
💡 NFT Tutorial
=================

Deploy a NFT project on Ethereum:

`
mkdir NFT-Tutorial
cd  NFT-Tutorial
npm init --yes
npm install --save-dev hardhat
`


`
npx hardhat
--> Select JavaScript project
`

`
npm install --save-dev @nomicfoundation/hardhat-toolbox
`

ERC20 - Token to print money (a lot of similar, swapable);
ERC721 - Unique ID (it is not swapable);
ERC725 - Similar tokens in the same collection but different ID;

ALCHEMY API
🔗 https://www.alchemyapi.io
--> It allows to run 10 nodes for free
--> Connect to Alchemy pasting the ALCHEMY_API_KEY_URL in .env file
--> Connect private key GOERLI_PRIVATE_KEY
--> Install the following environment:
`
npm install dotenv
`

