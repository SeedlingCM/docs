---
description: >-
  Seedling Tokens afford their holders special priority access to investment
  opportunities on the Seedling Launchpad.
---

# Investment Allocations

Users acquire the right to invest in projects listed on the Seedling platform by **locking** their SDLN tokens. The more tokens you lock, and the longer you lock them for, the higher your allocation. Alternatively, users may also **burn** SDLN tokens outright for a one off conversion to investment allocation. Allocation is not transferable and does not expire.

This system is tier-less and deflationary by design, benefiting committed holders while still providing an accessible option for one time users to access a sale with no further commitment.

### Burning SDLN tokens:

Users burn SDLN to obtain 50x the dollar conversion of their burned SDLN as allocation to be spent in one or more projects on the Seedling Launchpad. Burned tokens are irrevocably eliminated from the circulating supply, thus appreciating the value of the remaining SDLN.

### Locking SDLN tokens:

Users who lock their SDLN will receive the same amount of tokens back at the end of the locking term. For the duration of the locking, users will enjoy a monthly investment allocation based on the dollar value of their locked SDLN, and the length of the locking. Find the conversion schedule below:

| Lock Period | Monthly Allocation Multiple |
| ----------: | --------------------------- |
|     1 month | 8x                          |
|    3 months | 10x                         |
|    6 months | 12x                         |
|   12 months | 16x                         |

The SDLN to dollar conversion rate will be updated every hour. Unspent allocations will float with the value of the locked SDLN. If the current price of SDLN is lower than the price at the time of locking, the higher price will be considered.

#### Unlocking SDLN tokens:

Users who have locked SDLN tokens may unlock them before the end of the locking term. If you do so, the allocation accrued so far will be considered as purchased through burning. You will receive your locked SDLN back minus the cost of the allocation you received so far. This amount is calculated with the following formula:

$$
allocatedAmount * ( 0.02 - ( 0.02 / totalLockingPeriod ) * lockingPast )
$$

## Examples

#### 1. Allocation is _cumulative_ and _never expires_

David has 1,000 SDLN, which is worth $100. This price does not change for the next 6 months. David decides to lock all of his SDLN for 6 months. David immediately receives an allocation of $1,200 to invest on any IDO on Seedling. Every 30 days after that David receives an additional $1,200 allocation which David may either use to invest, or accumulate. If David choses on to invest in any project, by the 6th month he will have accumulated $1,200\*6=$7,200 worth of allocation in his account. At the end of the locking period, David will receive his 1,000 SDLN back. He will still have $7,200 allocated to be deployed on any investment of his choosing, whenever.

#### 2. Allocation is priced _dynamically_

David has 1,000 SDLN, which is worth $100. David locks all of his SDLN for 6 months. David immediately received an allocation of $1,200. David decides to hold of investing in an IDO before a great one comes along... 3 months have now passed since David's first locking. He would have had an allocation equivalent to $1,200\*3= $3,600 had the price of SDLN stayed the same. Luckily for David, SDLN is now worth $0.2/SDLN. His locked 1,000 SDLN are worth $200. And so too his available allocation is worth $7,200.

#### 3. Locking price is _guaranteed_

...continued from Example 2: 4 months have passed since David locked his 1,000 SDLN. Unfortunately the price of SDLN rapidly declined. With a price of $0.09/SDLN, his 1,000 tokens are now worth only $90. That's less than what they were worth when David locked them. Luckily, Seedling guarantees the price of locking, therefore his available allocation is not $4,320: it's $4,800!

{% hint style="info" %}
More examples to follow soon!
{% endhint %}
