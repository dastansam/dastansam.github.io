---
layout: page
title: "Portfolio"
permalink: /
---

<style type="text/css">
  .wrapper {
    max-width: -webkit-calc(960px - (30px * 2));
    max-width: calc(960px - (30px * 2));
  }
  strong {
    font-weight: 600;
  }
  hr {
    margin-bottom: 15px;
  }

  li {
    line-height: 30px;
  }

  img[src*="#profile"] {
    width: 15%;
    height: 15%;
    position: relative;
  }
</style>

### Rust Engineer
[GitHub 1](https://github.com/dastansam) | [Github 2](https://github.com/dastanbeksamatov) | [Email](mailto:dastanbeksamatov@gmail.com) | [Linkedin](https://www.linkedin.com/in/dastanbek-samatov-30ab71128/)

![Me](/assets/pfp.jpg)

Rust and Substrate engineer highly interested in cryptography, peer-to-peer networks and blockchain interoperability

# Experience 

**Freeverse, June, 2023 - Present <br> Senior Rust Engineer**

Freeverse, the dynamic NFT infrastructure platform leading the way in creating User Generated Value (UGV) with digital assets. Living Assets™ provide brands and games with new and novel ways to increase revenue while engaging their customers or players like never before.

Role:

- Leading the development of LAOS EVM-based parachain
- Successfully launched a parachain on Kusama: KLAOS
- Designing and developing precompiles, smart contracts and other key EVM features of the chain
- Leading the XCM integration with other parachains
- Researching and building POC trustless bridge between a Substrate solochain and a Polkadot parachain
- Contributing to Polkadot's EVM tech stack `frontier`

---
**Enjin, March, 2021 - September, 2023 <br> Core Rust/Substrate Engineer**

Joined as a core Substrate engineer for formerly [Efinity](https://efinity.io) (now **Enjin Matrixchain**) parachain. Enjin Matrixchain supports NFTs on a protocol level and helps users easily integrate and interact with digital assets in their apps. I helped Enjin to launch its own layer-zero chain and migrate Efinity parachain from Polkadot to Enjin relay chain successfully.

Some highlights:

- Focused on multi-block and lazy storage migrations
- Worked on successfully integrating XCM between parachains in the Polkadot network.
- Researched building trustless bridge for cross-chain token transfers, e.g from Ethereum to Polkadot
- Took active part on implementing and maintaining multi tokens pallet that enables: fungible and non-fungible asset operations at protocol level (core feature of Enjin). Also worked on other trademark pallets (*marketplace*, *fuel tanks*, etc.)
- Took active part in developing staking and nomination pools pallet from scratch
- Led the development of infrastracture/tooling pallets, e.g *emergency mode*, *migrations organizer*, etc.
- Led development of internal tool for easily launching local testnets. Somewhat combination of [`parachain-launch`](https://github.com/open-web3-stack/parachain-launch) and [`zombienet`](https://github.com/paritytech/zombienet).
- Integration and smoke tests for parachain with JS and Python, CI/CD, deployment and debugging of nodes, etc.

---
**Limechain, June, 2020 - February, 2022 <br>Blockchain Developer**

Worked on several projects mostly focused in **Polkadot** ecosystem. Responsible for end-to-end delivery of features, from gathering requirements, to designing solutions to implementing and testing them.

Some highlights:

- Successfully delivered 3 [**Web3 Foundation**](https://web3.foundation/grants/) grants
- Took active part in researching and implementing alternative ways of building Substrate runtimes: [**Subsembly**](https://github.com/LimeChain/subsembly)
- Worked with [**Ink!**](https://paritytech.github.io/ink/) to write WASM smart contracts
- Presented **Subsembly** at **Substrate Seminar** podcast and to Substrate Builders Program
- Designed and implemented developer documentation
- Designed several CI/CD pipelines for testing and building projects/libraries
- Mentoring junior developers
- Reduced gas usage by 50% making a critical fix in Math library
- Designed and implemented end-to-end testing architecture

---
**Personal projects <br> Blockchain Engineer**

This section lists some of my personal and freelance projects.

***Hyperfridge***

The idea of [Hyperfridge](https://github.com/element36-io/hyperfridge-r0) is to create a bidirectional bridge to the TradFi world for blockchain applications, using Zero-Knowledge proofs. Hyperfridge's vision is to create a ZK-based ledger to provide a trustless interfaces to TradFi so that anyone can "plug-in" their own bank-account into the Web3 world, similar as you can do it today with Stripe in the Web2 world, but open-sourced and fully trustless.

Role:

- Leading the development of Substrate [chain](https://github.com/element36-io/ocw-ebics) for resolving fiat transactions on-chain
- Working with Risc-Zero framework to integrate zero knowledge proofs on-chain

*This project is Work In Progress*

***ISO-8583 Polkadot Integration***

Personal project to research possible integration of ISO-8583 standard to Polkadot. Successfully delivered first milestone of the grant to Web3 Foundation.

https://github.com/subclone

***Qaul.net***

[qaul.net](https://github.com/qaul/qaul.net) is an Internet independent wireless mesh communication app. With qaul.net, you can communicate directly from one device to another. I am a part-time Rust and P2p Engineer here and try to help with the development from time to time. My work mostly revolves around integrating [`rust-libp2p`](https://github.com/libp2p/rust-libp2p) library.

---
***Decentralized Auctioned Backends***

For my senior thesis in Computer Science, I worked on a proof-of-concept project on the topic of *managed decentralization*. The project was aimed to explore how enterprises and companies could benefit from blockchain without compromises on privacy and thoroughput.

In the project, the goal was to build a decentralized network of nodes that host a backend for an **NFT Marketplace**. Backend simply serves and matches orders. Marketplace and orders function with the use of **Order Commitments**. 

Consensus of the network is a simple **Auction** protocol smart contract. It is also called a **Proof-of-Donation**. Essentially, whichever node bids the most amount of value to the time slot, will be the winner and **main processor/backend**(validator) at that slot. Nodes are incentivized by commissions from gossiping and matching orders. **Main backend** in a given slot, gets to match all the orders in that slot.

The network and backend was built in **Rust**, consensus and marketplace in **Solidity** and frontend in **React**. Many design and architecture patterns are inspired by **Substrate** and **FileCoin**.

---
**Upwork and Freelance, January, 2020 - Present, <br>Blockchain and Full Stack developer**

Started my programming career as a freelancer and later picked up **Upwork**. Mostly specialize on projects in the blockchain space and provide full cycle development services as well as consultations.

***Substrate chain indexer***

Built personal indexer script for **Substrate** chains. As part of the task, also contributed to open-source library: [**@open-web3js**](https://github.com/open-web3-stack/open-web3.js)

# Education
---

**American University in Bulgaria, Sep 2017 - Dec 2021, BSc in Computer Science**

- Minor in Math (several advanced Math classes taken)
- First place at university Math contest among Math department students
- Participant of computational olympiads
- Senior thesis with **excellent** mark

# Activities
---

- 2 times winner of **AUBG Soccer League**

# Languages and technologies
---

- Confident: **Rust**, **NodeJs**, **Solidity**, **Substrate**, **Python**, **React**, **AssemblyScript**
- Some experience: **C++**

# Open source contributions
---

- [Enjin](https://github.com/enjin)
- [LAOS](https://github.com/freeverseio/laos)
- [Hyperfridge chain](https://github.com/element36-io/ocw-ebics)
- [Hyperfridge-risc0](https://github.com/element36-io/hyperfridge-r0)
- [qaul.net](https://github.com/qaul/qaul.net)
- [open-web3-js](https://github.com/open-web3-stack/open-web3.js)
- [Zombienet](https://github.com/paritytech/zombienet)
- [Subsembly](https://github.com/LimeChain/subsembly)
- [AssemblyScript SCALE Codec](https://github.com/LimeChain/as-scale-codec)
- [polkadot-sdk](https://github.com/paritytech/polkadot-sdk)
