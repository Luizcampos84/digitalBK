
# Digital Bank

A brief description of what this project does and who it's for

This project is reference to the Digital decentralised Bank that allow to stake(deposit) and 
unstaking(withdraw) tokens (Ethereum cryptocurrency) making some transaction using blockchain 
technology through Web3 which is going to actually allow us to interact with MetaMask(wallet)
interacting with accounst on MetaMask.



## Installation

Install Node.js -  https://nodejs.org/en/

Install truffle - https://www.npmjs.com/package/truffle   - npm install -g truffle

Install MetaMask - https://metamask.io/

Install Ganache - https://trufflesuite.com/ganache/ - click on quick start to test a network up 
and running to hook up to be deployng all of the Smart Contracts.

    
## Run Locally

Clone the project

```bash
  git clone https://github.com/Luizcampos84/digitalBK.git
```

Go to the project directory

```bash
  cd digitalBK
  
```

Install dependencies

```bash
 Install the project digitalBK -   npm install 
 Install the text editor search for Solidity Extensions - Ethereum Solidity Language
 

 We need to link Ganache with MetaMask it is not going to be automatically set up.

 1 - Open you MetaMesk clik on the right icon, open the Ethereum Mainnet and you
  will be seeing all the tests network names such as (Ropsten, Rinkeby...).
 
 2 - Click on Add Network
 
 3 - Fill the all information - Network name input Ganache, New RPC URL copy from Ganache 
 http://127.0.0.1 , Chain ID input 1337 and click save.

 4 - When you save go to network find Ganache and click on it.

 5 - Go to the terminal search digitalBK folder and run truffle migrate --reset to up date the Ganache address account ("index 1")
 
 6 - Import accounts to Ganache click on line to on Ganache ("index 1" it will be represent the
 account for the customer to hook up to the Ethereum network) click on the key and grab the Private
 key number copy it go to the Metamesk, click on the circle icon on the top right side, choose the
 import account paste it on the Ganache network click on import. You should see that the Ganache,
 We have 100 ether in this account.
 
 7 - Go to terminal and run npm start or yarn start in the digitalBK folder and refresh the browser to see the correct account address and
 100 ether display on the Stake token Balance.
 

```

Start the server

```bash
  npm run start
```


## Tech Stack

**Client:** React, Web3, Truffle, Ganache, Bootstrap, MetaMask.

**Server:** Node.js


## Deployment

To deploy this project run

```bash
  npm run deploy
```

