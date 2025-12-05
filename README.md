# base4s
Tracking Wallet Health and Activity in Base for Analytics
You can evaluate wallet activity using simple metrics:

inbound/outbound transfers

unique contracts interacted with

stablecoin flows

Python: count unique interactions

logs = w3.eth.get_logs({"fromBlock": "0x0", "address": user})
print("Events:", len(logs))
