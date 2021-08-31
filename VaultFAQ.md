# Golff Vault FAQ

## What is G-HecoToken

G-HecoToken is the same as G-V2Token is the same as Golff Vault V2, the equity Token of Golff Vault.

## Why don't I get 1 G-HecoUSDT when I deposit 1 USDT in the Vault pool?

Since Golff Vault Pool uses a principal-less strategy, the proceeds of the target pool will be automatically converted to costcoin Tokens by the contract, and the more Tokens a user can redeem by virtue of G-HecoToken due to the ongoing proceeds put into the pool, while the number of G-HecoTokens remains the same. So the exchange rate between Token and G-HecoToken is not a 1:1 relationship, G-HecoToken is a collateralized share warrant and each G-HecoToken has a unit net value.

Net value per unit formula: 
```
Net value per unit = cumulative number of Tokens in the current pool / cumulative number of G-HecoTokens issued
```
G-HecoUSDT has a unit equity of 1.1, so if you deposit 10,000 USDT you will get: 
```
10000 USDT/ 1.1 = 9090.9 G-HecoUSDT
```


## Automatic reinvestment and compound interest mechanism

Automatic reinvestment can be simply understood as a mechanism by which the Vault pool will automatically withdraw and reinvest the earnings from the target pool, thus achieving earnings reinvestment to generate more earnings. As the conventional target income is fixed income, i.e. the invested principal is fixed, and the income output is also fixed under the condition that the yield remains unchanged. Automatic reinvestment, on the other hand, can automatically withdraw the income within a certain period of time and reinvest it as the principal, thus achieving the purpose of increasing the income.

For example, if the target fixed annualized rate of return is 50%, if the reinvestment is done on a daily basis, the annualized rate of return would be
```
(1+50%/365)^365 - 1 = 64.8%
```

## Why there is no revenue increase in a short period of time after deposit

The proceeds of the Vault pool need to be settled with Harvest. At present, the Vault pool has just been launched and the settlement trigger period is long, so the proceeds are not settled in real time and there may be no proceeds for a short period of access. Therefore, please wait patiently for the settlement of earnings after depositing funds, and you can see the change of earnings.