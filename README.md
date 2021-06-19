# TAN 

### Description:

A companion token for [TITAN](https://polygonscan.com/token/0xaaa5b9e6c589642f98a1cda99b9d024b8407285a?a=0x69cc04dd3381b4fed0785ccebb0c5bfbecf45365) with a maximum supply of (1,000,000,000 TAN) and zero pre minted tokens. 

TAN will be emitted to users who sacrifice TITAN and all TITAN recieved by the protocol will removed from circulation.

<br></br>

#### The following are the steps necessary to accomplish the task written above:

1. Create an ERC20 contract on ETH chain that mint all the token(TAN)  
2. Bridge it into POLYGON 
3. Create a new smart contract on polygon that gives out TAN token which takes titan as input(burn)
4. Send all TAN tokens to the new smart contract in 3
