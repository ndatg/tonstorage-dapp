# tonstorage-dapp
This example of tonstorage-dapp which allows to create storage contracts between users and provider.

[Dapp interface](https://ndatg.github.io/tonstorage-dapp/)

It is expected that every storage-provider will set up it's own dapp-page to interact with users. Later it is planned to create "unifyed dapp" which allow to interact with all providers and simultaneously ensure replication. 

# How to use it
## Prerequisites
1. You need TON Wallet extension installed
2. If you want to host large file, you need to create Bag and obtain BagId yourself.
## Contract creation
1. Open Dapp
2. If you want to host small files you can add them via "Upload" section otherwise insert BagId into BagId input field.
3. Insert into "Initial balance" input desired amount of TONs
4. Click "Create Contract" button, it will open TON Wallet modal window, confirm transaction
5. Wait till smart contract will be deployed (check progress on timeline)
6. Wait till contract is confirmed by provider  (check progress on timeline)
7. Store storage contract address
## Check storage contract
1. Open manage tab
2. Insert your storage contract address and load data
3. Check actual balance and parameters
4. Top-up balance or cancel contract if you want

