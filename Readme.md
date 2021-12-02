# Proof of Authority Development Chain
## The devlopment of JMcoin

1. Issues persisted when running the puppeth directory as a class. 
2. When utlizing the go etherieum genesis block we faced a chain value error that will be outlined below
3. When Initiatting the puppeth command to start building our network:
   
        ./puppeth
As a class we were met with a few challenges when attempting to activate the mininig operations on our genesis bloc using the puppeth tool

![puppeth attempt 1](https://user-images.githubusercontent.com/87097889/144486611-eb96531f-b5c2-47d1-8c7b-31b6425026f5.png)

![puppeth attempt 2](https://user-images.githubusercontent.com/87097889/144486649-21386074-e7d6-47e2-b661-549a84cca423.png)

![puppeth attempt 3](https://user-images.githubusercontent.com/87097889/144486670-59d81660-2553-4407-8974-4e059f3aaf84.png)

Mining of our first node of jmcoin as shown below was successful. The operation was able to send and recive rewards against the created network 
  ![puppeth mining](https://user-images.githubusercontent.com/87097889/144487465-b872272f-509c-4a5a-a8ae-6feeca93abf7.png)
![puppeth mining2](https://user-images.githubusercontent.com/87097889/144487492-db976881-385e-48de-a553-249444a8b844.png)
![Mining success](https://user-images.githubusercontent.com/87097889/144487627-64998c64-4091-4374-80b3-ed2e29a28bd8.png)


it was the utilization of our second node where we were unable to successfully record transactions as our chain link error occured
note that as I forgot my password to node2 I had to create a third node where it still was unable to create a chain link. 
![puppeth fail message](https://user-images.githubusercontent.com/87097889/144487908-1978a6b8-2203-4731-973f-89d4ba1babc8.png)


Leading to the creation of our blockchain to be utilized over an alternate web based nerwork, Ganache
![blockchain creation](https://user-images.githubusercontent.com/87097889/144488053-4d9a6127-c2c7-4a23-88fb-8aee7bc82158.png)

Once this test network was initiated I utilized MyCrypto Wallet to create and execute a transactions over the network
    
- added the custom node "bootcamp node"
![bootcampnode](https://user-images.githubusercontent.com/87097889/144489116-f0a99584-4bcf-48a2-b3e0-f3a6836fe952.png)

- will enter the first node name in the crossponding box
- network name is "bootcamp node"
- currency is ethereum
- chain ID is the network ID (it forced me to accept 1545) 
- url is  "http:/127.0.0.1:7545"
- click save & use custom nodee

Two accounts were seleceted from the block chain (Ganache) 
![ganache account 1](https://user-images.githubusercontent.com/87097889/144490377-5c637ed5-4dc4-45ec-9346-61b4558dbc7a.png)

![ganache account 2](https://user-images.githubusercontent.com/87097889/144490392-512411d7-14b2-42ac-a40e-9d0b8d6bf89f.png)


Transfered ETH from node to another, check for transaction status
![transaction confirm](https://user-images.githubusercontent.com/87097889/144490454-c7631d31-28b0-4243-a7c6-3f40df68aa7d.png)

![transaction proof](https://user-images.githubusercontent.com/87097889/144490490-5ad7f1d3-3050-4db9-8c1b-aa67951f6094.png)



###  Challenges I faced:

1. node issue preventing me from successfully creating a local blockchain 


### Challenges Solved as follows:
2. created and utlized a blockchain network using the Ganache tool. 


