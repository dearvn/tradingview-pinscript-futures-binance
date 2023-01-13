**If you win, please support me on Paypal: clickclone@gmail.com**

ETHUSDT: 0x269a945fb11642235c1c6ae3fe755ce9d7a50e32
ETHBUSD: 0x269a945fb11642235c1c6ae3fe755ce9d7a50e32

## Trading on Binance

Timeline trading: 6:00AM to 1:00PM

* 2023 Using script `ETHUSDTPERP.txt` to auto bot from tradingview to Binance

* AUTO ALERT ETHUSDTPERP
`ETHUSDTPERP.txt`

## Profit

![Alt text](https://github.com/dearvn/tradingview-pinscript-futures-binance/raw/main/eth1.png?raw=true "01122023")

![Alt text](https://github.com/dearvn/tradingview-pinscript-futures-binance/raw/main/eth2.png?raw=true "01122023")


## History
* 12/14/2022

![Alt text](https://github.com/dearvn/tradingview-pinscript-futures-binance/raw/main/12142022.png?raw=true "12142022")

* 12/13/2022

![Alt text](https://github.com/dearvn/tradingview-pinscript-futures-binance/raw/main/ETHUSDTPERP.png?raw=true "Max DrawDown")


## Some pinescripts to study trading futures on Binance

## BNBUSDTPERP
![Alt text](https://github.com/dearvn/tradingview-pinscript-futures-binance/raw/main/ETHUSDTPERP.png?raw=true "Max DrawDown")


## SOLUSDTPERP
backtest SOLUSDTPERP 82%
![Alt text](https://github.com/dearvn/tradingview-pinscript-futures-binance/raw/main/SOLUSDTPERP.png?raw=true "SOLUSDTPERP")


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

** Over 90% accurately then use `futures-strategy-1m-candles-best.txt`

![Alt text](https://github.com/dearvn/tradingview-pinscript-futures-binance/raw/main/accurrate-90.png?raw=true "accurrate-90")


** Over 70% accurately and filter sideway then use `binance-futures-strategy-candle-bar.txt`

![Alt text](https://github.com/dearvn/tradingview-pinscript-futures-binance/raw/main/backtest.png?raw=true "backtest")

![Alt text](https://github.com/dearvn/tradingview-pinscript-futures-binance/raw/main/trades.png?raw=true "trades")
