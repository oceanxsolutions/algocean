# algocean
Algorand integrations on Botocean

# AlgoceanBridge
This is the smart contract bridge between Algorand and Botocean network. 
Users deposit coins to Botocean and withdraw coins from Botocean.

On Botocean network, `AlgoceanBridge` bundle (an application running on Botocean network) that watches changes in the `algoceanbridge` contract, for whom who called `deposit_to(amount, botocean_addr)` this bundle will interact with `Accounting` bundle to increase account's balance on Botocean network.
