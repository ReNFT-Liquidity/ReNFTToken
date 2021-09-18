### RNFT.sol  --> RNFT ERC20 CONTRACT

```
A: Provide erc20 standard protocol method (transfer, balance, authorization, total amount);
B: The contract include an owner Owner, you can change the owner
C: Provide additional issuance function, can set up and change the mint;
D: Provides the destruction function, can set up and change the mint;
E: Provide the function of increasing and decreasing the amount of authorization;
F: Provide batch airdrop distribution function;
```

### TokenVesting.sol --> lock contract

```
A: Support cliff lock time, unlock according to the interval ratio;
B: Support lock-up recovery. For example: the beneficiary is the original shareholder and withdraws before the lock-up period. The project owner can recover the remaining locked amount.
C: Support expired unlocking, called and released by the beneficiary;
```





