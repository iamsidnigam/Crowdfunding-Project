# Crowdfunding Project
 Prefinal Year Project

Project features 💡

User can start a fundraising.

Anyone can contribute.

End project if targeted contribution amount reached.

Expire project if targeted amount not fulfills between deadline.

Contributors can withdraw contributed amount if project expire.

Owner need to request contributors for withdraw amount.

Owner can withdraw amount if 50% contributors agree.

Connect with waller
 
 

Tech stack & packages used 📦

package	explain

Next.js	For building frontend

solidity	For writting smart contracts

tailwind css	For building design

ether.js	Web3 client (contract testing ).

web3.js	Web3 client (Frontend Next.js).

Chai	javascript testing framework.

react-toastify	For Notification.

hardhat	Ethereum development environment.

Redux	For managing and centralizing application state.


How to run 🏃 :

Run hardhat node

npx hardhat node

Run test cases

npx hardhat test

Deploy contract in local hardhat node

npx hardhat run scripts/deploy.js --network localhost

Connect hardhat with metamask

Run Next.js frontend

cd client

npm run dev


Web3.js

Load web3

Connect with contract

new web3.eth.Contract(jsonInterface[, address][, options])

Callback promises events

.on('transactionHash', function(hash){ ... })

.on('error', function(error){ ... })

Subscribe to event

contractName.events.EventName([options][, callback])

Fetch all data from contract event

An array with the past event Objects, matching the given event name and filter.

contractName.getPastEvents(EventName[, options][, callback])

Hardhat commands

npx hardhat accounts

npx hardhat compile

npx hardhat clean

npx hardhat test

npx hardhat node

node scripts/deploy.js

npx hardhat help

npx hardhat run scripts/deploy.js --network <network name>

