---
title: Functions
parent: Systems
nav_order: 5
---

# Function Referances

| Subject | Import Command | Uses |
|---|---|---|
| Import Wallet | `from wallet.wallet import Wallet_Import` | `Wallet_Import(account,mode,password = None)` |

| Send Transactions | `from transactions.send import send` | `send(my_public_key, my_private_key, to_user, password, data=None, amount=None)` |
| Send Coin | `from transactions.send_the_coin import send_the_coin` | `send_the_coin(to_user, coin_amount, password)` |
| Get Transaction History | `from transactions.get_my_transaction import GetMyTransaction` | `GetMyTransaction()` |
