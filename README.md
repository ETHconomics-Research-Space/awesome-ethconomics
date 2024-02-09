# Awesome ETHconomics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome resources related to crypto-economics insights on protocol mechanism design, fee model, token utility within Ethereum ecosystem.

<div align="center">
  <a href="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Supply-and-demand.svg/1920px-Supply-and-demand.svg.png">
    <img alt="Ethereum Economy" width="70%" src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Supply-and-demand.svg/1920px-Supply-and-demand.svg.png" >
  </a>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="https://github.com/ETHconomics-Research-Space/awesome-ethereum-economy/graphs/contributors">
      <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/ETHconomics-Research-Space/awesome-ethereum-economy">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
    <a href="https://twitter.com/ETHconomicspace">
      <img alt="Twitter" src="https://img.shields.io/twitter/url/https/twitter.com/ETHconomicspace.svg?style=social&label=Follow%20%40ETHconomicspace">
    </a>
  </p>
</div>

## Table of Contents
- [Awesome ETHconomics](#awesome-ethconomics-)
  - [Table of Contents](#table-of-contents)
  - [General introduction](#general-introduction)
    - [Mechanism Design](#mechanism-design)
    - [Intro to crypto-economics](#intro-to-crypto-economics)
    - [Resource pricing](#resource-pricing)
    - [Censorship Resistance](#censorship-resistance)
  - [Ethereum economics](#ethereum-economics)
    - [Intro to Ethereum economics](#intro-to-ethereum-economics)
    - [Ethereum fee model](#ethereum-fee-model)
    - [Staking economics](#staking-economics)
    - [Proposer and builder separation, PBS](#proposer-and-builder-separation-pbs)
    - [MEV](#mev)
  - [Layer2 scaling solutions and economics](#layer2-scaling-solutions-and-economics)
    - [General](#general)
    - [Rollup economics](#rollup-economics)
    - [EIP-4844 fee market](#eip-4844-fee-market)
  - [DeFi](#defi)
  - [Governance in crypto-economics](#governance-in-crypto-economics)
  - [Tokenomics](#tokenomics)
  - [Case studies](#case-studies)
  - [Research groups, forums and communities](#research-groups-forums-and-communities)
  - [Courses and educational resources](#courses-and-educational-resources)
  - [Podcasts and videos](#podcasts-and-videos)
  - [Tools and platforms](#tools-and-platforms)
- [Contributing](#contributing)

## General introduction

### Mechanism Design

[Barnabé Monnot - Tutorial on Blockchain Mechanism Design Part I](https://mediaweb.ap.panopto.com/Panopto/Pages/Viewer.aspx?id=5d3a1953-b139-45c6-9f9b-afeb003b46c5)

[Davide Crapis - Tutorial on Blockchain Mechanism Design Part II](https://mediaweb.ap.panopto.com/Panopto/Pages/Viewer.aspx?id=1d24699f-5f56-4cb1-95ea-afeb003b1951)

### Intro to crypto-economics

[ELI5: Cryptoeconomics by Julian Ma | Devcon Bogotá](https://www.youtube.com/watch?v=gMiykGwPDSI), [slides](https://docs.google.com/presentation/d/1ADPiTVWEVQ8nBGLMRdx5GmSFdrrKi3OzsbyedOcVLWk/edit#slide=id.g141d1b1a5ae_0_0)

### Resource pricing

[Optimal Dynamic Fees for Blockchain Resources](https://arxiv.org/abs/2309.12735), [talks](https://streameth.org/watch?event=ethconomics&session=65b8f8cda5b2d09b88ec1011)

[Structuring Blockspace Derivatives](https://mirror.xyz/0x03c29504CEcCa30B93FF5774183a1358D41fbeB1/WKa3GFC03uY34d2MufTyD0c595xVRUEZi9RNG-dHNKs)

[Wait, It's All Resource Pricing?](https://www.youtube.com/watch?v=YoWMLoeQGeI)

### Censorship Resistance

[Censorship Resistance in On-Chain Auctions](https://arxiv.org/abs/2301.13321)

## Ethereum economics

### Intro to Ethereum economics

[The road to Ethereum](https://barnabe.substack.com/p/eth2)

[Guide to Ethereum Economics](https://medium.com/@dcrapis/guide-to-ethereum-economics-introduction-abe89a873d09)

[Ethereum economics model](https://github.com/CADLabs/ethereum-economic-model), [tutorial](https://www.cadcad.education/course/masterclass-ethereum)

### Ethereum fee model

[On Block Sizes, Gas Limits and Scalability](https://ethresear.ch/t/on-block-sizes-gas-limits-and-scalability/18444)

[On Increasing the Block Gas Limit](https://ethresear.ch/t/on-increasing-the-block-gas-limit/18567)

[Ethereum gas limit analysis](https://github.com/nerolation/eth-gas-limit-analysis), code of the analysis

[Approximating User Welfare and Surplus with Transaction Data](https://ethresear.ch/t/approximating-user-welfare-and-surplus-with-transaction-data/14766)

[Multidimensional EIP 1559](https://ethresear.ch/t/multidimensional-eip-1559/11651), [中文](https://www.ethereum.cn/Eth1.x/multidimensional-eip-1559)

[Dynamical Analysis of the EIP-1559 Ethereum Fee Market](https://arxiv.org/pdf/2102.10567.pdf)

[Transaction Fees on a Honeymoon: Ethereum’s EIP-1559 One Month Later](https://arxiv.org/pdf/2110.04753.pdf)

[Optimality Despite Chaos in Fee Markets](https://arxiv.org/abs/2212.07175)

### Staking economics

[ROP-0: Timing games in Proof-of-Stake](https://www.notion.so/385f0f6279374a90b52bf380ed76a85b?pvs=21)

[Time in Ethereum](https://www.youtube.com/watch?v=Zfqvke8BNhM), [slides](https://docs.google.com/presentation/d/1hQ1sWfAvsmJpbnNe6tfyvKfd13YyTW1GPGDk6z0KoQw/edit#slide=id.p)

[Timing games in Proof-of-Stake](https://ethresear.ch/t/timing-games-in-proof-of-stake/13980)

[Time is Money: Strategic Timing Games in Proof-of-Stake Protocols](https://arxiv.org/abs/2305.09032); [talk 1](https://www.youtube.com/watch?v=f8YLZqqpFpU) and [slides](https://docs.google.com/presentation/d/1TjzS5oYI_vfcGRSWpHmQ3_P6eq_oQ1WdDve_rNWlFsg/edit#slide=id.g2401d3821ec_1_0); [talk 2](https://www.youtube.com/watch?v=jTZq58SB1l8&t=48s) and [slides](https://docs.google.com/presentation/d/18vlAs5uRspZNEORXNjwqKOCR6rtMuonD_WeC2A5fB8g/edit#slide=id.p)

[Properties of issuance level (part 1)](https://notes.ethereum.org/@anderselowsson/HyUIqjo_6)

[Three Attacks on Proof-of-Stake Ethereum](https://arxiv.org/abs/2110.10086)

### Proposer and builder separation, PBS

[(Re-)drawing Ethereum economics for the brave new builder world](https://www.youtube.com/watch?v=mKyyNvQeopM)

[State of research: increasing censorship resistance of transactions under proposer/builder separation (PBS)](https://notes.ethereum.org/@vbuterin/pbs_censorship_resistance#Solution-1-can-we-run-many-pre-confirmation-private-PBS-auctions-in-parallel)

[Fun and games with inclusion lists](https://ethresear.ch/t/fun-and-games-with-inclusion-lists/16557)

[Unbundling PBS: Towards protocol-enforced proposer commitments (PEPC)](https://ethresear.ch/t/unbundling-pbs-towards-protocol-enforced-proposer-commitments-pepc/13879)

[PEPC FAQ](https://www.notion.so/0787ba2f77e14efba771ff2d903d67e4?pvs=21)

[When To Sell Your Blocks](https://collective.flashbots.net/t/when-to-sell-your-blocks/2814)

### MEV

[Decoding MEV: Past, Present, Future](https://www.youtube.com/watch?v=F9IuBZGseFQ)

[MEV Auction: Auctioning transaction ordering rights as a solution to Miner Extractable Value](https://ethresear.ch/t/mev-auction-auctioning-transaction-ordering-rights-as-a-solution-to-miner-extractable-value/6788)

MEV Podcast Series by Bell Curve, [ep1](https://www.youtube.com/watch?v=_8DkRO60fvw), [ep2](https://www.youtube.com/watch?v=fWRboyGk_lc), [ep3](https://www.youtube.com/watch?v=17n6oHoo7pw), [ep4](https://www.youtube.com/watch?v=b3o2YP6sxpg), [ep5](https://www.youtube.com/watch?v=NqM9PNPQFMs), [ep6](https://www.youtube.com/watch?v=IknurQzmVhY), [ep7](https://www.youtube.com/watch?v=4t7qbv4Wzn4&t=9s), [ep8](https://www.youtube.com/watch?v=pMhc3MHip5k), [bounus](https://www.youtube.com/watch?v=RjSG38e1Zl0)

[Strategic Bidding Wars in On-chain Auctions](https://arxiv.org/abs/2312.14510)

[Are We Heading Towards the MEV Dystopia?](https://wenbuilding.simplecast.com/episodes/ep9-the-mev-dystopia-IyLpnoAQ) 

## Layer2 scaling solutions and economics

### General

[Latency in blockchains and Ethereum L2 migration](https://www.notion.so/f4ea156908bb48688615bddcc6b14ed3?pvs=21)

### Rollup economics

[ROP-3: Rollup economics framework](https://www.notion.so/561d6340ad174195a335af6cc4e66bb7?pvs=21)

[Understanding rollup economics from first principles](https://barnabe.substack.com/p/understanding-rollup-economics-from), [中文](https://www.ethereum.cn/Layer2/understanding-rollup-economics), [talks](https://www.youtube.com/watch?v=BmQnb7TN3Ho)

[Rollups are Real — Rollup Economics 2.0](https://www.notion.so/2516079f62a745b598133a101ba5a3de?pvs=21)

[Fair and sustainable fees for L2 (ETHconomics @ Devconnect 2022)](https://www.youtube.com/watch?v=JfaxBythV4Q&list=PLTLjFJ0OQOj5PHRvA2snoOKt2udVsyXEm)

[Ethereum Rollup Call Data Pricing Analysis](https://forum.celestia.org/t/ethereum-rollup-call-data-pricing-analysis/141)

### EIP-4844 fee market

[EIP-4844 Fee Market Analysis](https://ethresear.ch/t/eip-4844-fee-market-analysis/15078),  [code of Simulation and Backtest](https://github.com/dcrapis/blockchain-dynamic-pricing/blob/685b837dda64d149bd330e5619cf9682f4e58dc8/eip-4844-sim.ipynb)

[EIP-4844 Economics and Rollup Strategies](https://arxiv.org/abs/2310.01155)

[Data Availability Post 4844](https://scroll.io/blog/data-availability-4844)

[Comprehensive coverage of EIP-4844](https://www.eip4844.com/)

## DeFi

## Governance in crypto-economics

## Tokenomics

[Designing Token Economies](https://www.notboring.co/p/designing-token-economies)

[Tokengated Commerce](https://www.notboring.co/p/tokengated-commerce)

[Simple Tokenomics for a Proof-of-Stake Utility Token](https://starkware.co/resource/simple-tokenomics-for-a-proof-of-stake-utility-token/)

## Case studies

## Research groups, forums and communities

[Robust Incentives Group (RIG) under Ethereum Foundation](https://www.notion.so/802339956f2745a5964d8461c5ccef02?pvs=21)

[RIG Open Problems (ROPs)](https://www.notion.so/c11382c213f949a4b89927ef4e962adf?pvs=21)

[ETHconomics @ Devconnect 2022](https://www.youtube.com/playlist?list=PLTLjFJ0OQOj5PHRvA2snoOKt2udVsyXEm)

[ETHconomics 2 @ Devconnect in Istanbul 2023](https://www.notion.so/f3ff71566e8140bfa832c2462288a14c?pvs=21)

[Flashbots forum](https://collective.flashbots.net/categories)

[Columbia CryptoEconomics Workshop 2023](https://www.youtube.com/playlist?list=PLpktWkixc1gX-L5NT-vuDP54kW--3gDnK)

[IC3, The Initiative for CryptoCurrencies and Contracts](https://www.initc3.org/)

[Economics of Ethereum organized by American Economic Association 2024](https://www.aeaweb.org/conference/2024/program/1850?q=eNqrVipOLS7OzM8LqSxIVbKqhnGVrJQMlWp1lBKLi_OTQRxzJR2lktSiXFwgG8hKSayEMEoyc1MhrLLM1HKQAUUFBUABUwOl2lpcMGLJG8A)

[ETHconomics Research Space](https://www.notion.so/ETHconomics-Research-Space-Hub-880ec73dc0d343639bf0a5a7e1d2ab41?pvs=21)

[Frontier Research](https://frontier.tech/)

## Courses and educational resources

[cadCAD Masterclass: Ethereum Validator Economics](https://www.cadcad.education/course/masterclass-ethereum)

## Podcasts and videos

[Finematics](https://www.youtube.com/@Finematics/videos)

[Bell Curve](https://www.youtube.com/@bellcurvepodcast/videos)

## Tools and platforms

[Crypto Fees](https://cryptofees.info/)

[L2 Fees](https://l2fees.info/)

[SimpleStakers.info](https://simplestakers.info/)

[Ultra sound money](https://ultrasound.money/)

[Crypto data nerd](https://0xkofi.com/)
# Contributing

Contributions are very welcome!

Please have a look at [contributing.md](https://github.com/ETHconomics-Research-Space/awesome-ethereum-economy/blob/main/contributing.md) for guidelines.
