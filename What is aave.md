2024-06-28 02:15

Status:

Tags: [[AAVE]] [[Blockchain]]


# What is aave
So its a lending platform which works in a pool based strategy. Lenders send money to the pool. Borrows get money from the pool.

The interest rate is decided algorithimically. Less money in the pool = more interest rates.

### Reserve
every pools has reserves in multiple currencies and the total is expressed in ETH which is total liquidity.

There is a concept of *Loan- to- Values* but not understood yet. Every single currency can be borrowed with a stable or a variable rate and every borrow has infinite time with any payment plan.

### Liquidation
So if collatral value goes below certain % they can be liquidated and peps can by it in low price. Every reserve has a liquidation threshold.

so every collataral has a health bar - if it drops below 1 then can be liquidated accordingly.

50% per valid liquidation call. but we must know the acc address also the amount and debt whats their underlying asset and then we can purchase . to purchase we need to have specific amount of balance in our account which is used by our liquidation call to pay off the debt.


### Governance
Each pool is governed by pool's goverance which is under the protocol governance, hierchy shit

### Flash Loans
so like you give a loan **temporalily** to a smart contract and in that transaction it runs a function. if after the execution of the function the contracts returns the loan + fee then txn successful otherwise the txn is reverted.

So like we can check the returned value (just like in normal use cases (require > bla bla stuff))

### Tokenization
You get deposit worth of aTOkens. it grows by interest. 1:1 pegged to underlying token
eg 1 eth = 1 aETH


### Borrow
so every pool has max borrowing power eg eth has 0.8 so 1 eth = 0.8 can borrow per collatral
no time as long as health > 1 

### Lens protocol:

NFT to represent different data ( share data between different social medias) ("NFT wala social media app which provides user with their data)

### STABLE AND VARIABLE INTERRSTS
so stable interest takes the value of the 30 day period of the deposit to search for the interest rate while the variable rate is less time dependent thus it fluctuates very fast. You can go from one to another easily.

### 3 versions of AAVE
why? cuz smart contracts cant be changed. so every single version still remains functional but the newer functions will have better use cases.

specifics not required.



## ***References***
[github.com/aave/aave-protocol/blob/master/docs/Aave_Protocol_Whitepaper_v1_0.pdf](https://github.com/aave/aave-protocol/blob/master/docs/Aave_Protocol_Whitepaper_v1_0.pdf)
-------------------
Linked mentions: