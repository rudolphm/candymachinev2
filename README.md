
SPL Token commands
==================
1 Create token
spl-token create-token > token-output.txt 

2 Create account
spl-token create-account 7ZqYRooKrqcijG2Gp5ZJQZtyK9NHiupzDCezch1AefpA --url devnet > account-treasury.txt

3 Check balance
spl-token balance 7ZqYRooKrqcijG2Gp5ZJQZtyK9NHiupzDCezch1AefpA --url devnet

4 Mint 1000 tokens to the treasury account
spl-token mint 7ZqYRooKrqcijG2Gp5ZJQZtyK9NHiupzDCezch1AefpA 1000 5981t8pVM3UFV6aHaUnzz1CLbwjZrYWUSAQhFbq1XRu8 --url devnet

Sugar cli commands
==================
sugar create-config
sugar upload
sugar deploy
sugar verify

spl-token transfer 7ZqYRooKrqcijG2Gp5ZJQZtyK9NHiupzDCezch1AefpA 1 GKocpJ3wAg1JsLPanRRnGeMf8LJ14wp5G3i5WXopJmpo --allow-unfunded-recipient --fund-recipient --url devnet