---
layout: landing
title: Rayonism
---

## TLDR

Merge. Sharding. Specs. Hackathon. Implementation. Testnet.

----

## Roadmap

This is an illustrative roadmap, highly uncertain.
Note that this is a month-long (!!!) **hackathon**.
We are ambitious, and may implement some shortcuts to *ship*.

- March 28: Initial Merge specs land in `dev` eth2.0-specs
- March 29: Rayonism project starts
- Early April: Initial Phase 1 refactor lands in eth2.0-specs, modularizing Sharding
- Early April: target for Eth2-Eth1 devnet following the Merge specs
- April 16: [ETHGlobal Scaling Hackathon](https://scaling.ethglobal.co/) starts
- Mid April: Sharding minimal viable specs target (No Custody Game or Data Availability Sampling)
- During hackathon: develop sharding functionality on top of participating Eth2 clients
- Stretch goal: Initial L2, Optimism-Eth2 prototype
- May 14: Hackathon ends
- Post-hackathon: launch public trial testnet with Merge and Sharding

----

## F.A.Q. &#9728;&#65039;

### What's Rayonism?

A project to that takes the research and engineering efforts of the Eth1-Eth2 Merge and Sharding,
and builds a testnets around the ETHGlobal Scaling Hackathon.

The name is taken from an early abstract art movement with sharding and beacon motives.

And yes, it's a reference to Optimism. The *stretch-goal* (if you didn't think Merge and Sharding are ambitious enough!)
is to build a version of Optimism with shard data. This may spin out as post-hackathon effort.

### How can I help?

#### Non-technical help

You're welcome, although the initial stage of this project is very technical. If you are into UI design or data analysis there may still be good opportunities to help.
If you have different skills, and you are motivated, just open a chat with us :)

#### Dapp help

We are looking to deploy a Merge testnet before fully diving into Sharding.
This means we should have an experimental chain with EVM (and same Geth RPC endpoint) to experiment on around the 2nd half of the Scaling Hackathon.

If you want to experiment with EVM on Eth2 Proof of Stake, and want to be on the bleeding edge by running the Catalyst Geth fork, this is for you.
Note that you can already run local Merge testnets with Teku and Catalyst, don't wait for the public testnet if you want to get started!

More to be announced as the Merge testnet engineering makes progress. 

#### Protocol help

The best way to get started is to read the [Eth1-Eth2 merge specifications](https://github.com/ethereum/eth2.0-specs/blob/dev/specs/merge/beacon-chain.md),
and then look into the latest work by [Mikhail](https://github.com/mkalinin) and [Guillaume](https://github.com/gballet/).

After familiarizing yourself with the Eth2 (consensus) - Eth1 (application) Merge design, join the [#merge](https://discord.gg/nwtbUDHJRc) discord channel for any questions.

From there, we maintain the so called "Meta specs": a fork of the eth2.0-specs that aims to:
- Stabilize Merge changes just enough to target something stable during the hackathon.
  We attempt to keep in sync with the latest changes in upstream, like the eth2.0-specs, but may lock in something temporarily for testnet-shipping.
- Extend with an experimental simplified version of Sharding 
- Coordinate around misc. Hackathon requirements and documentation

The meta specs are in active R&D and unstable until the hackathon starts.
When started, focus will change from spec work to implementation work.

#### L2 Help

On the very very bleeding edge we are re-engineering Optimism to utilize shard data-availability, as a stretch-goal when/if we get some form of Sharding done.
If you are familiar with Optimistic Rollups, reach out and we can prepare updated Optimism specs for a (probably post-hackathon) L2 deployment.  

### Who is participating?

This is collaborative effort between contributors from many teams:
- Merge specs researchers. Mikhail, Guillaume, Vitalik, Danny, protolambda, more
- EF Research team
- Teku, and the Merge-fork of Teku
- Geth, the Catalyst fork
- Lighthouse and Prysm, starting with Merge efforts.
- You?!
