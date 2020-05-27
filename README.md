# keep-network
All stuff related to KEEP&amp; Stake Capital

## Contracts

Stake Capital KEEP address: https://etherscan.io/address/0xD078f1faE0bddB569309D421D14C34ca49160eBd#tokentxns

## Workers

- Operator 1: 0x1de632bb859b09e016bf189836a00a0d2d791d53
- Staking tx: https://etherscan.io/tx/0xb77dfd0965bc907554f215ee09edf29f444d3da0c589ef7fe4d5c784615e3051

To pay fees: tx from 0x Staking Pool to KEEP worker: https://etherscan.io/tx/0xb18ab061b39d48d07e22fe47972790c63ae4b39ef919b7e0b869965d9b3f065d


## Staking information

1) Go to the token dashboard: https://dashboard.keep.network/
2) Ensure you're Metamask is on the account from the Ledger (with the delegation) and that you're on Mainnet.
3) Click TOKENS -> Delegate Tokens
4) Click the "owned" tab
5) Create delegation with the following values:
    - Beneficiary Address: set this to the address of the Ledger wallet (it will receive the rewards)
    - Operator Address: 0x1de632bb859b09e016bf189836a00a0d2d791d53 (this is the operator address of the node we're running on the instance)
    - Authorizer Address: set this to the address of the Ledger wallet also (must create authorization transaction for operator, but doesn't need to be hot)
6) Submit the transaction
