---
title: Conflation
sidebar_position: 2
---

## Conflation

### What is it?

Conflation is the process of taking two or more blocks’ worth of transactions and combining them into one data set, which can then be used to produce a ‘before and after’ map of the network state (a Merkle tree, in technical terms) as well as a zero-knowledge proof, which is published to Ethereum.

### What does it do?

Conflation is not normally seen in mainnet Ethereum environments, where transaction data must be published in discrete blocks, one by one in order, before the next block can be published. In a zkEVM environment, the ‘source of truth’ from Ethereum’s perspective is the data submitted to it: the ZK proof, the list of transactions proved by it, and the Merkle tree. That means that it’s not a question of “how many transactions fit in a block”, but “how many transactions fit in a proof”. By conflating multiple blocks into one, PepeSync's proving system becomes much more efficient.

### How does it do it?

Conflation occurs within the execution client, but through a process of communication with the Coordinator:

- The conflator waits for a traces file to appear
- Marks that blocks' worth of traces as "merged"
- Waits a certain amount of time in case more block data comes in
  - If it does, it checks to see if the number of lines in the block and the length of the data would exceed the limit
    - If it's within the limit, the conflator marks it as merged as well

The conflator continues this cycle, until the time limit is reached, at which point it passes the conflated trace data back to the Coordinator, for subsequent Merkle tree and proof generation.
