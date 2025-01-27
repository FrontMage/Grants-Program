# W3F Grant Proposal

- **Project Name:** Decentralized Edge-Computing Platform(DEP)
- **Team Name:** Deeper Network
- **Payment Address:** 0x24cfc36f699dacc5cb652630ddd894a8df658233 (BNB Smart Chain BEP20 USDT)
- **[Level](https://github.com/w3f/Grants-Program/tree/master#level_slider-levels):** 2

## Project Overview :page_facing_up:

### Overview

We sincerely request a funding grant from the web3 Foundation to build a decentralized edge computing framework that will provide a basic environment for off-chain decentralized application development. Today, on-chain web3 applications have shown a blossoming ecology, but off-chain web3 applications lack a common environment. For example, chainlink keepers is a decentralized component dedicated to the oracle machine domain, filecoin's fvm is a decentralized component dedicated to the storage domain, and kp3r is a guardian network focused on the Defi domain. However, they more or less lack some key components of decentralization off-chain, such as commitment to security, commitment to privacy, commitment to availability, and commitment to actual available nodes.

Deeper Network will leverage its technical strengths to provide security, privacy and scalability to the on-chain decentralized base execution environment, thus opening up the possibility for many potential web3 applications to emerge.


### Project Details

We expect the teams to already have a solid idea about your project's expected final state. Therefore, we ask the teams to submit (where relevant):

- Mockups/designs of any UI components
- Data models / API specifications of the core functionality
- An overview of the technology stack to be used
- Documentation of core components, protocols, architecture, etc. to be deployed
- PoC/MVP or other relevant prior work or research on the topic
- What your project is _not_ or will _not_ provide or implement
  - This is a place for you to manage expectations and to clarify any limitations that might not be obvious

Things that shouldn’t be part of the application (see also our [FAQ](../docs/faq.md)):
- The (future) tokenomics of your project 
- For non-infrastructure projects—deployment and hosting costs, maintenance or audits
- Business-oriented activities (marketing, business planning), events or outreach

### Ecosystem Fit

Help us locate your project in the Polkadot/Substrate/Kusama landscape and what problems it tries to solve by answering each of these questions:

- Where and how does your project fit into the ecosystem?
- Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?
- What need(s) does your project meet?
- Are there any other projects similar to yours in the Substrate / Polkadot / Kusama ecosystem?
  - If so, how is your project different?
  - If not, are there similar projects in related ecosystems?

## Team :busts_in_silhouette:

### Team members

-   Hui Liu
-   Jerry Yu
-   Biguo Xin
-   Bin Guo
-   Fei Xie

### Contact

-   **Contact Name:** Bin Guo
-   **Contact Email:** bin.guo@deeper.network

-   **Website:** [https://deeper.network/](https://deeper.network/)

### Legal Structure

-   **Registered Address:** 5200 Great America pkwy, Santa Clara CA USA 95054
-   **Registered Legal Entity:** Deeper Network Inc

### Team's experience

**Hui Liu**  
Hui worked at Intel, Fortinet, and Palo Alto Networks, where he held positions such as R&D Manager and Chief Engineer. He brings more than ten years of experience in network security and operating system development. He spearheaded the development of the cloud firewall engine which still brings billions of dollars in annual revenue for the company.

**Jerry Yu**  
Worked at HuaWei,JingDong and Crypape Technology where held position of architect
Over 10 years of working experience in various aspects of computer programming, including DB,Network,Blockchain etc.
Deeper Network, Nervos technical community participant.
System level engineer(worked in Go/Rust/C++)
Github : https://github.com/jerry-yu
Email : huoqiutianyu@gmail.com

**Biguo Xin**  
Chief data scientist of WHU Big Data Instituion
Over 5 years working on Rust
Author of various GO/Rust libraries
GitHub https://github.com/FrontMage
Email xbgxwh@outlook.com

**Bin Guo**  
Yang worked at Bytedance, Alibaba, Windriver, and has working experience in cloud infrastructure, operating system and embedded system.

**Fei Xie**  
8 years as a full stack web developer in game, E-commerce and online documentation, 2 years of experience in web3 and blockchain.
Core member of casbin (a high performance authorization framework), google summer of code 2020 community mentor: https://summerofcode.withgoogle.com/archive/2020/organizations/6587176113930240
Contributor of [substrate](https://github.com/paritytech/substrate/commits?author=xcaptain), [frontier](https://github.com/paritytech/frontier/commits?author=xcaptain), [substrate-archive](https://github.com/paritytech/substrate-archive/commits?author=xcaptain), [polkadot api](https://github.com/polkadot-js/api/commits?author=xcaptain) and some other popular web3 opensource projects.
Github: https://github.com/xcaptain
Email: joey.xf@gmail.com

### Team Code Repos

- [deeper-chain](https://github.com/e2chain-dev/deeper-chain)
- [deeper-web3d](https://github.com/FrontMage/web3d)

## Development Status :open_book:

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:

- links to improvement proposals or [RFPs](https://github.com/w3f/Grants-Program/tree/master/rfp-proposal) (requests for proposal),
- academic publications relevant to the problem,
- links to your research diary, blog posts, articles, forum discussions or open GitHub issues,
- references to conversations you might have had related to this project with anyone from the Web3 Foundation,
- previous interface iterations, such as mock-ups and wireframes.

### Demo deck
The introduction of DEP can be seen below: 
https://docs.qq.com/slide/DUkJFbXV1blBZaW1C?u=c8722c9f9bb5490883f378c4606097bc

### Demo applications
Everyone can try a simple demo at [Demo](https://github.com/dantenetwork/cross-chain-demo/tree/develop)

### Demo driver layer
[deeper-web3d](https://github.com/FrontMage/web3d)  

## Development Roadmap :nut_and_bolt:

This section should break the development roadmap down into milestones and deliverables. To assist you in defining it, we have created a document with examples for some grant categories [here](../docs/grant_guidelines_per_category.md). Since these will be part of the agreement, it helps to describe _the functionality we should expect in as much detail as possible_, plus how we can verify and test that functionality. Whenever milestones are delivered, we refer to this document to ensure that everything has been delivered as expected.

Below we provide an **example roadmap**. In the descriptions, it should be clear how your project is related to Substrate, Kusama or Polkadot. We _recommend_ that teams structure their roadmap as 1 milestone ≈ 1 month.

For each milestone,

- make sure to include a specification of your software. _Treat it as a contract_; the level of detail must be enough to later verify that the software meets the specification.
- include the amount of funding requested _per milestone_.
- include documentation (tutorials, API specifications, architecture diagrams, whatever is appropriate) in each milestone. This ensures that the code can be widely used by the community.
- provide a test suite, comprising unit and integration tests, along with a guide on how to set up and run them.
- commit to providing Dockerfiles for the delivery of your project.
- indicate milestone duration as well as number of full-time employees working on each milestone.
- **Deliverables 0a-0d are mandatory for all milestones**, and deliverable 0e at least for the last one. If you do not intend to deliver one of these, please state a reason in its specification (e.g. Milestone X is research oriented and as such there is no code to test).

> :zap: If any of your deliverables is based on somebody else's work, make sure you work and publish _under the terms of the license_ of the respective project and that you **highlight this fact in your milestone documentation** and in the source code if applicable! **Teams that submit others' work without attributing it will be immediately terminated.**

### Overview

- **Total Estimated Duration:** Duration of the whole project (e.g. 2 months)
- **Full-Time Equivalent (FTE):**  Average number of full-time employees working on the project throughout its duration (see [Wikipedia](https://en.wikipedia.org/wiki/Full-time_equivalent), e.g. 2 FTE)
- **Total Costs:** Requested amount in USD for the whole project (e.g. 12,000 USD). Note that the acceptance criteria and additional benefits vary depending on the [level](../README.md#level_slider-levels) of funding requested. This and the costs for each milestone need to be provided in USD; if the grant is paid out in Bitcoin, the amount will be calculated according to the exchange rate at the time of payment.

### Milestone 1 — Implement DEP node

- **Estimated duration:** 1 month
- **FTE:**  2
- **Costs:** 8,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | An **inline documentation** will be provided to the miners to show the functions and what should they provide for the DEP node. Then there will be a **tutorial** for miners to show them how to spin up a DEP worker node. |
| 0c. | Test Nodes | A total of 10 DEP nodes will be deployed for testing purpose. All of these nodes are running by the developer team for debugging convience. |
| 0d. | Testing Guide | All functions in the DEP node will be tested and provided with a rust library for test automation. |


### Milestone 2 — Implement DEP contract

- **Estimated duration:** 1 month
- **FTE:**  2
- **Costs:** 8,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | An **inline documentation** will be provided to the developer users about the APIs of the DEP contract. |
| 0c. | Test Network | A testnet will be deployed and maintained by the developer team. |
| 0d. | Testing Guide | All functions in the DEP contract will be tested and provided with a rust library for test automation. |
| 0e. | Testing Application Program | Since the test of DEP requires a certain amount of network token, we will be starting a tester application program for testers to join and get free tokens on the testnet. |
| 0f. | Article | We will publish an **article**/workshop that explains how DEP is built, these articles are targeting the power users of DEP. Furthermore, we will publishing articles for the users of DEP who are only interested in what can the network do for them and what are the advantages comparing to the traditional WEB2 solutions.

### Milestone 3 — The oracle price

- **Estimated duration:** 1 month
- **FTE:**  1
- **Costs:** 8,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | A totorial will be provide to show how to get oracle price by using the DEP network. |
| 0c. | Testing Guide | All functions in the oracle price DAPP will be tested and provided with a rust library for test automation. |
| 0d. | Article | We will publish an **article**/workshop about why the oracle price is better when running on the DEP network, and the various applications such as EZC can be built on top of it.

### Milestone 4 — The Easy Cent(EZC) Trading Medium Criterion

- **Estimated duration:** 1 month
- **FTE:**  1
- **Costs:** 8,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / GPLv3 / MIT / Unlicense |
| 0b. | Documentation | A totorial will be provide to show how to get burn DPR into EZC. |
| 0c. | EZC contract | A contract based on the oracle price will be made to provide basic functions of EZC. |
| 0d. | Article | We will publish an **article**/workshop about why a non transferable token is useful to the network and how it performs as the blood of the network.

## Future Plans
- DAPP developement guidelines and the denylist

While we want the network to be free and open to anyone, we are also taking the `bad guys` into consideration. There should be a community voted denylist to prevent the abuse of DEP, we have hope and confidence for the most of mankind are good and willing to maintain a positive DEP network. Also a guideline will be published for developers, ones that should be aware of both the good and bad things that the network is capable of.

- DAPP store

By building the DEP network, we are empowered to provide a easy to use, robust and dencentralized application framework, which we will build a WEB3 ecosystem on.

By providing a DAPP store, developers of DEP can easily build and publish their DAPPs and the users of DEP can use our network pay for the DAPPs that there are intersted in, and the miners can easily choose what DAPPs they want to provide as a runner.


## Additional Information :heavy_plus_sign:

**How did you hear about the Grants Program?** Web3 Foundation Website / Medium / Twitter / Element / Announcement by another team / personal recommendation / etc.

Here you can also add any additional information that you think is relevant to this application but isn't part of it already, such as:

- Work you have already done.
- If there are any other teams who have already contributed (financially) to the project.
- Previous grants you may have applied for.
