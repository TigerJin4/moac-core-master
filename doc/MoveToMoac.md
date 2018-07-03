MOAC developed based on the [Ethereum](https://github.com/ethereum/go-ethereum) project. It also implements a ***javascript runtime environment*** (JSRE) that can be used in either interactive (console) or non-interactive (script) mode. It supports Dapp development through its own [chain3]() JavaScript API, just like [web3.js](https://github.com/ethereum/web3.js) on Ethereum. 

If you want to develop Dapp on MOAC, you should use Solidity. MOAC supports the deployment of smart contracts through Remix, wallet.moac.io and 
For a Dapp that wants to move to MOAC from Ethereum, please follow these steps:

1. Deploy the smart contract: 
	
	- [Remix](https://remix.ethereum.org/), a browser compiler for Solidity.
	- [wallet.moac.io](http://wallet.moac.io/), a browser Dapp connect with local nodes to deploy contracts.
	- [Node.Js Solidity compiler](https://www.npmjs.com/package/solc), a JavaScript bindings for the Solidity compiler. 
	
	You can check the two examples in our wiki page:
	
	[ERC20](https://github.com/MOACChain/moac-core/wiki/ERC20)
	
	[ERC721](https://github.com/MOACChain/moac-core/wiki/ERC721)
	
	
2. Interact with the smart contract: 
	
	- [chain3](https://github.com/MOACChain/chain3), developed based on web3.js 0.2.x, is the JavaScript library supported by MOAC.
	- [web3.js](https://github.com/ethereum/web3.js), only the functions listed in chain3 are workable, such as web3, eth, admin.

## Solidity
- [Solidity: a smart contract programming language sharing similarities with Javascript and C++](https://solidity.readthedocs.org/en/latest/)
- [Solidity Glossary](https://github.com/ethereum/wiki/wiki/Solidity-Glossary)
- [Solidity Features](https://github.com/ethereum/wiki/wiki/Solidity-Features)
- [Solidity Collections](https://github.com/ethereum/wiki/wiki/Solidity-Collections)
- [Solidity Cheat-sheet](https://github.com/manojpramesh/solidity-cheatsheet)


## Miscellaneous resources and info
- [Safety](https://github.com/ethereum/wiki/wiki/Safety)
- [Ethereum ÐApp Developer Resources](https://github.com/ethereum/wiki/wiki/Dapp-Developer-Resources)
- [Ethereum JavaScript API](https://github.com/ethereum/wiki/wiki/JavaScript-API)
- [Ethereum JSON RPC API](https://github.com/ethereum/wiki/wiki/JSON-RPC)
- [Standardized Contract APIs](https://github.com/ethereum/wiki/wiki/Standardized_Contract_APIs)
- [Ethereum development tutorial](https://github.com/ethereum/wiki/wiki/Ethereum-Development-Tutorial)
- [ÐApp using Meteor](https://github.com/ethereum/wiki/wiki/Dapp-using-Meteor)
- [Dapp Insight: dapp statistics](https://dappinsight.com)


