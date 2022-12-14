# VU Blockchain smart contract - simple auction

The idea is to create decentralized auction. At the momement contracts is deployed when app is created and assigned to the first account wich is the owner, other accounts can do bids for the auction, if a few conditions are met (bid is higher and auction is still going). After the auction is finished, owner and bidders who are not the highest bidder can withdraw their funds. 

![Auction smart contract work flow](https://user-images.githubusercontent.com/72403454/207725471-21e22363-9b39-43df-ad39-0616282c3c8d.png)

# Run the app

1. Open Ganache
2. In comand line get to the root folder and type "truffle migrate"
3. In comand line proceed to the client folder and type "yarn start"
