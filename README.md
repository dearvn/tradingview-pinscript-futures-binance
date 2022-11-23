## Some pinescripts to study trading futures on Binance

** Coins to trade ex: C98USDTPERP
** Timeframe: 1m

![Alt text](https://github.com/dearvn/tradingview-pinscript-futures-binance/raw/main/c98.png?raw=true "c98")


Indicators using at here:
`bash
vwap
wma
rsi
`
## SWIDEWAY

I try some logic to filter sideway at here
if math.abs(close - avg(close[0] ... close[10])) < 0.001 then detecting as sideway case

You can use this strategy candle bar as study case.

## BACKTEST

** Over 70% accurrate

![Alt text](https://github.com/dearvn/tradingview-pinscript-futures-binance/raw/main/backtest.png?raw=true "backtest")

![Alt text](https://github.com/dearvn/tradingview-pinscript-futures-binance/raw/main/trades.png?raw=true "trades")
