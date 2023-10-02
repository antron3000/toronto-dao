# Toronto DAO - ETH Waterloo 2023


This is our hackathon submission to ETH Waterloo 2023 by the Toronto DAO team. 

Our team won 
* 3rd Place Gnosis chain, best use case, for $2000
* 1st Place Nouns DAO - best public goods for $3000 

This code demonstrates a membership signup and a reputation scoring system. Our aim is to build something a little bit more fair and balanced than just 1 membership = 1 vote, or 1 token = 1 vote. 

After siging up, members can earn XP (reputation points) in different fields by making contributions to Toronto DAO. XP tokens influence governance and voting power. 

We also use Sismo Connect for proof of personhood, and proof that the person is from Toronto using zkproofs. This part is not yet completed. 


## In This Repo

### React App

[React App Code](https://github.com/antron3000/toronto-dao/tree/main/ui)

The app lets you sign up for membership on gnosis chain. After you sign up you receive a soul bound ERC721 NFT. 


### Smart Contracts

* DAOMembership Contract (ERC721), for non-transferrable memberships
* ERC6551 Registry, so each DAO member can create a smart contract wallet to hold Reputation points, badges, Tokens & NFTs
* DAO Tokens - Proposed tokens to be used in Toronto DAO
    * Gov Token - Governance XP Token
    * Fin Token - Finance XP Token
    * General Token - General XP Token
    * Tech Token - Tech XP Token
    * Donation Token - XP Token to measure donations
    * Health Token - XP Token for Health Initiatives


