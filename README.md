# BCDentistry

In this project we are implementing storing patient data on the blockchain. We started by using the ethereum blockchain platform and then realized that using Hyperledger Fabric is better for our project and what we are trying to implement. Here's how to access the project on each one 

## Ethereum 
to run the project

_Run the ganache client_

**ganache-cli**

Use one of the account's private keys to import it into Metamask Wallet.

Do not forget to change the network to a ganache network (use the network information form truffle-config.js)

_deploy the smart contract:_

**truffle migrate --reset**

Take the contract address and replace with it the old contractAddress variable in patientList.html 

when you open the HTML file, right-click and choose run with Live Server (if you do not have it. install it from VScode extension)

## Hyperledger Fabric
