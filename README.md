# Unit 21: You sure can attract a crowd! 

The objective is to crowdsale PupperCoin token for fundraising. This requires creating an ERC20 token that will be minted through a Crowdsale contract, leveraged from the OpenZeppelin Solidity library.  This crowdsale contract will manage the entire process, allowing users to send ETH and get back PUP (PupperCoin). This contract will mint the tokens automatically and distribute them to buyers in one transaction.

files: Crowedsale.sol and PupperCoin.sol
Wallet: MetaMask/Account 1 and Account 6
Envivronment: Injected Web3
Network: Ropsten

First we run PupperCoinSaleDeployer by choosing Account1 in metmask and the following values:


![image](images/Picture1.png)


We see the contract has been deployed and we see the token_address and token_sales_address populated:
![image](images/Picture2.png)

We then take the “sale_token_address” and put in the “At Address” and changes the contract to Crowdsale.sol

![image](images/Picture3.png)

And validate that contract has been deployed:

![image](images/Picture4.png)


