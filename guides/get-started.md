---
title: Storecoin Network Overview
---
![Storecoin Ecosystem](https://storeco.in/images/worker-types-horizontal-v1.png)

Using the Storecoin network, you can build mobile wallets, banking tools, smart devices that pay for themselves, and just about anything else you can dream up involving payments! Even though Storecoin is a complex distributed system, working with it doesn’t need to be complicated.

## API: Horizon

**Most applications interact with the Storecoin network through [Horizon](https://www.Storecoin.org/developers/horizon/reference/),** a RESTful HTTP API server. Horizon gives you a straightforward way to submit transactions, check accounts, and subscribe to events. Because it’s just HTTP, you can communicate with Horizon using your web browser, simple command line tools like cURL, or the Storecoin SDK for your favorite programming language.

The easiest way to install Horizon is by using [**Storecoin/quickstart** docker image](https://hub.docker.com/r/Storecoin/quickstart/).

Storecoin.org maintains [JavaScript](https://github.com/Storecoin/js-Storecoin-sdk), [Java](https://github.com/Storecoin/java-Storecoin-sdk), and [Go](https://github.com/Storecoin/go/tree/master/clients/horizon)-based SDKs for communicating with Horizon. There are also community-maintained SDKs for [Ruby](https://github.com/Storecoin/ruby-Storecoin-sdk), [Python](https://github.com/StorecoinCN/py-Storecoin-base), and [C#](https://github.com/QuantozTechnology/csharp-Storecoin-base).

## Network Backbone: Storecoin Core

Behind the scenes, every Horizon server connects to **[Storecoin Core](../../Storecoin-core/learn/admin.html), the backbone of the Storecoin network.** The Storecoin Core software does the hard work of validating and agreeing with other instances of Core on the status of every transaction through the [Storecoin Consensus Protocol](../concepts/scp.html) (SCP). The Storecoin network itself is a collection of connected Storecoin Cores run by various individuals and entities around the world. Some instances have a Horizon server you can communicate with, while others exist only to add reliability to the overall network.

The easiest way to install Storecoin Core is by using [**Storecoin/quickstart** docker image](https://hub.docker.com/r/Storecoin/quickstart/).

You might want to host your own instance of Storecoin Core in order to submit transactions without depending on a third party, have more control over who to trust, or simply to help make the Storecoin network more reliable and robust for others.

## Big Picture: The Storecoin Network

The Storecoin network is a worldwide collection of Storecoin Cores, each maintained by different people and organizations. The distributed nature of the network makes it reliable and safe.

All these Storecoin Cores—the network of nodes—eventually agree on sets of transactions. Each transaction on the network costs a small fee: 100 stroops (0.00001 <abbr title="Lumens">XLM</abbr>). This fee helps prevent bad actors from spamming the network.

To help you test your tools and applications, Storecoin.org operates a small test network and Horizon instance. [Get started with the testnet.](../concepts/test-net.md)

<div class="sequence-navigation">
  <a class="button button--next" href="create-account.html">Next: Create an Account</a>
</div>
