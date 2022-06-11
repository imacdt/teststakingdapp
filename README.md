
#  Test Token Staking dApp <h1>

#### Blockchain Token Staking dApp built with React, Solidity, on Ethereum Ganache, Ropsten,  testnet networks <h6>



![Preview](src/assets/screenshot.png)

## Changes
- [x] Added ERC20 TestToken 
- [x] Added Token Staking basic contract
- [x] Started testing 
* 
- [x] Updated Token Staking contract
- [x] Added ability to stake, unstake, redistribute
- [x] Implemented testing 
- [x] Added redistribution script
* 
- [x] Injected web3 and Metamask
- [x] Ability to detect if Metamask installed, logged, locked
- [x] Added skeletons for totalStaked, myStake, 
- [x] Added skeletons for Tester to Redistribute rewards and claim test tokens
* 
- [x] Added ability to load contracts
- [x] Fetching data from TokenStaking contract
- [x] Fetching balances
- [x] Stake, Unstake is now working
- [x] Redistribute rewards for (Admin only) is now working
* 
- [x] Implemented totalStaked
- [x] Implemented ability to claim test token(Tst) (FOR TESTING PURPOSE ONLY)
- [x] Added amount type validity check
- [x] Add ability for user to stake max 
* 
- [x] Added ability to listen to triggers .on transactionHash
- [x] Data automatically fetched after confirmation received
- [x] Added HDWallet provider and Infura setup
- [x] Deployed on ropsten
* 
- [x] Different staking pool implemented customStake/customUnstake
- [x] Implemented ability for admin to change custom pool APY value via script
* 
- [x] Implemented custom reward Pool redistribution
- [x] Contract Source Code Verified (Exact Match)
* 
- [x] Components split in to smaller
- [x] Added frontend logic for custom pools
- [x] Added UI Elements
- [x] Loaders fixed
* 
- [x] Added checks and restrictions for when Metamask is not connected
- [x] UI Optimised for mobiles






## Running instructions
* Install project packages (`npm install`)
* Start project (`npm run start`)

## For Testing
* To run tests, navigate to /test/TokenStaking and run: `truffle test`
 
## For Admin Use
*Scipts located in scripts folder to adjust APY.



## Deployoment to Ethereum network and Verification

For private Ethereum test network make sure Ganache is running on HTTP://127.0.0.1:7545
* First configure `truffle-config.js` with your infura key and mnemonic key. You can reate files in top dirrectory under names `.infuraKey` and `.secret` and paste your keys in there
* If you planning to publish your project on github make sure you `.gitignore` your keys 
* Compile smart contracts with `truffle compile`
* Deploy to your local (Ganache) network run: `truffle migrate --reset ` or for Ethereum test network (Rinkeby) run: `truffle migrate --network rinkeby --reset` or change `rinkeby` to `ropsten`
* To verify contract code on Ethereum test network add your Etherscan API key to `.ethKey` and for (Rinkeby) run: `truffle run verify TestToken --network rinkeby` or change `rinkeby` to `ropsten`


 


