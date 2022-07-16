# 🏗 cheese-touch-eth | Tristan & George

## Getting Started - download this project by following the following steps



  First, clone the repo to your local machine with 
  ```sh 
  git clone https://github.com/tristann3/dapps-final
  yarn install
  yarn chain
  ```

  You can start the web server by using 
  ```
  yarn start
  ```

  Open http://localhost:3000 to see the app

## Cheese Touch NFT

This is a final project developed as a proof-of-concept of the blockchain and using existing libraries to deploy and create our own smart contracts. We used inspiration from Speed Run Etherium to lay out a beautiful front end, the rest was up to us to modify the smart contract to our conditions.

Cheese touch NFT was designed so that only one token can be 'live' at one time. Nobody wants the cheese touch...its stinky. Once the NFT is created, the token has a timer. If the token gets minted or transfered, the timer was then reset. If the NFT does not get transfered within 24 hours, the NFT would be destroyed, and any user on the blockchain could create the Cheese Touch NFT.

## Our Progress

We initially developed this project to see how we could create a roulette-style blockchain, where users could mint an item at a gamble. You would want to avoid minting a bad NFT, but for the most part, you should be good. Using percentage based minting logic seemed simple at the time. As we ran into development issues, we decided to land on the cheese touch idea which was presented to us in class. 

We were able to get 2 out of the 3 objectives completed for this project, we were able to modify the front-end UI by manipulating the data on the smart contract, including the metadata.

The second objective we completed was we were able to deploy our smart contract after making extensive changes to the architecture, like including time-based logic to determine wether or not a NFT is able to be made, and by searching the blockchain for any existing NFTs.

Our stretch goal for this project would be to implement the Health attribute we included in our metadata of the NFTs.