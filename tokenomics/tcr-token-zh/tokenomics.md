# Tokenomics

> TCR is a governance token only.&#x20;

For the avoidance of doubt, the TCR token provides no ownership, financial or economic rights of any kind. That being said, governors can always vote to change the token model.&#x20;

### Research

#### Vote-Escrow

One proposed change is a veTCR model. In this model, governors can choose to lock TCR, tTCR, or other TCR derivatives for up to 4 years in return for non-transferable governance rights (veTCR).

The model uses the formula:&#x20;

$$
veTCR= TCR\frac{p_w}{208}
$$

where $$p_w$$ is an integer $$\ge1$$ and $$\le208$$, representing a lock-up period in weeks.&#x20;

veTCR holders are able to direct TCR liquidity mining rewards to Pools of their choice, using a gauge voting model. This encourages protocols to acquire veTCR and direct incentives to Pools that settle with their assets.&#x20;

When the vesting period has ended, veTCR can be redeemed for TCR.&#x20;

See more:

{% embed url="https://tracer.finance/radar/tracer-tokenomics" %}

#### Convertible Allocation&#x20;

Another proposed change is a two-token 'convertible allocation' model for TCR distribution. In this model, gTCR + jTCR = TCR, where gTCR is a non-transferable governance right and jTCR is a non-transferable right to convert gTCR to TCR.&#x20;

gTCR has the same voting power as TCR.&#x20;

A governor is given the full allocation of gTCR immediately, along with a seed amount (1%) of jTCR. The rest of their jTCR balance accrues at a compounding rate, $$r$$, calculated as:&#x20;

$$
r= \sqrt[n]{100} - 1
$$

where $$n$$ is the vesting period in days.&#x20;

The governors balance of jTCR is, then:

$$
jTCR_t=\min(jTCR_{t-1} \times (1+r), gTCR_t)
$$

where $$t$$ is the current time.

At any time, they can redeem jTCR and gTCR together for TCR, so long as their jTCR balance does not fall below 1% of their gTCR balance, excepting when jTCR=gTCR, at which point they can redeem the total amount.&#x20;

See more:

{% embed url="https://medium.com/tracer-dao/realigning-incentives-6dbd3bd4e21e" %}

#### Commitment Voting

RMIT blockchain innovation hub (BIH) have previously proposed to change the TCR voting model. In their proposed model, governors can choose to lock TCR for any amount of time for more voting power.&#x20;

See more:

{% embed url="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3742435" %}
