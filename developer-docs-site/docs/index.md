---
title: "Aptos 开发文档"
slug: "/"
hidden: false
sidebar_position: 0
hide_table_of_contents: true
---

欢迎你来到 Aptos 实验室，我们正在为每个人建立一个第一层公链。本文档将帮助您为 Aptos 区块链开发应用程序，运行节点，并成为蓬勃发展的 Aptos 社区的一部分。该文档涵盖了基本和高级主题。在这里，你可以找到概念、操作指南、快速入门、教程、API 参考、代码示例、发布说明等。

## 设置 Aptos 环境和开始新手教程

<div class="docs-card-container">
<div class="row row-cols-1 row-cols-md-3a g-4">
  
  <div class="col">
    <div class="card card-body h-100 d-flex flex-column" >
    <a href="guides/getting-started" class="card-title card-link stretched-link"> <h2>开始</h2></a>
    <p class="card-text">设置你的本地开发环境.</p>
</div>
  </div>
  <div class="col">
    <div class="card card-body h-100 d-flex flex-column">
    <a href="tutorials/aptos-quickstarts/" class="card-title card-link stretched-link"> <h2>新手快速指南</h2></a>
    <p class="card-text">提交你的第一笔交易，编写你的第一个 Move 模块，部署你的第一个代币，以及更多。</p>
</div>
</div>
</div>
</div>

## Learn Aptos concepts and follow the guides

<div class="docs-card-container">
<div class="row row-cols-1 row-cols-md-2a g-4">
  <div class="col">
    <div class="card card-body h-100 d-flex flex-column">
    <a href="concepts/aptos-concepts" class="card-title card-link stretched-link"> <h2>概念</h2></a>
    <p class="card-text">了解Aptos区块链的关键概念，包括交易、账户、汽油费和交易费用、节点等等。 </p>
</div>
</div>
  <div class="col">
    <div class="card card-body h-100 d-flex flex-column" >
    <a href="guides/aptos-guides" class="card-title card-link stretched-link"> <h2>如何工作</h2></a>
    <p class="card-text">与Aptos区块链的互动是如何进行的，Move在Aptos上是如何工作的，如何创建一个签名交易，等等。</p>
</div>
  </div>
  <div class="col">
    <div class="card card-body h-100 d-flex flex-column">
    <a href="guides/move-guides/move-on-aptos" class="card-title card-link stretched-link"> <h2>用Move 在 Aptos上</h2></a>
    <p class="card-text">了解Move在Aptos区块链上是如何工作的。</p>
</div>
</div>
</div>
</div>

## Run Aptos nodes

<div class="docs-card-container">
<div class="row row-cols-1 row-cols-md-2a g-4">
  <div class="col">
    <div class="card card-body h-100 d-flex flex-column" >
    <a href="/nodes/validator-node/validators" class="card-title card-link stretched-link"> <h2>运行一个验证节点</h2></a>
    <p class="card-text">安装和运行一个验证节点或全节点</p>
</div>
</div>
  <div class="col">
    <div class="card card-body h-100 d-flex flex-column"  >
    <a href="/nodes/local-testnet/local-testnet-index" class="card-title card-link stretched-link"> <h2>运行一个本地测试环境</h2></a>
    <p class="card-text">运行一个验证节点或本地测试环境.</p>
</div>
  </div>
  <div class="col">
    <div class="card card-body h-100 d-flex flex-column"  >
    <a href="nodes/full-node/public-fullnode" class="card-title card-link stretched-link"> <h2>运行一个公共的全节点</h2></a>
    <p class="card-text">运行一个全节点并连接到测试网.</p>
</div>
  </div>
  
</div>
</div>

## Develop apps with SDKs and APIs

<div class="docs-card-container">
<div class="row row-cols-1 row-cols-md-2a g-4">
<div class="col">
    <div class="card h-100" >
    <div class="card-body d-flex flex-column" >
    <a href="/cli-tools/aptos-cli-tool/aptos-cli-index" class="card-title card-link stretched-link"> <h2>CLI</h2></a>
    <p class="card-text">用于在Aptos区块链上开发和部署的CLI。</p>
</div>
</div>
</div>
  <div class="col">
    <div class="card h-100" >
    <div class="card-body d-flex flex-column" >
    <a href="/sdks/index" class="card-title card-link stretched-link"> <h2>SDKs</h2></a>
    <p class="card-text">用于在Aptos区块链上构建的SDK。</p>
</div>
</div>
</div>
  <div class="col">
  <div class="card h-100" >
    <div class="card-body d-flex flex-column"  >
    <a href="https://fullnode.devnet.aptoslabs.com/v1/spec#/" class="card-title card-link stretched-link"> <h2>REST API</h2></a>
    <p class="card-text">与Aptos区块链交互的REST API参考。</p>
</div>
</div>
</div>
</div>
</div>

## Connect to Aptos networks

Aptos 提供了运行本地测试网，以及使用共享的 devnet 和 testnet，mainnet 也在路上。请参阅 [System Integrators Guide](guides/system-integrators-guide.md#networks) 以了解可用的网络和连接它们的方法。

:::tip Aptos Devnet Resets
Aptos 开发网每周四都会重置。在 Aptos[Discord][discord]查看最新的更新。
:::info

## 提出问题并提供答案

加入[Discord][discord]，与开发者对话，并跳入 Aptos 社区。这是在 Aptos 宇宙中保持最新的新闻和发展的最佳方式。一定要检查频道中的钉子信息--这是我们喜欢保留特定主题的链接，事件，和更多。

甚至如果你只是想停下来说 "早上好！"也可以。每个人都有自己的东西。

:::注意事项 在外安全

独自去是很危险的。请记住，社区经理永远不会先给你发信息或 DM，他们也不会要求你给他们送钱或分享任何敏感、隐私或个人信息。如果这种情况发生在你身上，请在[Discord][discord]向我们报告，或者发送电子邮件到[security@aptoslabs.com](mailto:security@aptoslabs.com)。

:::

## Join us

想加入一个伟大的团队，致力于解决惊人的世界性问题吗？看看[活跃角色](https://boards.greenhouse.io/aptoslabs)，并和我们一起建设吧!

或者只需[创建一个拉动请求](https://github.com/aptos-labs/aptos-core/pulls)来进行更新，[提交问题](https://github.com/aptos-labs/aptos-core/issues)来报告问题。

## 玩得开心

我们很高兴你在这里，我们期待着了解你。欢迎来到 Aptos 社区! 了解更多关于我们的信息:

- [AptosLabs.com](https://www.aptoslabs.com/)
- [Forum](https://forum.aptoslabs.com/)
- [Discord](https://discord.gg/aptoslabs)
- [Medium](https://medium.com/aptoslabs)
- [Telegram](https://t.me/aptos_official)
- [Twitter](https://twitter.com/AptosLabs)
