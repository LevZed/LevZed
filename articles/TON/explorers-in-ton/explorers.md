# Explorers in TON

In this article, we will consider TON explorers, their capabilities and features from the point of view of the developer.

## What is an explorer?

If you are new to the blockchain technology, here is some basic information:

Explorer is a website that allows you to view information in the blockchain, such as account balance, transaction history, blocks, etc.

## What explorers exist?

Among the TON explorers, you can distinguish several categories:

- For everyday use
- With extended information for developers
- Specialized

The division into categories is largely conditional, and one explorer can belong to several categories at the same time. So let's not pay too much attention to this.

## General functionality

Let's start with the general functionality that is present in all explorers.

Almost all explorers have the ability to find information about the balance, transaction history, and information about the smart contract, if any, deployed on this address by the address in the TON network.

Next, we will consider several explorers that can be attributed to each of the categories.

## TonScan Explorer

Good explorer for everyday use.

### Features

- **Convenient for everyday use**
- Convenient for developers
- TON DNS support
- Сontract types
- Contract disassembler

| base address info                  | transaction                       |
| ---------------------------------- | --------------------------------- |
| ![tonscan](./eit-tonscan-info.png) | ![tonscan](./eit-tonscan-txn.png) |

- URL: https://tonscan.org/
- Testnet URL: https://testnet.tonscan.org/

## TonWhales Explorer

This explorer is more oriented towards developers than ordinary users.

Also, the TonWhales team supports its own network `sandbox`. This is both a plus and a minus. The plus is that you can test your smart contracts in this network, the minus is that all information about transactions in this network is not displayed in other explorers.

### Features

- **Convenient for developers**
- Support for its own network `sandbox`
- Сontract types
- **Ability to view code of verified smart contracts**
- Contract disassembler

| base address info                      | transaction                           |
| -------------------------------------- | ------------------------------------- |
| ![tonwhales](./eit-tonwhales-info.png) | ![tonwhales](./eit-tonwhales-txn.png) |

- URL: https://tonwhales.com/explorer
- Testnet URL: https://tonsandbox.com/explorer

## TonAPI Explorer

This explorer is the newest of the presented and has its own pleasant features.
For example, Trace. This feature allows you to see the entire sequence of transactions between smart contracts, even if subsequent transactions do not contain your address.

Transaction information is not as detailed as, for example, tonwhales.

### Features

- Convenient for developers
- Convenient for everyday use
- Jetton transaction history
- **Trace**
- TON DNS support

| base address info                | transaction                     |
| -------------------------------- | ------------------------------- |
| ![tonapi](./eit-tonapi-info.png) | ![tonapi](./eit-tonapi-txn.png) |

## TON NFT EXPLORER

This explorer is specialized in NFT, but it can also be used as a regular explorer.

When viewing the wallet address, you can find out which NFT it stores, and when viewing the NFT, you can find out the metadata, collection address, owner, and transaction history.

### Features

- Convenient for developers
- Сontract types
- **Specialized in NFT**

| nft address info                         | nft data                                    |
| ---------------------------------------- | ------------------------------------------- |
| ![tonnft](./eit-tonnftexplorer-info.png) | ![tonnft](./eit-tonnftexplorer-nftdata.png) |

## Want to be in this list?

Please, write to one of the [maintainers](/contribute/maintainers).

## References

Right now you could find most of the explorers in the Ton.App directory:

- [https://ton.app/explorers](https://ton.app/explorers)

<!-- Explorers list:
- Tonscan
- Tonwhales
- TonAPI
- Nft tools
- Ton.cx
- Ton.sh -->
