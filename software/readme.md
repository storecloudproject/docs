---
title: Storecoin Software
---
# Software

Pre-built software and services you can run on your own infrastructure, provided by Storecoin.org.

## [Storecoin Core](../Storecoin-core/learn/admin.html)
Storecoin Core is the backbone of the Storecoin network and does the hard work of validating and agreeing on the status of every transaction with other instances of Core through the Storecoin Consensus Protocol (SCP).

## [Horizon](https://github.com/Storecoin/go/tree/master/services/horizon)
Horizon is the client-facing API server for the Storecoin ecosystem. It acts as the interface between Storecoin Core and applications that want to access the Storecoin network. If you are running Storecoin Core, you will probably also want to run Horizon.

## [Federation Server](https://github.com/Storecoin/go/tree/master/services/federation)
A standalone Federation protocol server designed to be dropped in to your existing infrastructure. It can be configured to pull the data it needs out of your existing SQL database.

| Platform       | Latest Release                                                                         |
|----------------|------------------------------------------------------------------------------------------|
| Mac OSX 64-bit (amd64) | [federation-darwin-amd64](https://github.com/Storecoin/go/releases/download/federation-v0.2.0/federation-v0.2.0-darwin-amd64.tar.gz)      |
| Linux 64-bit (amd64)  | [federation-linux-amd64](https://github.com/Storecoin/go/releases/download/federation-v0.2.0/federation-v0.2.0-linux-amd64.tar.gz)       |
| Linux 32-bit (arm)  | [federation-arm-amd64](https://github.com/Storecoin/go/releases/download/federation-v0.2.0/federation-v0.2.0-linux-arm.tar.gz)       |
| Windows 64-bit (amd64) | [federation-windows-amd64.exe](https://github.com/Storecoin/go/releases/download/federation-v0.2.0/federation-v0.2.0-windows-amd64.zip) |

## [Bridge Server](https://github.com/Storecoin/bridge-server)
Storecoin’s Bridge server provides a simple interface for the Storecoin network. It is meant to simplify compliance operations and other more complicated integrations. Because it stores and manages keys and account information, access to it should be well protected. Unlike Horizon, it should never be exposed to the public internet.

## [Archivist](https://github.com/Storecoin/go/tree/master/tools/Storecoin-archivist)
This is a small tool, written in Go, for working with Storecoin-core history archives directly. It is a standalone tool that does not require Storecoin-core, or any other programs.


| Platform       | Latest Release                                                                        |
|----------------|------------------------------------------------------------------------------------------|
| Mac OSX 64-bit (amd64) | [Storecoin-archivist-darwin-amd64](https://github.com/Storecoin/go/releases/download/Storecoin-archivist-v0.1.0/Storecoin-archivist-v0.1.0-darwin-amd64.tar.gz)      |
| Linux 64-bit (amd64)   | [Storecoin-archivist-linux-amd64](https://github.com/Storecoin/go/releases/download/Storecoin-archivist-v0.1.0/Storecoin-archivist-v0.1.0-linux-amd64.tar.gz)       |
| Linux 32-bit (arm)   | [Storecoin-archivist-linux-arm](https://github.com/Storecoin/go/releases/download/Storecoin-archivist-v0.1.0/Storecoin-archivist-v0.1.0-linux-arm.tar.gz)       |
| Windows 64-bit (amd64) | [Storecoin-archivist-windows-amd64.exe](https://github.com/Storecoin/go/releases/download/Storecoin-archivist-v0.1.0/Storecoin-archivist-v0.1.0-windows-amd64.zip) |
