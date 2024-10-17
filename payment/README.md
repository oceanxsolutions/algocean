# Payment
Bundle for depositing coins from Algorand to Botocean.
It watches changes in the Algorand smart contract, for whom who called:
```
deposit_to(amount, botocean_addr)
```
this module will interact with `botocean_accounting` Bundle to increase user's balance.