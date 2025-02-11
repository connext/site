---
description: xDai TokenBridges provide multi-chain compatibility and interoperability
---

# Bridges

* [xDai Bridge](converting-xdai-via-bridge/): Bridge from Ethereum to the xDai network designed for the xDai native token. Convert Dai to xDai and bridge xDai to Dai on Ethereum. 
* [Ethereum Omnibridge](omnibridge/): Bridge ERC20 tokens between Ethereum and xDai. 
* [Binance Smart Chain OmniBridge](binance-smart-chain-omnibridge/): Bridge ERC20s between BSC and xDai. Provides beta access to inexpensive interoperability.

{% hint style="success" %}
For In-depth bridge specific documentation, please see the [TokenBridge Docs](https://docs.tokenbridge.net/).
{% endhint %}

With multi-chain bridging, there is a possibility that multiple instances of an underlying asset can be created on a single chain. 

For example, USDT can be bridged to xDai from Ethereum and also bridged to xDai from BSC. This results in 2 separate USDT token instances on xDai. These tokens cannot be merged into a single instance once they are minted. 

A suffix is added to the token name in BlockScout, specifying the origin chain of a bridged token \(ie. from Ethereum, from BSC etc\). Tags indicate a token is bridged, and which chain the token is bridged from. Users can click View Original Token to view the token on the chain of origin.

![Tether on xDai: 1 is bridged from ETH, the other from BSC](../../.gitbook/assets/tether1.png)

Though not available for all tokens \(pairs can be added as community need arises\), swaps are available for certain cross-chain token pairs using [component.finance](https://xdai.component.finance/).  
  
-&gt; [Learn more here](../../about-xdai/project-spotlights/component-finance.md)

{% hint style="info" %}
We are working to further address this issue in a decentralized manner without requiring prior approval to bridge. **Look for more details soon**.
{% endhint %}

