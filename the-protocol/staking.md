---
description: An overview of the core of ALY fair distribution.
---

# Liquidity Mining and Farming

Liquidity Mining is a proven way to attract users to a DeFi platform, and refers to providing and staking liquidity provider tokens in return for yield not just in fee revenue but also in a given platform’s token.&#x20;

We developed Alloy in such way that it works on top of currently existing DEXes LP tokens
For example, Roland is a retail investor wanting to partake in Decentralized finance, and wants to earn ALY in Alloy's farm. To do so, Roland can pair Wrapped FUSE and FUSD on Volt, and then deposit those tokens onto Artemis, and then will recieve the yield paid in ALY tokens. These Alloy tokens give Roaland access to Governance and AlloyPad for future participation in AlloyProtocol.


{% hint style="success" %}
Liquidity mining protocols by definition are intensive in token emissions, so Alloy focuses on providing sustainable yields for liquidity providers.
{% endhint %}

Since Alloy aims to build on-chain liquidity while offering stable yield, it believes that Solo Staking is not a priority; however, after careful consideration, it holds true that these pools could indeed bring investor interest in our protocol, causing not only an increase in our total value locked, but also generating notice in our protocol's governance and other products for more risk-averse users.&#x20;

ALY tokens are minted on each block once rewards begin. Our total allocation is based on the following rule,

$$
∑ i ≪ ∑ h / (i = allocation(e/pool)∧ h=allocation(e/lp))
$$

Where,

$$
∑ i + ∑ h = 100
$$

It is to be noted that among incentivized liquidity pairs, the allocation destined to native pairs will also be strictly higher than that of non-native ones, consequence of our intention to build liquidity around our governance token, which means that if one was to swap from x token to y token (being y a newly-bridged token), the DEX hosting its liquidity would have to route through ALY, that is

$$
Token(x)⟺ALY⟺Token(y)
$$
