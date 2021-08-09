# Golff Lend（Heco）Tutorial

## What is Golff Lend

Golff Lend is a one-click aggregation lending service that will aggregate with mainstream DeFi lending platforms such as AAVE, Compound, dYdX and others. This will greatly expand the underlying assets available for lending, enhance the liquidity of users' assets, and reduce the cost of borrowing by selecting the best interest rates. At the same time, Golff lending will adopt a new on-chain fee alternative in the future to solve the common problem of high ethereum funding rates, significantly reducing contract call fees and lowering the threshold for user participation.

Navigate to the lending page through Golff's official website (https://golff.finance/) and link to the wallet (currently supports regular wallets such as Metamask, ImToken, BitKeep, Firecoin Wallet, Wheat Wallet, TokenPocket, etc., with Metamask as the example below).

?> Metamask wallet link Heco network tutorial See：[MetaMask wallet configuration HECO tutorial for details](Heco)

## What are the advantages of Golff Lend

- Increase mining mechanism: increase mining revenue, both depositing and borrowing coins can get GOF mining revenue.
	- Users can participate in lending mining when depositing and borrowing coins
	- Heco Golff Lend has a total of 3,480 GOFs per week, which are allocated to each lending pool in different proportions
![image](images/HecoLend/2.png)

- Aggregate lending: V2 will aggregate the mainstream DeFi lending platforms one after another to automatically provide users with the best solution for coin storage and lending rates across the network.
- Lending Vault pool: V3 will combine lending with leveraged Vault pool mining products to maximize users' revenue.

## How to deposit?

The following is an example of how to store USDT: Find the USDT coin in the supply market list, click on it and the USDT deposit pop-up window will appear, the first operation requires authorizing Golff Lend's smart contract to use the USDT coin in your account, click on the "Enable" button, and in the Metamask wallet pop-up window, confirm the authorization. In the Metamask wallet pop-up window, confirm the authorized transaction.

![image](images/HecoLend/1.png)

After confirming, enter the amount of USDT to be deposited in the deposit pop-up window. In the pop-up window, we can see the estimated annualized return, the annualized return of a single coin will increase as the number of coins lent increases, i.e. the higher the usage rate of the coin the higher the annualized return. Click the "Deposit" button after entering the quantity, and confirm the deposit transaction in the Metamask wallet window that pops up.

Once the deposit is successfully made, you will see the balance of your account at the top of the page. At the same time, you will receive a G-Lendtoken in your account, and you will need to redeem your collateral assets through the G-Lendtoken when you redeem.

## How to mortgage?

To lend coins in Golff Lend, you first need to deposit an asset in Golff Lend and pledge that asset, then you can lend other assets. Please note that collateral assets may be subject to seizure in liquidation when the price of the collateral and the lending asset fluctuates.

To mortgage an asset, click on the "Mortgage" switch in the Supply Market list to turn on the mortgage for that currency. Click on "Use USDC as collateral" in the pop-up screen and then confirm the action in the Metamask wallet pop-up window.

At the top of the page you can see the funds deposited and funds lent, as well as the current loanable limit.

## How to borrow?

In the lending marketplace, select the coins you want to lend, click on the list of coins to be lent pop-up, enter the number of coins you want to lend, click on the "Loan" button, and then in the Metamask wallet pop-up window, confirm the operation. After the on-chain operation is completed, you will receive the loaned coins in your wallet.

## How to repay?

Click on the coin you are borrowing in the lending market, select "Repayment" in the pop-up window, enter the amount you want to repay and click the "Repay" button, and confirm the transaction in your Metamask wallet. When the on-chain operation is completed, you will see an increase in the number of tokens available for lending on the page.

After the repayment is completed, you can redeem the collateral, select the coin in the supply market, and select the "Withdraw" operation in the pop-up window, enter the amount to be withdrawn, click the "Withdraw" button, and confirm the transaction in the Metamask wallet. If the asset is being pledged or the amount available for withdrawal is insufficient, the withdrawal operation cannot be performed.

## Liquidation Mechanism

Borrowers are required to pledge certain assets in Golff Lend at the time of borrowing. The amount that borrowers can borrow is determined by the pledge factor, i.e. the loan limit is: value of pledged assets x pledge factor.

When the price of collateral and lending assets fluctuates, the collateral assets may be seized in liquidation. Golff Lend therefore monitors each borrowing account in real time and risks liquidation of a user's lent assets when the lent assets exceed the loan limit.

At this point, the user can trigger the liquidation process as a liquidator and can obtain collateral at a discount. As a result, the borrower repays the loan to the DeFi Lending System, avoiding debt and bad debts on the DeFi Lending Platform, maintaining the solvency of the system, and at the same time, the liquidator gains revenue and the platform is able to operate normally.

For example, user A deposited 10,000U worth of USDT and made a collateralized loan, and lent 5 ETH, when the price of 5 ETH rose to 7500U, user A's asset triggered the liquidation boundary. At this time, liquidator B liquidates this, and he repays 2.5 ETH for user A (the maximum single liquidation limit is 50% of the borrowed amount), and he can get the G-LendUSDT corresponding to the liquidation amount*108%.
