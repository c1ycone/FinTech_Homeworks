###Blockchain Building Blocks


***Environment Setup & Libraries***

Libraries needed to be installed:
- Create a new Python environment: 
```
conda create -n ethereum python=3.7 anaconda

conda activate ethereum
```
- Clone hd-wallet-derive



- web3.py
```
pip install web3
```
- bit
```
pip install bit
```
---
***Tools***

- Terminal or Git bash
- Download [MyCrypto Application](https://download.mycrypto.com/)
    
    - For this homework, the following was used:
     
        - **Change Network:** Then click "Add Custom Node"
        - **Node Name:** farmm
        - **Network:** Custom
        - **Network Name:** puppethnet
        - **Currency:** ETH
        - **Chain ID:** 334
        - **URL:** http://127.0.0.1:8545

- Dowload [Go Ethereum](https://geth.ethereum.org/downloads/)


---
***Acvitity Overview***

1. Create two nodes with two different account addresses. [ Terminal/Git bash]

2. Generate ***genesis block***, which is the beginning of the chain, by running ./puppeth command and export genesis configurations in .json format. [Terminal/Git bash]


3. Initialize the nodes with genesis files and start mining blocks - Proof of Authority Blockchain. [ Terminal/Git bash]

    - Launch node 1 in mining mode then launch the next nodes, one at a time. 



4. Test the blockchain by sending ETH between two nodes [MyCrypto]


---

***Blockchain Testing Screenshots***

MyCrypto Before
![1](/Screenshots/1._MyCrypto_BEFORE.png)


New genesis block generated.


![2](/Screenshots/2.Terminal_NewGenesisBlockGenerated.png)


Export genesis configurations.
![3](/Screenshots/3.ExportGenesisConfigurations.png)

Node 1 launch.
![4](/Screenshots/4.Node1Launch.png)

Node 2 launch.
![5](/Screenshots/5.Node2LaunchUnlock.png)


####Notes:
Failed to fund the wallet after trying 3 times [network names: farm (1st try), farmm (2nd try), hotel (3rd try with new wallet setup)]. Please see attached Screenshots folder. Thus, was unable to transfer funds to other address.