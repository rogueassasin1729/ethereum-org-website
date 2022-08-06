---
title: Ethereum Development Standards
description:
lang: en
sidebar: true
incomplete: true
---

## Standards overview {#standards-overview}

The Ethereum community has adopted many standards that help keep projects (such as [Ethereum clients](/developers/docs/nodes-and-clients/) and wallets) interoperable across implementations, and ensure smart contracts and dapps remain composable.

Typically standards are introduced as [Ethereum Improvement Proposals](/eips/) (EIPs), which are discussed by community members through a [standard process](https://eips.ethereum.org/EIPS/eip-1).

- [Introduction to EIPs](/eips/)
- [List of EIPs](https://eips.ethereum.org/)
- [EIP GitHub repo](https://github.com/ethereum/EIPs)
- [EIP discussion board](https://ethereum-magicians.org/c/eips)
- [Introduction to Ethereum Governance](/governance/)
- [Ethereum Governance Overview](https://web.archive.org/web/20201107234050/https://blog.bmannconsulting.com/ethereum-governance/) _March 31, 2019 - Boris Mann_
- [Ethereum Protocol Development Governance and Network Upgrade Coordination](https://hudsonjameson.com/2020-03-23-ethereum-protocol-development-governance-and-network-upgrade-coordination/) _March 23, 2020 - Hudson Jameson_
- [Playlist of all Ethereum Core Dev Meetings](https://www.youtube.com/playlist?list=PLaM7G4Llrb7zfMXCZVEXEABT8OSnd4-7w) _(YouTube Playlist)_

## Types of standards {#types-of-standards}

There are 3 types of EIPs:

- [Standard Track](https://eips.ethereum.org/)
- [Meta Track](https://eips.ethereum.org/meta)
- [Informational Track](https://eips.ethereum.org/informational)

Further, the Standard Track is sub-divided into 4 categories:

- [Core](https://eips.ethereum.org/core)
- [Networking](https://eips.ethereum.org/networking)
- [Interface](https://eips.ethereum.org/interface)
- [ERC](https://eips.ethereum.org/erc)

The main difference in the above categories of Standards Track EIP is where it's deployed. For example, ERCs are deployed at the application level. They don't need to be adopted by all participants, unlike Core Track EIP which is deployed at the protocol level and requires a broader consensus in the community as all core EIPs must be widely adopted (all nodes must upgrade to remain part of the network)


### Token standards {#token-standards}

- [ERC-20](/developers/docs/standards/tokens/erc-20/) - A standard interface for fungible (interchangeable) tokens, like voting tokens, staking tokens or virtual currencies.
- [ERC-721](/developers/docs/standards/tokens/erc-721/) - A standard interface for non-fungible tokens, like a deed for artwork or a song.
- [ERC-777](/developers/docs/standards/tokens/erc-777/) - A token standard improving over ERC-20.
- [ERC-1155](/developers/docs/standards/tokens/erc-1155/) - A token standard which can contain both fungible and non-fungible assets.
- [ERC-4626](/developers/docs/standards/tokens/erc-4626/) - A tokenized vault standard designed to optimize and unify the technical parameters of yield-bearing vaults.

Learn more about [token standards](/developers/docs/standards/tokens/).

## Further reading {#further-reading}

- [Ethereum Improvement Proposals (EIPs)](/eips/)

_Know of a community resource that helped you? Edit this page and add it!_
