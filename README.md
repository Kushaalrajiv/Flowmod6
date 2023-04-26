# Flowmod6
# NFT Minting

This code provides a basic example of how to mint non-fungible tokens (NFTs) in Candence on the Flow blockchain. 


## Description

This program is a contract written in Cadence(Flow playground). The contract allows you to mint NFTs.First it creates a collection in the account address given by the owner.Then it takes the input from the user like address(where it has to deposit),user name,lucky number,fav food etc. and it mints an NFT.

## Getting started

To use this code to mint your own NFTs on the Flow blockchain, follow these steps:

1)Clone this repository to your local machine.

2)Open the nft-mint.cdc file in your code editor or IDE.

3)Modify the metadata dictionary to include the metadata for your NFTs, such as the name, description, and image URL.

4)Modify the mintNFT function to specify the total number of NFTs you want to mint and the price of each NFT.

5)Save the nft-mint.cdc file.

6)Open a terminal window and navigate to the directory where you cloned this repository.

7)Run the following command to deploy the contract to the Flow blockchain:
flow project deploy

8)Once the contract is deployed, run the following command to mint your NFTs:
flow transactions send ./transactions/mintNFT.cdc

9)Enter your Flow account credentials when prompted.

10)Wait for the transaction to be confirmed on the Flow blockchain.

## License

This code is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.See the LICENSE file for more information.

## Authors

Kushaal Rajiv
@kushaalrajiv@gmail.com
