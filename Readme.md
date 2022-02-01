# Udacity-Build-CryptoStar-Dapp-on-Ethereum

#### In this project, the star had been given token name and symbol. Then added functionality to exchange stars and transfer stars. Next, written the test cases for added functions.Finally deployed the smart contract to public Rinkeby network.

#### Truffle v5.4.17, Node v14.17.5, Metamask already have to be installed

    cd app
    # install packages
    npm install --save  openzeppelin-solidity@2.3
    npm install --save  truffle-hdwallet-provider@1.0.17
    npm install webpack-dev-server -g
    npm install web3
```
#### In another window start truffle

      truffle develop
      compile
      migrate --reset
      test

#### All the tests should be passed
 
     ![truffle test]()

#### To run on rinkeby testnet

     truffle migrate --reset --network rinkeby

     ![truffle-migrate]()

#### To start the frontend run from app folder

      npm run dev     

#### Once you create a star it will show the address of the star owner.

      ![Create star: http://localhost:8080/ ]()
       
#### Lookup star will show the owned star name.

      ![Lookup star: http://localhost:8080/ ]()

###  ERC-721 Token Name is TestStarToken

###  ERC-721 Token Symbol is TST

###  Token Address on the Rinkeby Network is 0xf4f2e1a40c976079dcbe10773c22812a171bdcb1


