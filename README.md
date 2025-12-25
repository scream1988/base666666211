# base666666211
Building a Wallet Age Checker
nonce = w3.eth.get_transaction_count(wallet)
if nonce < 5:
    print("New wallet")
