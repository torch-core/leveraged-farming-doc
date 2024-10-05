# 🚨 Risks

While we’ve implemented several security measures and regular audits to protect your assets, engaging in **Leveraged Yield Farming** on the **TON blockchain** involves certain risks. Below, we’ll explain some of the key risks that you should be aware of, along with real-world examples to help you understand how they may affect you.

## :left\_facing\_fist: Impermanent Loss (IL)

**Impermanent Loss (IL)** occurs when the price of one or both tokens in a liquidity pair fluctuates, causing your share of the pool to be worth less than if you had just held the tokens. Even **stablecoin pairs** can experience IL if one token loses its peg.

For example, if you provide liquidity to a **tsTON/USDT** pool and the price of tsTON fluctuates, you might end up with more of the less valuable asset when you withdraw. In leveraged farming, this risk is magnified, as you are working with borrowed funds.

### :detective: **How to Protect Yourself**

**Enter and exit when prices are stable**: Timing your entry and exit points carefully can help you avoid large price swings that lead to impermanent loss. By entering and exiting the pool when the prices of both tokens are similar, you reduce the chance of significant IL.

## :left\_facing\_fist: When Borrowing Costs Outweigh Gains

This occurs when the interest rate you’re paying on your borrowed assets exceeds the profits you’re earning from yield farming. This can cause your debt to grow faster than your farming rewards, reducing your equity. If this continues over time, it can lead to liquidation.

Two common causes of negative APY are:

1. **High pool utilization**, which increases borrowing interest rates.
2. A **significant price drop** in the reward token, causing your farming yield to drop.

For example, if you borrow **USDT** to farm with **3x leverage** and the pool utilization rises sharply, pushing your borrowing rate to **20%**, while your farming rewards drop to **15%**, your debt grows faster than your earnings, leading to a negative APY.

### :detective: **How to Protect Yourself**

* If borrow APR turns negative, consider changing strategy to saving account, closing your position, or waiting for market conditions to improve.
* Be cautious when borrowing rates is over 60%, it represents that the pool utilization rate is too high.

## :left\_facing\_fist: Liquidation Risk

In **Leveraged Yield Farming**, you are borrowing assets to increase your farming position. If the value of the borrowed assets rises too much in comparison to your farming position, your **Debt Ratio** will increase. When this ratio reaches the **Liquidation Threshold** (typically 80%), the system will automatically liquidate your position to repay the loan.

For example, let’s say you borrow **50 USDT** and **150 USDT worth of stTON** to create a **300 USDT** position. If the price of stTON rises significantly, your **debt** increases faster than the value of your farming position, pushing your debt ratio toward the **80% liquidation point**. If it crosses this threshold, your position is liquidated.

### :detective: **How to Protect Yourself**

* Actively **monitor your healthy factor**. If it starts dropping too quickly, consider closing your position to avoid liquidation.
* Be mindful of market volatility, and be prepared to adjust your strategy as prices fluctuate.

## 👀 Risk Calculation and Heatmap for Farmers

<figure><img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*qMZFSQA1j1b0tlvqmbXEVQ.jpeg" alt=""><figcaption><p>Relationship between Net Reward APR, Price Change and Impermanent Loss</p></figcaption></figure>

As a farmer, there are multiple factors that you need to consider: **borrowing rates, reward rates, and the impermanent loss caused by price fluctuations**. To help visualize these dynamics, we have created a heatmap that serves as a useful reference for decision-making.

### How to Read the Heatmap

The heatmap is designed to simplify the decision-making process for farmers. Here is a breakdown of the different elements of the heatmap:

* **X-axis**: Represents the changes in price.
* **Y-axis**: Represents the reward rate after subtracting the borrowing rate. We refer to this value as the **Net Reward APR**.
* **Color Gradient**: Indicates the actual APR, taking impermanent loss into account. The redder the area, the higher the actual APR; the bluer the area, the lower the actual returns.

### Opening a Position

When initially opening a position, since the price change is effectively zero, you should focus on the central part of the heatmap. The redder the center, the better the opportunity to open a position. In general, the more red an area is, the more favorable it is to initiate a new position.

### Managing a Position Over Time

After a position has been opened, price fluctuations become more significant, and you need to start factoring in the risk of impermanent loss.

On the heatmap, you may notice a **light blue area**. We call this the **Decision Boundary**. This boundary represents areas where the actual return is approximately zero. If your position lies in a red area, your returns are positive, and the strategy remains profitable. However, if your position moves into a blue area, it is a signal that you might want to consider closing your position and reopening it, effectively resetting the associated risks.

### Key Insights

* **Red Areas**: Favorable for opening or holding a position, as they indicate positive real returns.
* **Blue Areas**: Less favorable for holding a position, indicating that returns are dwindling, and you may want to reopen your position to reset the risk.

By utilizing this heatmap, you can make more informed decisions regarding when to open, hold, or close positions to maximize returns while minimizing risks.

## 📕 Learn more

We have published a Medium article that includes details about risk calculation and control

{% embed url="https://blog.torch.finance/revolutionizing-yield-farming-on-ton-introducing-the-first-leveraged-yield-farming-396928f22158" %}



