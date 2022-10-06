# Fixed Swap Pools

Seedling will allow projects to list at a fixed price, which will be maintained for as long as there are tokens remaining in the original supply. This should ensure less volatility around a token launch.

It also allows a project and its investors increased transparency over the amount of money raised and tokens sold. This data is not as easily calculable when the tokens sold varies greatly with price volatility.

### **How Liquidity Pools work in AMM Swap Platforms**

A liquidity pool offers users liquidity at any price level. This property is a valuable benefit for projects seeking immediate liquidity for their project’s token. When the token has yet to go through an extended price discovery phase, it is really anyone’s guess as to its value. Thus, when a project creates a new liquidity pair for its protocol token, the initial price swings can be quite volatile, especially when there is less than $100,000 of value in the pool.&#x20;

Each time a user swaps a token with the liquidity pool, the pool’s balance ratio shifts. Let’s say we have a pool that allows you to swap watermelons for grapes. The current rate for swapping watermelons for grapes is one against seven. At the moment, the pool holds 12 watermelons and 80 grapes.&#x20;

Next, Alice swaps one watermelon for seven grapes. Now, the pool consists of 13 watermelons and 73 grapes. To offer liquidity at each price level, the pool needs to maintain an equal value balance (50/50 ratio).&#x20;

Therefore, the smart contract controlling rate will automatically adjust the ratio, so each pool’s value is equal. Let’s divide 73 by 13, which results in the new ratio of 5.61 grapes per watermelon. This new ratio ensures a 50/50 ratio for both currencies in our liquidity pool.

### **Why Use a Fixed Swap Pool?**&#x20;

Fixed swap pools solve three main challenges:

1. Lack of control mechanisms: Unfair token distribution and liquidity rug pulls
2. Prevent token dumps by private investors
3. Reduce token offering costs

As we can see, each time we swap with the liquidity pool, the rate changes. As projects try to launch their token via AMM liquidity pools, a popular token’s price can rapidly increase when plenty of investors buy it. This price increase is caused by the [bonding curve model](https://yos.io/2018/11/10/bonding-curves/) that liquidity pools implement.

For that reason, a fixed swap pool sets a fixed price for token swaps. Projects who want to use the Initial DEX Offering (IDO) model know precisely how much money they’ve raised and how many tokens they’ve sold. They know that their fresh community of token holders has paid a fair price. Conversely, the new token holders can be confident that the value they have contributed will go directly to the development of the project.

Furthermore, projects that pursue the IDO model with fixed swap pools can set additional parameters to gain more control over their fundraising, like controlling the maximum investment per user or the number of investors allowed in the pool. Soft caps and hard caps can be hard coded into the smart contract. Many elements can be crafted to make sure that the new set of token holders is taken care of as equitably and transparently as possible.
