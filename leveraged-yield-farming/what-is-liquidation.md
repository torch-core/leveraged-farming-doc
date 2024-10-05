# 👻 What is Liquidation

In **Leveraged Yield Farming (LYF)**, you borrow assets to increase your farming position and earn more rewards. But borrowing also introduces **risk**. If the price of the assets you’ve borrowed increases too much compared to your total position value, your **debt rate** (the percentage of debt compared to your total position) rises.

## What is the Debt Rate?

The **Debt Ratio** is your Debt Value divided by the Position Value that measures how much of your position is made up of borrowed funds versus your own funds. For example:

* If you farm with **3x leverage** by borrowing **50 USDT** and **150 USDT worth of stTON**, and your total position is **300 USDT**
* Your debt rate starts with **(50+150)/300** (about 67%)

As token prices fluctuate, the value of the **borrowed assets** changes. If the price of **stTON** increases, the value of the **stTON** you borrowed also rises, causing your **debt rate** to increase. If the debt rate reaches **80%**, you are at risk of **liquidation**.

## What is Liquidation?

**Liquidation** happens when your **debt rate** becomes too high (reaching **80%**). This means that the value of the assets you owe is too close to the value of your entire position, putting your investment at risk.

When the **debt rate** hits **80%**, the system automatically **sells off your assets** to repay the borrowed funds. This protects the platform and prevents further losses by ensuring the debt is paid off before your position loses too much value.

#### Example:

Let’s say you start farming with **100 USDT** and borrow an additional **50 USDT** and **150 USDT worth of stTON**, giving you a total position of **300 USDT**.

* Initially, when the price of **stTON** is **6 USDT**, your **debt rate** is manageable.
* But if the price of **stTON** increases to **11 USDT**, the value of the **stTON** you borrowed rises, pushing your **debt rate** up to **80%**.
* At this point, the system will **liquidate** your position by selling off your assets to repay the loan.

## Why Does Liquidation Happen?

Liquidation occurs to **protect** both you and the platform:

* **For you**: It ensures you don’t lose more than your investment due to market fluctuations.
* **For the platform**: It makes sure the borrowed assets are repaid before the value of your position falls too low to cover the debt.

## What Does This Mean for You?

* **Before Liquidation**: You’re farming with leverage, and everything is safe as long as the token prices remain stable.
* **At Liquidation Point**: If the price of the borrowed asset (like stTON) rises too much, your **debt rate** hits 80%, and the system automatically liquidates your position to repay the borrowed amount. This closes your position and helps prevent bigger losses.
