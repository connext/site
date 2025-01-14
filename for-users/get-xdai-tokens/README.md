---
description: >-
  xDai tokens are transactional tokens on the xDai chain and also used to pay
  for execution of smart contracts and gas fees.
---

# xDai Token

xDai tokens are used to pay for gas and transactions on the xDai chain. They are a stable token \(worth ~ 1 USD\) created from locked Dai.

{% hint style="info" %}
**STAKE Governance Token Info:**

The xDai ecosystem is a [dual token environment](../../for-stakers/stake-token/stake-reward-mechanics/dual-token-model.md) with the xDai stable token and the STAKE governance token.   
-&gt; [Learn more about STAKE and how to get STAKE](../../for-stakers/stake-token/get-stake/).
{% endhint %}

### **How to get xDai stable tokens**

* From another user on the xDai Chain.
* Converting Dai to xDai using the [xDai Bridge](../bridges/converting-xdai-via-bridge/).
* Purchase directly on [BitMax with the xDai/USDT Pair](https://bitmax.io/en/basic/cashtrade-spottrading/usdt/xdai).
* Purchase directly with fiat using [Ramp.Network](https://ramp.network/buy/?swapAsset=XDAI) or [MtPelerin](https://www.mtpelerin.com/buy-xdai#).
* Trading on [Honeyswap](https://honeyswap.org/) \(you will need a small amount of xDai to start trading\).

### xDai Native Token

xDai is a cryptocurrency created from the [MakerDAO DAI token](https://makerdao.com/). Dai is a stable token on the Ethereum mainnet pegged to the US dollar. xDai can be acquired by users in a number of ways \([for example with a credit card](evernote-html-snippet:///@poa/s/xdai/~/drafts/-MUjaXNW6ZqobKM39Hbv/for-users/get-xdai-tokens/buying-xdai-with-fiat/ramp-network)\) but behind the scenes it is always created from Dai, and the value of xDai corresponds 1:1 with Dai. Here's how xDai is created:

1. Dai is locked into a smart contract on Ethereum. This means it must remain in that contract and cannot be moved until the contract receives a verified signal to unlock it.
2. Using a bridge mechanism called the [TokenBridge](https://docs.tokenbridge.net/), data about the locked Dai is transmitted to a smart contract on the xDai chain.
3. The contract on the xDai chain creates the exact same amount of xDai.
4. This xDai is then usable on the xDai chain. Users only need to switch the chain their wallet is pointing to, and xDai is available using the same Ethereum address.

When users want to exchange xDai for Dai, the process happens in reverse. xDai is burned \(destroyed\) in the xDai chain smart contract, and a verified signal is sent to unlock the exact same amount of Dai on the Ethereum mainnet. The unlocked Dai is then returned to the user’s address on the mainnet.

