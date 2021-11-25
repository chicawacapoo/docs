---
description: An overview of the core of MIS fair distribution.
---

# Liquidity Mining

Liquidity Mining is a proven way to attract users to a DeFi platform, and refers to providing and staking liquidity provider tokens in return for yield not just in fee revenue but also in a given platform’s token.&#x20;

We architected Artemis in such way that it works on top of currently existing decentralized exchanges liquidity provider tokens tokens; i.e., say Alice, a retail investor wanting to leverage the power of DeFi, wants to earn MIS on Artemis Earn, to do so, she can pair Wrapped ONE and 1USDC on say, SushiSwap and deposit those tokens on Artemis, in return of yield paid in MIS. With the earned tokens, Alice has now gained access to our Governance, Launchpad and Incubator products, and in a future, to xMIS, a vested version of MIS based on veCRV contracts. It follows then, that by increasing the value, utility, and overall demand of MIS, we can incentivize more participation in the protocol and grow our total value locked.&#x20;

{% hint style="success" %}
Liquidity mining protocols are inherently intensive in token emissions, so Artemis focuses on providing sustainable yields for liquidity providers.
{% endhint %}

Since Artemis aims to build on-chain liquidity while offering stable yield, it follows that Solo Staking (i.e., the staking of a given token in return of yield paid in MIS) is far from being a priority; however, after careful consideration, it holds true that these pools could indeed bring investor interest in our protocol, causing not only an increase in our total value locked, but also generating notice in our protocol's governance and other products for more risk-averse users.&#x20;

MIS tokens are minted on each block once rewards begin. Our total allocation is based on the following rule,

$$
∑ i ≪ ∑ h / (i = allocation(e/pool)∧ h=allocation(e/lp))
$$

Where,

$$
∑ i + ∑ h = 100
$$

It is to be noted that among incentivized liquidity pairs, the allocation destined to native pairs will also be strictly higher than that of non-native ones, consequence of our intention to build liquidity around our governance token, which means that if one was to swap from x token to y token (being y a newly-bridged token), the DEX hosting its liquidity would have to route through MIS, that is

$$
Token(x)⟺MIS⟺Token(y)
$$
