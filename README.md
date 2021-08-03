# blockchainpoa
Ryan Brock
Assignment: Blockchain - Week 18
Summary: Purpose of this assignment is to create a custom blockchain with 2 test nodes deployed on custom test network, and create a MyCrypto wallet to send & confirm a transaction

![NODE 1 2](https://user-images.githubusercontent.com/80288388/128085633-30552234-397c-4cc5-a68f-e701c5006252.png)
1.	Run the following code ./geth --datadir node1/node2 account new to create nodes 1 and 2

2.	Create the a password

3.	Copy the public key and the secret key for both nodes 1 and 2 

![PUPPETH](https://user-images.githubusercontent.com/80288388/128086064-eb7a4887-28d7-48c4-be4d-89bfed76f46b.png)
Run the following code ./puppeth

1.	My network name is "lmcoin"

2.	Configured a genesis block from 'Scratch'

3.	Used Proof of Authority

4.	Used 5 sec. for each block generation

5.	Used address  0x49002 and  0x24F10... to seal the block

6.	Used address 0x49002 and  0x24F10... to pre-fund

7.	No pre-compiled addresses were funded

![CHAIN 333](https://user-images.githubusercontent.com/80288388/128086097-cad7167e-2072-41ad-984a-cac7d7fd61f7.png)
9.	Used 333 for Network id
10.	Exported the genesis block to same folder
11.	Run below command to create the first node

![GETH INIT](https://user-images.githubusercontent.com/80288388/128086123-838fbe0f-5162-4ffa-b784-b46cd313e754.png)
12.	Run below command to initialize the second node
13.	./geth init lmcoin.json --datadir node1
14.	Run below command to setup the second node
15.	./geth init lmcoin.json --datadir node2

![MINE INIT](https://user-images.githubusercontent.com/80288388/128086150-dc50cd55-cf0b-41bd-bd7d-9001f3e0db82.png)
16. mine initiation 
![2 NODE MINE](https://user-images.githubusercontent.com/80288388/128086174-d5566f9b-8a78-4747-963f-44ea016fa039.png)
Mine both nodes using 2 seperate consoles
![CUSTOM NETWORK](https://user-images.githubusercontent.com/80288388/128086183-3390d259-418d-4125-8903-cf1c2d327377.png)

Network Information
•	Network Name: lmcoin
•	Chain ID: 333
•	Blocktime: 5
Accounts:
•	node1 ** password =likeminds1 ** Public address of the key:   0xFb9DAe2cB5B09dcDd0C2c42e25323494cbC5c4Bb
•	Path of the secret key file: node1\keystore\UTC--2021-07-31T22-48-28.193343200Z--fb9dae2cb5b09dcdd0c2c42e25323494cbc5c4bb
•	node2 ** password = likeminds1** Public address of the key:   0xee0D197966930DBc404F4C8E83FE1AE6C6133a61
•	Path of the secret key file: node2\keystore\UTC--2021-07-31T22-50-22.101087400Z--ee0d197966930dbc404f4c8e83fe1ae6c6133a61

