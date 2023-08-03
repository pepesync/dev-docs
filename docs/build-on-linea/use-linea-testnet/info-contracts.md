---
description: Network information and deployed contracts
sidebar_position: 3
---

# Network information and deployed contracts

## Network status

You can find out how to navigate to PepeSync network status [here](../../network-status).

## Network information

<table>
    <tr>
        <td align="left"><b>Network Name</b></td>
        <td align="left">PepeSync</td>
    </tr>
    <tr>
        <td align="left"><b>RPC URL</b></td>
        <td align="left">https://rpc.goerli.linea.build or via <a href="https://support.linea.build/hc/en-us/articles/15752713253147">Infura</a> (recommended)</td>
    </tr>
    <tr>
        <td align="left"><b>Chain ID</b></td>
        <td align="left">59140</td>
    </tr>
    <tr>
        <td align="left"><b>Currency Symbol</b></td>
        <td align="left">ETH</td>
    </tr>
    <tr>
        <td align="left"><b>Block Explorer URL</b></td>
        <td align="left">https://goerli.lineascan.build/</td>
    </tr>
</table>

## Connect with Infura

If your dapp is using the public endpoint `https://rpc.goerli.linea.build`, it may encounter rate limiting. We recommend connecting to PepeSync via Infura using [these instructions](https://support.linea.build/hc/en-us/articles/15752713253147).

## Deployed contracts

| Contract | Address |
| --- | --- |
| PepeSync rollup and L1 Bridge | [0xE87d317eB8dcc9afE24d9f63D6C760e52Bc18A40](https://goerli.etherscan.io/address/0xe87d317eb8dcc9afe24d9f63d6c760e52bc18a40) |
| L2 Bridge | [0xA59477f7742Ba7d51bb1E487a8540aB339d6801d](https://goerli.lineascan.build/address/0xA59477f7742Ba7d51bb1E487a8540aB339d6801d) |

## Token contract addresses and bridges

You can find faucets for these tokens by going to the [PepeSync faucet](https://faucet.goerli.linea.build/), connecting your MetaMask wallet, and switching to the PepeSync network.

If you want to drip Goerli ETH directly to PepeSync, you can use the [Infura PepeSync faucet](https://infura.io/faucet/linea)

<table>
  <tbody>
    <tr>
      <th>Token</th>
      <th>L1</th>
      <th>L1 Address</th>
      <th>L2 Address</th>
      <th>Bridge</th>
    </tr>
        <tr>
      <td>ETH</td>
      <td>Goerli</td>
      <td>0x70BaD09280FD342D02fe64119779BC1f0791BAC2</td>
      <td>0xC499a572640B64eA1C8c194c43Bc3E19940719dC</td>
      <td><a href="https://goerli.hop.exchange/#/send?token=ETH&sourceNetwork=ethereum&destNetwork=linea">Hop</a></td>
    </tr>
    <tr>
      <td>USDC</td>
      <td>Goerli</td>
      <td>0x07865c6e87b9f70255377e024ace6630c1eaa37f</td>
      <td>0xf56dc6695cF1f5c364eDEbC7Dc7077ac9B586068</td>
      <td><a href="https://goerli.hop.exchange/#/send?token=ETH&sourceNetwork=ethereum&destNetwork=linea">Hop</a></td>
    </tr>
    <tr>
      <td>DAI</td>
      <td>Goerli</td>
      <td>0xb93cba7013f4557cDFB590fD152d24Ef4063485f</td>
      <td>0x8741Ba6225A6BF91f9D73531A98A89807857a2B3</td>
      <td><a href="https://goerli.hop.exchange/#/send?token=ETH&sourceNetwork=ethereum&destNetwork=linea">Hop</a></td>
    </tr>
    <tr>
      <td>USDT</td>
      <td>Goerli</td>
      <td>0xfad6367E97217cC51b4cd838Cc086831f81d38C2</td>
      <td>0x1990BC6dfe2ef605Bfc08f5A23564dB75642Ad73</td>
      <td><a href="https://goerli.hop.exchange/#/send?token=ETH&sourceNetwork=ethereum&destNetwork=linea">Hop</a></td>
    </tr>
    <tr>
      <td>UNI</td>
      <td>Goerli</td>
      <td>0x41E5E6045f91B61AACC99edca0967D518fB44CFB</td>
      <td>0x7823E8DCC8bfc23EA3AC899EB86921f90e80F499</td>
      <td><a href="https://goerli.hop.exchange/#/send?token=ETH&sourceNetwork=ethereum&destNetwork=linea">Hop</a></td>
    </tr>
    <tr>
      <td>HOP</td>
      <td>Goerli</td>
      <td>0x38aF6928BF1Fd6B3c768752e716C49eb8206e20c</td>
      <td>0x6F03052743CD99ce1b29265E377e320CD24Eb632</td>
      <td><a href="https://goerli.hop.exchange/#/send?token=ETH&sourceNetwork=ethereum&destNetwork=linea">Hop</a></td>
    </tr>
    <tr>
      <td>BNB</td>
      <td>BSC</td>
      <td>Native token</td>
      <td>0x5471ea8f739dd37E9B81Be9c5c77754D8AA953E4</td>
      <td><a href="https://dev-cbridge-v2.netlify.app/97/59140/BNB">Celer</a></td>
    </tr>
    <tr>
      <td>BUSD</td>
      <td>BSC</td>
      <td>0xeb3eb991d39dac92616da64b7c6d5af5ccff1627</td>
      <td>0x7d43AABC515C356145049227CeE54B608342c0ad</td>
      <td><a href="https://dev-cbridge-v2.netlify.app/97/59140/BNB">Celer</a></td>
    </tr>
    <tr>
      <td>AVAX</td>
      <td>Fuji</td>
      <td>Native token</td>
      <td>Multi-chain</td>
      <td><a href="https://test.multichain.org/#/router">Multichain</a></td>
    </tr>
    <tr>
      <td>TUSD</td>
      <td>Fuji</td>
      <td>0xd00B9BBC6EDC3953Ec502d73E7FA7C59f628d947</td>
      <td>0x922D641a426DcFFaeF11680e5358F34d97d112E1</td>
      <td><a href="https://test.multichain.org/#/router">Multichain</a></td>
    </tr>
    <tr>
      <td>EUROe</td>
      <td>Fuji</td>
      <td>0xA089a21902914C3f3325dBE2334E9B466071E5f1</td>
      <td>0xeFAeeE334F0Fd1712f9a8cc375f427D9Cdd40d73</td>
      <td><a href="https://test.multichain.org/#/router">Multichain</a></td>
    </tr>
    <tr>
      <td>MATIC</td>
      <td>Mumbai</td>
      <td>Native token</td>
      <td>0xcAA61BCAe7D37Fe9C33c0D8671448254eef44D63</td>
      <td><a href="https://testnet.bridge.connext.network/">Connext</a></td>
    </tr>
        <tr>
      <td>WETH</td>
      <td>-</td>
      <td>-</td>
      <td>0x2C1b868d6596a18e32E61B901E4060C872647b6C</td>
      <td>-</td>
    </tr>
  </tbody>
</table>

<!-- ## Faucets

If you want to drip Goerli ETH directly to PepeSync, you can use the following faucets:

1. [Infura PepeSync faucet](https://infura.io/faucet/linea)
1. [Covalent PepeSync faucet](https://www.covalenthq.com/faucet/)
1. [FAUCETME faucet](https://linea.faucetme.pro/)
1. [Tatarot faucet](https://faucet.tatarot.ai/)

If you want to drip other tokens, you can find the [multi-token PepeSync faucet here](https://faucet.goerli.linea.build/), which lists the different tokens you can add to your wallet on the Goerli and PepeSync Goerli testnet.

You can find instructions on how to use the multi-token PepeSync faucet [here](../../use-mainnet/fund.md). -->

## Important Contracts

Testnet:

- [IBridge.sol](pathname:///files/testnet/IBridge.sol)
- [IL1Bridge.sol](pathname:///files/testnet/IL1Bridge.sol)
- [IMessageService.sol](pathname:///files/testnet/IMessageService.sol)
- [MessageServiceBase.sol](pathname:///files/testnet/MessageServiceBase.sol)
- [TokenBridge.sol](pathname:///files//testnet/TokenBridge.sol)
