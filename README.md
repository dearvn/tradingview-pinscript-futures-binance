## Some pinescripts to study trading futures on Binance
## Coins to trade ex: C98USDTPERP

Indicators using at here:
`bash
vwap
wma
rsi
`
**SWIDEWAY**
I try some logic to filter sideway at here
if math.abs(close - avg(close[0] ... close[10])) < 0.001 then detecting as sideway case

You can use this strategy candle bar as study case.

Backtest: over 70% accurrate

![Alt text](https://github.com/dearvn/tradingview-pinscript-futures-binance/raw/main/backtest.png?raw=true "backtest")

![Alt text](https://github.com/dearvn/tradingview-pinscript-futures-binance/raw/main/trades.png?raw=true "trades")
