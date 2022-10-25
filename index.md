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

### Blockchain and Full Stack Developer
[GitHub 1](https://github.com/dastansam) | [Github 2](https://github.com/dastanbeksamatov) | [Email](mailto:dastanbeksamatov@gmail.com) | [Linkedin](https://www.linkedin.com/in/dastanbek-samatov-30ab71128/)

![Me](/assets/pfp.jpeg#profile)

Experienced Substrate and web3 developer highly interested in peer-to-peer networks, blockchain scalability and interoperability.

# Experience 
**Efinity, March, 2021 - Present <br> Rust/Substrate Engineer**

[Efinity](https://efinity.io) parachain supports NFTs on a protocol level and makes it easy game studios to easily integrate NFTs and ordinary users to interact with them. I focus on pallet and runtime development with Substrate on **Efinity** parachain. As part of the core enginnering team, actively participate in discussions, code reviews. Efinity is not open source yet.

Some highlights:

- Developed pallet that enables filtering transactions and putting chain on emergency mode
- Led research on storage migration modes, implemented proof-of-concept template for multi-block and lazy storage migrations
- Took active part on implementing and maintaining pallet that enables NFT operations at protocol level (core feature of Efinity). Also worked on other trademark pallets (marketplace, fuel tanks, etc.)
- Co-led development of internal tool for easily launching local testnet. Somewhat combination of `parachain-launch` and `zombienet`. Also worked on maintaining and improving CI/CD tools
- Helped in XCM integration and simulation tests
- Helped troubleshooting and debugging issues with running testnet parachain on Rococo
- Wrote integration and smoke tests for parachain with JS and Python

---
**Limechain, June, 2020 - February, 2022 <br>Blockchain Developer**

Part of several projects mostly focused in **Polkadot** ecosystem. Responsible for end-to-end delivery of features, from gathering requirements, to designing solutions to implementing and testing them.

Some of the highlights of my time at Limechain:

***Lending Protocol***

- Implementing, writing and testing smart contracts in [**Ink!**](https://paritytech.github.io/ink/) smart contract language
- Responsible for implementing Math library
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

**Personal projects**

This section lists some of my personal and freelance projects.

***Fiat on-off ramp***

A **Web3 Foundation** grant that aims to connect banking interfaces with **Polkadot** ecosystem. I am responsible for building **Substrate** offchain-worker pallet, writing tests, as well as maintaining the project. For more information about it, refer to the original grant proposal [here](https://github.com/w3f/Grants-Program/blob/master/applications/FIAT-on-off-ramp.md).

*This project is Work In Progress*

***Qaul.net***

[qaul.net](https://github.com/qaul/qaul.net) is an Internet independent wireless mesh communication app. With qaul.net, you can communicate directly from one device to another. I am a part-time Rust and P2p Engineer here and try to help with the development from time to time. My work mostly revolves around [`rust-libp2p`](https://github.com/libp2p/rust-libp2p) library.


***Decentralized Auctioned NFT Marketplace***

For my senior thesis in Computer Science, I worked on a proof-of-concept project on the topic of *managed decentralization*. The project was aimed to explore how enterprises and companies could benefit from blockchain without compromises on privacy and thoroughput.

In the project, the goal was to build a decentralized network of nodes that host a backend for an **NFT Marketplace**. Backend simply serves and matches orders. Marketplace and orders function with the use of **Order Commitments**. 

Consensus of the network is a simple **Auction** protocol smart contract. It is also called a **Proof-of-Donation**. Essentially, whichever node bids the most amount of value to the time slot, will be the winner and **main processor/backend**(validator) at that slot. Nodes are incentivized by commissions from gossiping and matching orders. **Main backend** in a given slot, gets to match all the orders in that slot.

I successfully delivered and demonstrated my proof-of-concept project and received and exceptional grade. Final version of the project is raw and it is still work in progress. Some of the key issues need to be addressed before any production grade usage.

The network and backend was built in **Rust**, consensus and marketplace in **Solidity** and frontend in **React**. Many design and architecture patterns are inspired by **Substrate** and **FileCoin**.

**Upwork and Freelance, January, 2020 - Present, <br>Blockchain and Full Stack developer**

Started my programming career as a freelancer and later picked up **Upwork**. Mostly specialize on projects in the blockchain space and provide full cycle development services as well as consultations.

Some of the projects I was part of:

***Crypto Portfolio Tracker***

Portfolio tracker and exchange platform. Worked on integrating exchange APIs and blockchains.

***Bulk sender contract in Solana and Cosmos***

Port existing **Solidity** contract into **Solana** program and **CosmWASM** smart contract.

*This project is Work In Progress*

***Substrate chain indexer***

Built personal indexer script for **Substrate** chains. As part of the task, also contributed to open-source library: [**@open-web3js**](https://github.com/open-web3-stack/open-web3.js)

***Crypto and Fiat price indexer***

Tool for indexing daily prices of cryptocurrencies and fiat. Open source.

***NFT Marketplace and Gallery***

Built a simple NFT marketplace and gallery.

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

- Confident: **NodeJs**, **Rust**, **Solidity**, **Substrate**, **Ink!**, **Python**, **React**, **AssemblyScript**, **git**  
- Some experience: **C++**, **Solana**, **CosmosSDK**, **AWS**  
- Interested: **ML**, **AI**

# Open source contributions
---

- [Efinity](https://github.com/efinity)
- [qaul.net](https://github.com/qaul/qaul.net)
- [open-web3-js](https://github.com/open-web3-stack/open-web3.js)
- [Zombienet](https://github.com/paritytech/zombienet)
- [Subsembly](https://github.com/LimeChain/subsembly)
- [AssemblyScript SCALE Codec](https://github.com/LimeChain/as-scale-codec)
- [OCW Ebics](https://github.com/element36-io/ocw-ebics)
