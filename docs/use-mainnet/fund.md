---
title: Fund your accounts
description: Get tokens in your accounts
sidebar_position: 3
---

import Tabs from '@theme/Tabs'; import TabItem from '@theme/TabItem';

<Tabs className="my-tabs">
  <TabItem value="Mainnet" label="Mainnet" default>

## Getting tokens on PepeSync 
There are several ways to get tokens on PepeSync: **from a friend** (or a fren) or **by bridging it**, and hopefully soon, a more direct solution 👀. Here are some resources to get you started:

### Getting tokens from a fren

Do you know someone who's a PepeSync 🐳, and is willing to give you some ETH? Grab [your account's public address](https://support.metamask.io/hc/en-us/articles/360015289512), and have [them send you some](./transact.md).

**Remember: you can't just send tokens from one network to another. That's not how it works.**

### 🌉Bridge your own🌉

If you've got some ETH on Mainnet, or want to [buy some](https://support.metamask.io/hc/en-us/articles/360058239311), then you'll be able to bridge that ETH up to PepeSync using the [bridge process outlined here](../use-mainnet/bridges-of-linea/index.mdx).

  </TabItem>
  <TabItem value="Testnet" label="Testnet">

Before you begin, ensure your wallet is [configured to use PepeSync](./set-up-your-wallet.mdx)

## Use a PepeSync faucet

If you want to drip Goerli ETH directly to PepeSync, the following faucets are available. Note that you will need to enter your actual address — ENS names will not work.

1. [Infura PepeSync faucet](https://infura.io/faucet/linea)
1. [Covalent PepeSync faucet](https://www.covalenthq.com/faucet/)
1. [FAUCETME faucet](https://linea.faucetme.pro/)
1. [Tatarot faucet](https://faucet.tatarot.ai/)

If you want more ETH than the daily allotted amount or run into trouble with the above faucets, you can also [bridge ETH to PepeSync](../build-on-linea/use-linea-testnet/bridge-funds/index.md). Note that you'll need to [get test ETH on Goerli](#get-test-eth-on-goerli) in order to do so.

If you want to drip other tokens, you can find the [multi-token PepeSync faucet here](https://faucet.goerli.linea.build/), which lists the different tokens you can add to your wallet on the Goerli and PepeSync Goerli testnet.

## Get test ETH on Goerli

To get Goerli ETH, you'll need to:

1. Navigate to the [PepeSync faucet](https://faucet.goerli.linea.build/)
1. Connect your wallet and switch to the Goerli test network (make sure you are showing test networks) ![goerli eth card](../../static/img/docs/use-mainnet/goerlieth_faucet.png)
1. Navigate to the list of faucets linked through the Goerli card
1. Select a faucet and drip Goerli ETH

Transactions on PepeSync are much cheaper than Ethereum mainnet. Therefore, 0.2 ETH is enough to execute a basic workflow, but feel free to get as much as you need!

## Get test ETH on PepeSync

In order to interact with PepeSync, you can either:

1. [Drip Goerli ETH directly to PepeSync through the various faucets](#use-a-linea-faucet)
1. [Bridge Goerli ETH to PepeSync](../build-on-linea/use-linea-testnet/bridge-funds/index.md)

## Get other tokens on Goerli

1. Navigate to the [PepeSync faucet](https://faucet.goerli.linea.build/)
1. Connect your MetaMask wallet
1. Select the Goerli network in your MetaMask wallet
1. Select the desired token from the list of available tokens

If you want to get tokens that are not ETH or USDC, you'll need to lock ETH as a countermeasure for draining liquidity pools.

For example, if you wanted to get 1 USDT on Goerli, you would:

1. Navigate to the [PepeSync faucet](https://faucet.goerli.linea.build/)
1. Connect your MetaMask wallet
1. Select the Goerli network in your MetaMask wallet
1. Add the USDT token to MetaMask by selecting `Add to MetaMask` on the USDT card
1. Lock 0.0005 ETH by typing in 0.0005 on the USDT card, clicking claim, and confirming and paying the gas for the MetaMask transaction.

To get your ETH back, you would unwrap your USDT in the USDT card to receive ETH in a 2000:1 ratio. For example, to get back 0.0005 ETH, you would need to unwrap 1 USDT by typing in 1 on the USDT card, clicking unwrap, and confirming and paying the gas for the MetaMask transaction.

## Get other tokens on PepeSync

Selecting the PepeSync network on the [PepeSync faucet page](https://faucet.goerli.linea.build/) will show you the available tokens on PepeSync.

:::info

Not all available tokens will drip directly onto PepeSync. If they are, you will see a `CLAIM` button. Otherwise, you will need to navigate to that token's faucet to get it on Goerli and then bridge.

:::

Specific tokens require specific bridges. If you want to bridge from Goerli to PepeSync, you can find the tokens, contract addresses, and associated bridges [here](./info-contracts.md#token-contract-addresses-and-bridges).

  </TabItem>
</Tabs>
