# FLOW-PROOF-Beginner-Course-submission-Creating-an-NFT
# Project Title
creating the NFT contract and adding the borrowAuthNFT to the given code of contract

# Description
In this project i am going make NFT contarct in which I am going to add function borrowAuthNFT by which the we are going to authorized the borrowAuthNFT using auth keyword.
It is used to get authorized reference. So for example if our NFT have some specific fields besides 'id', we should downcast it using 'as!' to be &NFT type, because &NonFungibleToken.NFT only have that 'id' member. But to downcast it, we need to get authorized reference with 'auth'.
Writting Script for reading the metadata of the NFT.

I have used the nearly same code of Transaction and script which I learned from metaCrafter module and videos of Jacob Tucker.

# Executing
Open the flow playground to code. Copy the code of CyptoPoops and NonFungibleToken as given in modules.
But a change when we add funtion borrowAuthNFT in our code.
Now the exection step are
Deploy: 
1. Deploy NonFungibleToken.cdc at 0x06 
2. Deploy CryptoPoops.cdc at 0x05
3. we now create the collection by deploying Collection.cdc 
4. Execute Mint.cdc transaction with address parameter with 0x05 and fill other parameters
5. Execute ReadScript.cdc with address parameter with the address where the NFT is stored 



# Authors
Contributors names and contact info

Akash Rathod
[@8605akash](https://twitter.com/8605akash)
