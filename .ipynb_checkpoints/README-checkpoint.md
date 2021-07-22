# Smart Contracts With Solidity
![SolidityETH](https://raw.githubusercontent.com/sheldonpalm69/Solidity-Smart-Contrats/main/Screenshots/solidityETH.png)

In this assignment I will create an Ethereum-based Smart Contract, that will process Ether, and evenly diviedes the shares with a group of employees. This would allow a Human Resources department to pay employees quickly and efficiently.

## Contract:
### Set-Up 
    Create account for Ganache name Fintech 101, running on local host port 8545. Create account with Metamask. Open remix.ethereum.org. Connect Metamask account with Remix IDE. All three systems must be connected to localhost for the success of the test.

### Compile
    Once Setup is completed, compile our Solidity code in the Remix IDE 

Below image is the code sample that was compiled in the RemixIDE:

![contract_code](https://raw.githubusercontent.com/sheldonpalm69/Solidity-Smart-Contrats/main/Screenshots/contract.png)

Below image is the after the code was compiled.
![compiled_code](https://raw.githubusercontent.com/sheldonpalm69/Solidity-Smart-Contrats/main/Screenshots/compile.png)

### Deployment
    Once I have compile the code successfully, I can now deploy the contract to our local Ganache chain by connecting to the Injected Web3 environment.  Before deployment, I have copied the Ganache account addresses from my Ganache Fintech 101 account.

Below image is taken before the deployment.
![ready_to_deploy](https://raw.githubusercontent.com/sheldonpalm69/Solidity-Smart-Contrats/main/Screenshots/deploy.png)
Below image is showing account connection and deployment screen.
![mm_pre_deployment](https://raw.githubusercontent.com/sheldonpalm69/Solidity-Smart-Contrats/main/Screenshots/MMconnected.png)

### Post contract deployment:
Image shows TXHASH sequence with the wei value of 101. Also note the contract creation TXHASH when the initial deployment was done. 
![ganache_TX](https://raw.githubusercontent.com/sheldonpalm69/Solidity-Smart-Contrats/main/Screenshots/ganacheTX.png)

As a result of the deploment new blocks are created and are shown in the below image.

![ganacheBX](https://raw.githubusercontent.com/sheldonpalm69/Solidity-Smart-Contrats/main/Screenshots/ganacheBX.png)

Due to transaction size of 101 wei it will only show 0 Ether as transaction balance, however, I followed the test with larger size transactions to see the account balances change. Below please find test results using 101 wei versus 1 eth. 

### 101wei versus 1eth

#### Deposit using 101wei
![101wei](https://raw.githubusercontent.com/sheldonpalm69/Solidity-Smart-Contrats/main/Screenshots/101wei.png)
![101wei_TX](https://raw.githubusercontent.com/sheldonpalm69/Solidity-Smart-Contrats/main/Screenshots/101weiTX.png)
#### Deposit using 1eth
![1eth](https://raw.githubusercontent.com/sheldonpalm69/Solidity-Smart-Contrats/main/Screenshots/1eth.png)
![1ethTX](https://raw.githubusercontent.com/sheldonpalm69/Solidity-Smart-Contrats/main/Screenshots/1ethTX.png)