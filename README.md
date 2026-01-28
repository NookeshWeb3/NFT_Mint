# SessionNFT

## Overview
SessionNFT is a simple ERC721-based NFT smart contract built using OpenZeppelin templates. It allows the contract owner to mint NFTs with custom metadata stored on IPFS(Used Pinata.cloud). This project was developed and deployed on the Monad testnet.

## Features
- ✅ ERC721 implementation using OpenZeppelin
- ✅ Metadata support via `ERC721URIStorage`
- ✅ Ownership-based access control using `Ownable`
- ✅ Minting restricted to contract owner
- ✅ IPFS integration for NFT images and metadata

## Contract Details
- **Name**: PROFILEPICNFT
- **Symbol**: NOOKESH
- **Contract Address**: `0x6db3506cC88861a4aAdc9EbA4215E42C2EFc11F6`
- **Monad Explorer Link**: https://testnet.monadvision.com/token/0x6db3506cC88861a4aAdc9EbA4215E42C2EFc11F6

## How to Mint
1. Upload your image to Pinata.cloud site: https://silver-deep-cockroach-924.mypinata.cloud/ipfs/bafkreigogbiqt5atgrlvbdeskeymnhemmesdck4z2i5ewcxygktpytfpn4
2. Create a `metadata.json` file:
   {
  "name": "Nookesh",
  "description": "Aspiring web3 Developer.",
  "image": "https://silver-deep-cockroach-924.mypinata.cloud/ipfs/bafkreigogbiqt5atgrlvbdeskeymnhemmesdck4z2i5ewcxygktpytfpn4",
  "external_url": "https://github.com/NookeshWeb3",
  "attributes": [
    {
      "trait_type": "Developer",
      "value": "Beginner"
    },
    {
      "trait_type": "GIS Engineer",
      "value": "5 years of experience"
    },
    {
      "trait_type": "Location",
      "value": "Hyderabad"
    },
    {
      "trait_type": "Skills",
      "value": "Autocad, ArcGIS Pro, Smallworld, Python, Solidity"
    }
    


  ]
}
Minting Profile_Pic_NFT on monad testnet by giving "to" address, "tokenID" & "URI" of json file in safemint of deployed transaction in REMIX IDE.

VOLA FInally you can see your minted NFT in Monad testnet Explorer and also in your wallet NFT section with the image you given and the description you provided.
<img width="517" height="767" alt="image" src="https://github.com/user-attachments/assets/c3d98cdb-59c4-42a2-b250-96ac3b5cde21" />


