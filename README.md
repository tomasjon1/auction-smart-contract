# VU Blockchain smart contract - simple auction
This contract is aims to create decentralized lottery, which cannot be rigged by design. For now, this contract allows only two players to participate. If player wants to join, he must provide his number guess - either 0 or 1. When both numbers are provided, the contract generates a winner based on pseudo-random numbers.

The idea is to create decentralized auction. At the momement contracts is deployed when app is created and assigned to the first account wich is the owner, other accounts can do bids for the auction, if a few conditions are met (bid is higher and auction is still going). After the auction is finished, owner and bidders who are not the highest bidder can withdraw their funds. 

![Auction smart contract work flow](https://user-images.githubusercontent.com/72403454/207725471-21e22363-9b39-43df-ad39-0616282c3c8d.png)
