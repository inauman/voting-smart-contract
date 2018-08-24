# Voting Smart Contract

As part of my [Master in Digital Currencies & Blockchain from University of Nicosia, Cyprus](https://digitalcurrency.unic.ac.cy/about-the-program/); I have created this  Ethereum Smart Contract using Solidity with following requirements:

 - Voting has 3 simple options: 0, 1, 2
 - Only "verfied" addresses can vote
 - Only "owners" can mark the status "verified". 
 - Min 5 tokens are required to be eligible for voting
 - To prevent cheating, mark the address "unverfied" after voting
 - Only 
 - There can be multiple "owners"

## Getting Started

This program is written in Solidity 0.4.24 using [Remix IDE](https://remix.ethereum.org)

Following are the high level steps & functions implemented in this smart contract:

### Step 1: 
Bootstrap the contract with the appropriate values. In addition to the 
contract creator, feel free to add more co-owners.
```
["0x14723a09acff6d2a60dcdf7aa4aff308fddc160c"],1,5
```
### Step 2:
To avoid spam, I have mandated users to have minimum 5 tokens. Use buy() function.

### Step 3: 
Owners can register the voters. As the assignment requirement is only owners can register voters, voter address needs to be passed to the argument
```
"0x4b0897b0513fdc7c541b6d9d7e929c4e5364d2db","0xac","0xee",30 
"0x583031d1113ad414f02576bd6afabfb302140225","0xae","0xeb",35
"0xdd870fa1b7c4700f2bd7f44238821c26f7392148","0xab","0xff",37
```
### Step 4: 
Each verified voter cast their vote for SATOSHI, GREGOR, NAUMAN and so we know the outcome of this election already -:)
```
0
0
0
```

## Acknowledgements
Big thanks to all the people who have taken the time to provide wonderful tutorials, videos, and answered the questions for newbees like me.

### A multi-part series on "Ethereum for Web Developers" by Mahesh Murthy
 [Ethereum for web developers](https://medium.com/@mvmurthy/ethereum-for-web-developers-890be23d1d0c)
