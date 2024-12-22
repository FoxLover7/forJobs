gas_price = 19
gas_limit = 20000
transaction_cost = gas_price * gas_limit / 10**9

print(f"Стоимость газа {gas_price} гвей")
print(f"Стоимость транзакции {gas_limit} газа умноженные на {gas_price} гвей равно {transaction_cost} эфира")
