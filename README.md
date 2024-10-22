# algocean
Algorand integrations on Botocean

# Payment
This is a bundle (an application running on Botocean network) for depositing coins from Algorand to Botocean.
It watches changes in the Algorand smart contract, for whom who called:
```
deposit_to(amount, botocean_addr)
```
This bundle will interact with `Accounting` bundle to increase account's balance.
