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

### Senior Software Engineer
[GitHub 1](https://github.com/dastansam) | [Github 2](https://github.com/dastanbeksamatov) | [Email](mailto:dastanbeksamatov@gmail.com) | [Linkedin](https://www.linkedin.com/in/dastanbek-samatov-30ab71128/)

![Me](/assets/pfp.jpeg#profile)

Experienced Rust and Substrate engineer highly interested in peer-to-peer networks, blockchain interoperability and cryptography.

# Experience 

**Freeverse, June, 2023 - Present <br> Senior Rust Engineer**

Freeverse, the dynamic NFT infrastructure platform leading the way in creating User Generated Value (UGV) with digital assets. Living Assets™ provide brands and games with new and novel ways to increase revenue while engaging their customers or players like never before.

---
**Enjin, March, 2021 - September, 2023 <br> Core Rust/Substrate Engineer**

[Efinity](https://efinity.io) parachain supports NFTs on a protocol level and helps users easily integrate and interact with NFTs. I focus on pallet and runtime development with Substrate on **Efinity** parachain. As part of the core enginnering team, actively participate in discussions, code reviews and writing specs.

Some highlights:

- Led research on storage migration modes, implemented proof-of-concept template for multi-block and lazy storage migrations
- Co-led the work on integrating XCM to our parachain and building trustless bridge for cross-chain token transfers
- Took active part on implementing and maintaining multi tokens pallet that enables: fungible and non-fungible asset operations at protocol level (core feature of Efinity). Also worked on other trademark pallets (marketplace, fuel tanks, etc.)
- Took active part in developing staking pallet from scratch
- Led the development of pallet that enables filtering transactions and putting chain on emergency mode
- Co-led development of internal tool for easily launching local testnet. Somewhat combination of [`parachain-launch`](https://github.com/open-web3-stack/parachain-launch) and [`zombienet`](https://github.com/paritytech/zombienet). Also worked on maintaining and improving CI/CD tools
- Research and implement relay chain specific features
- Helped troubleshooting and debugging errors of nodes
- Integration and smoke tests for parachain with JS and Python

---
**Limechain, June, 2020 - February, 2022 <br>Blockchain Developer**

Part of several projects mostly focused in **Polkadot** ecosystem. Responsible for end-to-end delivery of features, from gathering requirements, to designing solutions to implementing and testing them.

Some of the highlights of my time at Limechain:

***Lending Protocol***

- Implementing, writing and testing smart contracts in [**Ink!**](https://paritytech.github.io/ink/) smart contract language
- Led development of math library - essential for calculations
- Reduced gas usage by 50% making a critical fix in the implementation of wrapper types
- Designed and implemented developer documentation
- Designed several CI/CD pipelines for testing and building projects/libraries
- Mentoring junior developers and code reviewing

***Subsembly and AssemblyScript runtime***
- Successfully delivered 2 [**Web3 Foundation**](https://web3.foundation/grants/) grants
- Completed proof-of-concept project on building **WASM** runtime in **AssemblyScript**
- Worked on design and implementation of library for building **Substrate WASM** runtimes in **AssemblyScript** - **Subsembly**
- Closely worked and interacted with **Substrate** source code
- Designed and implemented end-to-end testing architecture
- Presented **Subsembly** at weekly **Substrate Seminar** podcast
- Part of **Substrate Builders Program**

***SCALE Codec in AssemblyScript***
- Core developer and maintainer
- Writing unit and benchmark tests
- Documentation

---
**Personal projects <br> Blockchain Engineer**

This section lists some of my personal and freelance projects.

***Fiat on-off ramp***

A **Web3 Foundation** grant that aims to connect banking interfaces with **Polkadot** ecosystem. I am responsible for building **Substrate** offchain-worker pallet, writing tests, as well as maintaining the project. For more information about it, refer to the original grant proposal [here](https://github.com/w3f/Grants-Program/blob/master/applications/FIAT-on-off-ramp.md).

*This project is Work In Progress*

***ISO-8583 Polkadot Integration***

Work in progress.

https://github.com/subclone

***Qaul.net***

[qaul.net](https://github.com/qaul/qaul.net) is an Internet independent wireless mesh communication app. With qaul.net, you can communicate directly from one device to another. I am a part-time Rust and P2p Engineer here and try to help with the development from time to time. My work mostly revolves around [`rust-libp2p`](https://github.com/libp2p/rust-libp2p) library.

---
***Decentralized Auctioned NFT Marketplace***

For my senior thesis in Computer Science, I worked on a proof-of-concept project on the topic of *managed decentralization*. The project was aimed to explore how enterprises and companies could benefit from blockchain without compromises on privacy and thoroughput.

In the project, the goal was to build a decentralized network of nodes that host a backend for an **NFT Marketplace**. Backend simply serves and matches orders. Marketplace and orders function with the use of **Order Commitments**. 

Consensus of the network is a simple **Auction** protocol smart contract. It is also called a **Proof-of-Donation**. Essentially, whichever node bids the most amount of value to the time slot, will be the winner and **main processor/backend**(validator) at that slot. Nodes are incentivized by commissions from gossiping and matching orders. **Main backend** in a given slot, gets to match all the orders in that slot.

I successfully delivered and demonstrated my proof-of-concept project and received and exceptional grade. Final version of the project is raw and it is still work in progress. Some of the key issues need to be addressed before any production grade usage.

The network and backend was built in **Rust**, consensus and marketplace in **Solidity** and frontend in **React**. Many design and architecture patterns are inspired by **Substrate** and **FileCoin**.

---
**Upwork and Freelance, January, 2020 - Present, <br>Blockchain and Full Stack developer**

Started my programming career as a freelancer and later picked up **Upwork**. Mostly specialize on projects in the blockchain space and provide full cycle development services as well as consultations.

***Substrate chain indexer***

Built personal indexer script for **Substrate** chains. As part of the task, also contributed to open-source library: [**@open-web3js**](https://github.com/open-web3-stack/open-web3.js)

***Crypto and Fiat price indexer***

Tool for indexing daily prices of cryptocurrencies and fiat. Open source.

# Education
---

**American University in Bulgaria, Sep 2017 - Dec 2021, BSc in Computer Science**

- Minor in Math
- First place at university Math contest among Math department students
- Participant of computational olympiads
- Subject tutor and student assistant in **Java**
- Senior thesis with **excellent** mark

# Activities
---

- 2 times winner of **AUBG Soccer League**

# Languages and technologies
---

- Confident: **Rust**, **NodeJs**, **Solidity**, **Substrate**, **Ink!**, **Python**, **React**, **AssemblyScript**, **git**  
- Some experience: **C++**, **Solana**, **CosmosSDK**, **AWS**  
- Interested: **ML**, **AI**

# Open source contributions
---

- [Enjin](https://github.com/enjin)
- [LAOS](https://github.com/freeverseio/laos)
- [qaul.net](https://github.com/qaul/qaul.net)
- [open-web3-js](https://github.com/open-web3-stack/open-web3.js)
- [Zombienet](https://github.com/paritytech/zombienet)
- [Subsembly](https://github.com/LimeChain/subsembly)
- [AssemblyScript SCALE Codec](https://github.com/LimeChain/as-scale-codec)
- [OCW Ebics](https://github.com/element36-io/ocw-ebics)
