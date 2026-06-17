# Value Must Usually Be Zero

In Remix and MetaMask, the Value field sends native ETH with the transaction.

For most contract deployments:
- Value should be 0.
- Do not send ETH unless the constructor is payable.
- If unsure, keep Value at 0.

Sending ETH by mistake can cause loss or failed transactions.
