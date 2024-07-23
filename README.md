# Awesome Stacks(🚧正在翻译整合中...🚧)[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![awesome-stacks-zh-cn](./README.assets/awesome-stacks-zh-cn.png)

* 本文翻译自https://github.com/friedger/awesome-stacks-chain



[Stacks](https://www.stacks.co/what-is-stacks) is a blockchain anchored by Bitcoin that enables apps, smart contracts, and digital assets. Stacks is a layer-1 blockchain that connects to Bitcoin and implements smart contracts and decentralized applications through the [Clarity language](https://clarity-lang.org/). Through the [Proof of Transfer (PoX) consensus mechanism](https://docs.stacks.co/stacks-101/proof-of-transfer), the state of the Stacks blockchain is anchored against the Bitcoin blockchain, thus providing the security and finality of Bitcoin to Stacks. Stacks brings the programmability of other blockchain technologies to Bitcoin, without the need to modify the core consensus mechanism of Bitcoin itself.

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
<!--lint ignore awesome-list-item-->

- [Apps](#apps)
  - [Wallets](#wallets)
  - [Stacks Web Applications](#stacks-web-applications)
  - [Blockchain Name System](#blockchain-name-system)
  - [DeFi](#defi)
  - [Games](#games)
  - [Stacking Apps](#stacking-apps)
- [Clarity Resources](#clarity-resources)
  - [Developer Tools](#developer-tools)
  - [Example Contracts](#example-contracts)
  - [Libraries](#libraries)
  - [Contracts](#contracts)
  - [Non-Fungible Tokens](#non-fungible-tokens)
  - [Fungible Tokens](#fungible-tokens)
  - [Stacking](#stacking)
- [App Development](#app-development)
  - [Client Libraries](#client-libraries)
  - [CLI](#cli)
  - [Storage](#storage)
  - [Indexing and Querying APIs](#indexing-and-querying-apis)
- [Learning Resources](#learning-resources)
  - [Documentation](#documentation)
  - [Videos](#videos)
  - [Written Tutorials](#written-tutorials)
  - [Books](#books)
  - [Courses](#courses)
- [Community](#community)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## 应用程序

### 钱包

- [Asigna](https://asigna.io/) - 支持多签的钱包，适用于比特币、Ordinals、BRC20 和 Stacks。
- [Leather Wallet](https://leather.io/install-extension) - 开源钱包，仅支持比特币和 Stacks 生态。[桌面端版本](https://leather.io/install-desktop)。
- [Xverse Wallet](https://www.xverse.app/) - 移动钱包应用及浏览器插件，用于管理比特币、STX 和质押（部分开源）。

### Stacks Web 应用

- [Hiro Explorer](https://explorer.hiro.so/?chain=mainnet) - 区块链浏览器。
- [STX Scan](https://stxscan.co/) - 区块链浏览器。
- [Send Many](https://sendstx.com) - 一键向多个接收者发送 STX 和其他代币。
- [Sigle](https://www.sigle.io/) - 去中心化写作平台。
- [Console](https://www.console.xyz/) - 去中心化社交应用。
- [Blocksurvey](https://blocksurvey.io/) - 以数据所有权和隐私为重点的 AI 驱动的问卷调查平台。
- [MultiSafe](https://github.com/Trust-Machines/multisafe) - 金库，用于管理 Stacks (STX) 和比特币 (BTC)。

### BNS域名

- [BNSx](https://www.dots.so/) - 用一个账户管理多个 BNS 域名(1:n)。

- [btc.us](https://btc.us) - 用于注册 .btc 域名的应用程序。

- [BNS search](https://www.bnssearch.com/) - 用于搜索注册的 BNS 域名的应用程序。

- [BNS and Ordinals](https://www.bns.xyz/) - 将 BNS 域名通过 Ordinal 存储。

- [Owl.link](https://owl.link) - 用于为 BNS 名称创建链接页面的应用程序。

  

### 去中心化金融 (DeFi)

- [Alex Lab](https://app.alexlab.co) - 一个 DeFi 服务平台。
- [Arkadiko Protocol](https://github.com/arkadiko-dao/arkadiko) - 基于自我偿还贷款的稳定币 (USDA)。
- [Bitflow](https://www.bitflow.finance/) - 去中心化交易所。
- [Velar](https://www.velar.co/) - 在比特币 L2 上进行代币交换、交易和发起资产的平台。
- [Zest Protocol](https://www.zestprotocol.com/) - 在比特币和 Stacks 上的去中心化借贷协议。
- [STX20](https://github.com/fess-v/stx20-standard) - 用于在 Stacks 上创建和共享数字艺术品的协议。
- [STXTools](https://stxtools.io/) - 用于在 Stacks 上的 DeFi 图表、交易和价格警报工具。
- [Stacks Pulse](https://github.com/pradel/stackspulse) - 实时监控 Stacks 链上的 DeFi 状态。
- [Signal21](https://signal21.io/) - 比特币 L1、L2 和 Dapps 的链上分析工具。
- [Lydian](https://app.lydian.xyz) - 去中心化的财政管理协议（已停运）。
- [CityCoins](https://minecitycoins.com) - 城市代币（正在逐步关闭）。

### 游戏

- [Stacks Degens](https://stacksdegens.com) - 一个通过 NFT 实现的像素风赛车游戏。
- [Project Indigo](https://www.projectindigonft.com) - 一个交互式的RPG游戏。

## 

### 开发者工具

- [Clarinet](https://github.com/hirosystems/clarinet) - Clarity 的命令行工具，方便开发和测试 Clarity 智能合约。
- [Clariform](https://github.com/njordhov/clariform) - Clarity 的代码格式化和语法检查工具。
- [Clarigen](https://github.com/obylabs/clarigen) - 用于编写与 Clarity 智能合约交互的 TypeScript 代码的工具。
- [clarity.tools](https://clarity.tools) - 运行在浏览器中的 Clarity 交互执行环境。
- [ClarityGPT Prompt](https://claritygpt.com/) - 使用GPT编写智能合约的Prompt。
- [Hiro Platform](https://platform.hiro.so/) - 浏览器中的集成开发环境 (IDE)。

### 示例合约

- [Source of Clarity](https://source-of-clarity.com) - 已部署的主网 Clarity 合约列表，并附有一些注释。
- [示例合约](https://github.com/hirosystems/clarity-examples) - 一组示例智能合约，可以作为学习clarity合约的起点。
- [经过审计的示例智能合约](https://github.com/clarity-lang/book/tree/main/projects) - 另一组示例智能合约，已进行安全审计。

### 库

- [uint256](https://github.com/KStasi/clarity-uint256-lib) - 一个将值转换为 256 位的库。
- [clarity-bitcoin](https://github.com/friedger/clarity-bitcoin) - 验证比特币交易的库。

### 合约

- [CityCoin](https://github.com/citycoins/citycoin) - 使用 STX 转账按照比例概率铸造新币的 PoX Lite 实现。
- [SWAPR](https://github.com/psq/swapr) - 在 Stacks 2.0 和 Clarity 上实现的功能类似于 Uniswap 的合约。
- [FLEXR](https://github.com/psq/flexr) -  [Ampleforth](https://www.ampleforth.org/) 的 Clarity版本。
- [ClarityDAO](https://github.com/friedger/clarity-dao) - Moloch DAO 的 Clarity 版本。
- [NFT Marketplace](https://github.com/friedger/clarity-marketplace/blob/master/contracts/market.clar) - 用于交易资产的市场合约。
- [StackStarter](https://github.com/MarvinJanssen/stackstarter/blob/master/contracts/stackstarter.clar) - 用于众筹的 Clarity 智能合约。
- [Lightning Swaps](https://github.com/radicleart/clarity-rstack/blob/master/contracts/lightning-swaps-v1.clar) - 使用闪电网络实现防欺诈交换证明。
- [Election Voting](https://github.com/elbaruni/clarity-election/blob/master/contracts/election.clar) - 使用 Clarity 进行候选人投票的基本合约。
- [DualX](https://github.com/westridgeblockchain/dualX) - 一组实现去中心化交易生态系统的 Clarity 合约。
- [ExecutorDAO](https://github.com/MarvinJanssen/executor-dao) - 一个用于在智能合约中构建 DAO 功能的 Clarity 框架。
- [Digital Will](https://github.com/LoRdSoban/Cryptonomers) - 有条件的资金转移合约。

### 非同质化代币 (NFT)

- [This is #1](https://www.thisisnumberone.com) - 在比特币和 Stacks 区块链上构建的第一个专业 NFT ([合约](https://explorer.hiro.so/txid/SP3QSAJQ4EA8WXEDSRRKMZZ29NH91VZ6C5X88FGZQ.thisisnumberone-v2?chain=mainnet))。
- [Smart Contract GPT](https://github.com/Markeljan/smart-contract-gpt) - 一个用于创建 SIP-009 合约的聊天机器人。

### 同质化代币

- [Nothing](https://nothingtoken.xyz/) - 一个无实际作用的同质化代币 ([合约](https://explorer.hiro.so/txid/SP32AEEF6WW5Y0NMJ1S8SBSZDAY8R5J32NBZFPKKZ.nope?chain=mainnet))。

### 质押

- [Stacking Pools](https://github.com/friedger/clarity-stacking-pools) - 用于质押池的 PoX 包装合约。
- [Stacks Pools](https://github.com/degen-lab/stacks-pools) - 去中心化质押池。

## 应用开发

### 客户端库

- [Stacks.js](https://github.com/hirosystems/stacks.js) - 用于与 Stacks 区块链交互的 JavaScript 库的单一代码库。
- [stacks.rs](https://github.com/52/stacks.rs) - 用于与 Stacks 区块链交互的 Rust 工具包。
- [stacks.py](https://github.com/rohitverma007/stackspy) - 用于与 Stacks 区块链交互的 Python 库。

### 命令行工具 (CLI)

- [@stacks/cli](https://github.com/hirosystems/stacks.js/tree/master/packages/cli) - 用于交互授权、存储和交易的命令行接口。



### RPC服务

- [Stacks API](https://www.hiro.so/stacks-api) - 托管 API，用于直接与区块链交互以查询信息、广播交易。
- [Quicknode](https://www.quicknode.com/chains/stx) - 托管节点，使用 Quicknode 快速轻松地连接到 Stacks。
- [Self-Hosted Render](https://github.com/stacksfoundation/render-stacks) - 在 Render 上自动部署 Stacks 节点的一键式工具。
- [Self-Hosted Digital Ocean](https://marketplace.digitalocean.com/apps/stacks-blockchain) - 用于运行 Stacks 节点的 Digital Ocean 虚拟机。
- [Self-Hosted Docker](https://github.com/stacks-network/stacks-blockchain-docker) - 使用 Docker 自行托管 Stacks 节点的工具。

## 学习资源

### 文档

- [官方 Stacks 文档](https://docs.stacks.co/) - 学习 Clarity 和开发 Stacks 应用程序的文档和开发者教程。
- [Hiro 文档](https://docs.hiro.so/) - 面向开发者的文档。
- [Stacks 101](https://stacks101.com) - 由社区贡献的知识库。

### 视频资源

- [Clarity 101](https://youtu.be/lXJutQqDq3w) - 学习 Clarity 设计原则相关的基础知识.
- [Developer Registry 101](https://www.crowdcast.io/e/clarity-program) - 学习如何从头开始构建一个 Clarity 智能合约。
- [How Clarity Prevents Common Smart Contract Vulnerabilities](https://www.youtube.com/watch?v=VYXhrwPsBws) - 详细介绍Clarity的安全原则。
- [Proof of Transfer Whitepaper Reading with Muneeb Ali](https://www.youtube.com/watch?v=NY_eUrIcWOY&t=3s) - PoX白皮书的作者讲述PoX的概述。
- [Web3 for Bitcoin](https://www.crowdcast.io/e/web3-for-bitcoin/) - 概述 Stacks 如何将智能合约功能引入比特币。
- [Why Build on Stacks](https://www.youtube.com/watch?v=WaTMCremGwE) - 简述为什么Web3的开发者会选择stacks。

### 教程

- [Built on Bitcoin: An Introduction to Full-Stack Web3 Development with Stacks](https://dev.to/stacks/built-on-bitcoin-an-introduction-to-full-stack-web3-development-with-stacks-me9) - A high-level overview of building full-stack applications with Stacks.
- [Understanding Stacks Post Conditions](https://dev.to/stacks/understanding-stacks-post-conditions-e65) - A guide to understanding and working with Post Conditions in Stacks.
- [Test-Driven Stacks Development with Clarinet](https://dev.to/stacks/test-driven-stacks-development-with-clarinet-2e4i) - A tutorial showing how to utilize Clarinet for testing and TDD.
- [Build a DEX with Stacks](https://www.pointer.gg/tutorials/build-a-dex-with-stacks/56abb3a4-05c1-4608-b096-f82189e9f759) - An extensive introduction to working with Stacks by building a full-stack decentralized exchange.
- [Build a Stacks app with Remix](https://micro-stacks.dev/guides/with-remix) - How to create a server-side rendered Stacks app using the Remix JS framework and Micro-Stacks.
- [Build a Stacks app with Next.js](https://micro-stacks.dev/guides/with-nextjs) - Similar to the Remix tutorial above, this one utilizing Next.js and Micro-Stacks.
- [Creating a Voting Contract](https://www.clearness.dev/01-voting-clarity-smart-contract/01-getting-started) - 演示如何用 Clarity 创建一个基本的投票智能合约。
- [Building an NFT with Stacks and Clarity](https://blog.developerdao.com/building-an-nft-with-stacks-and-clarity) - Utilize the SIP-009 standard to create an NFT using Clarity.
- [Order Book Contract Walkthrough](https://byzantion.hiro.so/) - Walkthrough of an order book smart contract built with Clarity.
- [NFT Tutorial](https://docs.hiro.so/tutorials/clarity-nft) - Create an NFT with Clarity.

### Books

- [Clarity of Mind](https://book.clarity-lang.org/) - Writing productive smart contracts that are predictable. [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

### Courses

- [Clarity Universe](https://clarity-lang.org/universe) - A comprehensive Clarity development course, offered as both a self-paced course or as a 6-week guided cohort.

## Community

- [Discord](https://discord.gg/zrvWsQC) - Stacks ecosystem Discord.
- [Twitter](https://twitter.com/stacks) - Stacks ecosystem Twitter.
- [YouTube](https://www.youtube.com/c/Blockstack) - Stacks ecosystem YouTube.
- [Official Stacks Forum](https://forum.stacks.org/) - Stacks community forum.
- [r/stacks](https://www.reddit.com/r/stacks) - Stacks subreddit.

## Contributing

We welcome community contributions to this list. Please read the [contribution guidelines](contributing.md) before contributing.
