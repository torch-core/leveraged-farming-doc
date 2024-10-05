# 💸 Borrow Interest

When you use leverage, it’s important to remember that borrowing comes with **interest**. Let’s go back to the example:

* You’ve borrowed **50 USDT** and **150 USDT worth of stTON**.
* You will need to pay interest on both these amounts, based on the platform’s interest rate. Let’s assume the interest rate is **5%**.

Here’s how the interest works out:

* For the **50 USDT** you borrowed, you would owe **2.5 USDT** in interest.
* For the **150 USDT worth of stTON**, you would owe **7.5 USDT** in interest.

So, while your total rewards might be **90 USDT worth of TON** (because you’re farming with a **300 USDT** position), you also need to subtract the **10 USDT** in interest (2.5 USDT + 7.5 USDT). This leaves you with a **net profit of 80 USDT worth of TON**.

## Dynamic Borrow Interest: A Balancing Act

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

The borrowing interest rate is **not fixed** — it adjusts based on **demand**.&#x20;

As shown in the chart:

* When the pool's **utilization rate** is low (0-70%), borrowing interest is low.
* As the rate climbs (70-90%), borrowing demand increases, and interest rates rise.
* If utilization goes above **90%**, borrowing interest spikes dramatically due to high demand.

This is common in **Leveraged Yield Farming (LYF)**, where aggressive investors borrow tokens to farm. As more tokens are borrowed, interest rates rise. This higher APR attracts **conservative investors** to deposit, bringing the rates back down.

The system works like a **seesaw**, constantly balancing between aggressive borrowers and conservative depositors, each responding to changes in interest rates.
