# ERC20 Token with ICO Contract (Staking contract coming soon)

* Instructions coming soon

(Click for example transactions)

# Base Token Contract

yourtoken.sol - [Example contract deployed to Ropsten](https://ropsten.etherscan.io/token/0x93903333a4162885f43cd186aefefc246ffa927a) - [Security Audit](#)

**Standard Functions:** 
* .
* .

**Non-Standard Functions:**
* [enableTransfer()](https://ropsten.etherscan.io/tx/0x3c002eae81d7101b67d0c323d64d60c6c0cb4bf7f1b2dbe87863bb92c88d07f0)
* [mint(address to, uint256 value)](https://ropsten.etherscan.io/tx/0x789faaad923642a5842115612f618c57fc2f1f01486196d872a2ad7a70acc88b)
* [finishMinting()](https://ropsten.etherscan.io/tx/0x1c6affdf9883ee9196282aa86e53faf341fa40457a8005a9bc7d30f6af201075)
* [transfer(address to, uint256 value)](https://ropsten.etherscan.io/tx/0x55848251c762032f47aa731b6d1972c6312cd80a71e4dc38605e9e9e5ea5aced)
* [burn(uint256 amount)](https://ropsten.etherscan.io/tx/0x631e68bd0b66dde2bfb81a2d735ac6371e2c2d3259f751515cff754f3e861eec)

# Token Crowdsale / ICO Contract

yourtokenICO.sol - [Example contract deployed to Ropsten](https://ropsten.etherscan.io/address/0x27db5fa7f9c5d9a2f9260316db4c004aef7cbefa#code) - [Security Audit](#)

**Functions:** (Click for example transaction)
* .
* [initialize()](https://ropsten.etherscan.io/tx/0x79ae6bc7e626c7c940537946ca93efcc567bb5df61a44d889221d6741a91f309)
* [buyTokens()](https://ropsten.etherscan.io/tx/0xba457cd3722a5bfd6d04e52934ea9e1b81a92a3707628fe33e42bdf21c426111)

Ether from buyTokens is transfered to contract owner in the token purchase transaction.
