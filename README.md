Step 1 :- Create a ERC721 smart contract and eploy it on Remix IDE.
Step 2 :- After deployment check the transaction status on the testnet.
Step 3 :- Upload the NFT image that you want make a collection of on the IPFS service provider such as https://nft.storage .
Step 4 :- Create a asset folder on remix ide within the contract folder and add the image that you have uploaded on ipfs .
Step 5 :- Also you have to create a metadata json file for the each image you have uploaded on ipfs.
Step 6 :- Copy the image IPFS URI and paste it in the metadata json file in the "image" field.
Step 7 :- Now upload the metadata json file on IPFS storage and copy it IPFS URI.
Step 8 :- Mint a NFT on your address , give a tokenId and in the _uri field paste the IPFS URI of the metadata json file.
Step 9 :- On confirmation of the transaction go on the the testnet explorer and copy the contract address.
Step 10 :- Go to opensea testnet and copy the contract address and check for your nft collection. 