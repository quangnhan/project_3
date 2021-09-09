1. Smartcontract:

- You should create new contract with my code. Account create contract will become farmer, distributor, retailer and consumer.

- You will need this account to interact with Dapp. Because in function harvestItem in SupplyChain.sol I set onlyFarmer can call to this function, and so another function too.

2. Dapp:

I build this dapp with ReactJS.

Contract code was put in dapp/src/utils/contract.js
You should change contract address with your local contract at contract_address variable.

Run Dapp:

- cd dapp
- npm install
- npm start

In this app I create 4 page /farmer, /distributor, / retailer, /consumer to check, add or renounce a account.
Remember that you have to be a farmer to add new farmer and so on.
Those function in Dapp will connect with current account.

In SupplyChain tag (/supplychain), input all data you need to harvest item with method 1.Harvest. Method from 2.Process, 3.Pack, 6.Ship, 7.Receive, 8.Purchase only need upc to call. 4.ForSale, 5.Buy will need upc and price to execute.

You can you Fectch Data Two to check state and owner after each state.
