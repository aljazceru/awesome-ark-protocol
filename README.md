Ark is a layer-two protocol for making off-chain Bitcoin transactions. Initially published on the bitcoin-dev mailing list as TBDXXX by Burak, is has since been named Ark and the protocol design has advanced significantly.

The Ark protocol is a payments system where people can make Bitcoin transactions at very low cost and without requiring any setup. The Ark model very closely resembles the UTXO model, which is a key differentiator with Lightning.

Ark is a scaling solution for Bitcoin that involves moving transactions off-chain. Ark executes transactions outside of the Bitcoin main chain but posts transaction data back on-chain in a compressed format. Ark servers bundle multiple off-chain transactions into large batches before submitting them to the Bitcoin blockchain. This method spreads fixed costs across multiple transactions in each batch, significantly reducing fees for end-users.

### Protocol
- [Ark protocol](https://ark-protocol.org/) - Introduction to Ark maintained by [Steven Roose](https://github.com/stevenroose)
- [Introducting Ark v2](https://brqgoo.medium.com/introducing-ark-v2-2e7ab378e87b) - Updated Ark protocol proposal 
- [Ark protocol intro](https://docs.second.tech/protocol/intro/) - Intro to the Ark protocol by [Second](https://second.tech)
- [Ark protocol intro](https://docs.arklabs.xyz/ark/) - Intro to the Ark protocol by [Ark Labs](https://arklabs.xyz)
- [Ark deep dive](https://web.archive.org/web/20240328181345/https://www.arkpill.me/deep-dive) - Original Ark deep dive by Burak

### Implementations
- [Arkade](https://docs.arkadeos.com/)) - An Operating System For Programmable Money by [Ark Labs](https://arklabs.xyz)
- [bark](https://gitlabs.com/ark-bitcoin/bark) - A Rust implementation of the Ark protocol by [Second](https://second.tech)

### Developer resources

#### Documentation
- [Getting started with Arkade](https://docs.arkadeos.com) - Ark Labs' how-to for developers
- [Getting started with bark](https://docs.second.tech/getting-started/introduction/) - Second's how-to for developers

#### SDKs & Libraries
- [ark-ts](https://github.com/arkade-os/ts-sdk) - Arkade TypeScript SDK by Ark Labs
- [ark-go](https://github.com/arkade-os/go-sdk) - Arkade GO by Ark Labs
- [ark-rs](https://github.com/arkade-os/rust-sdk)) - Arkade Rust SDK by Ark Labs
- [bark-wallet](https://docs.rs/bark-wallet/latest/bark/) - bark Rust API reference by Second
- [boltz-swap](https://github.com/arkade-os/boltz-swap) - lightning swaps with boltz for Arkade

#### Faucets
- [Arkade munitynet faucet](https://mutinynet.arkade.money/) - Faucet for mutinynet
- [bark signet faucet](https://signet.2nd.dev) - Faucet for signet


#### Projects using Ark
- [arkd](https://github.com/arkade-os/arkd) -  Ark Server implementation that powers Arkade 
- [arkade.money](https://arkade.money/) - Web wallt by Ark Labs
- [arkash](https://github.com/supertestnet/arkash) - Supertestnet's ecash like implementation of Ark
- [Byte store](https://signet.2nd.dev/store) - Mock online store for testing Ark payments on signet
- [coinflip](https://coinflip.casino/) - Coinflip game implemented with Ark
- [fulmine](https://github.com/ArkLabsHQ/fulmine) - Bitcoin wallet daemon that enables swap providers and payment hubs to optimize Lightning Network channel liquidity while minimizing on-chain fees 
- [Noah wallet](https://alpha.noahwallet.io) - Mobile-native bitcoin wallet built on Ark
- [NArk](https://github.com/ArkLabsHQ/NArk) - Ark payment functionality with BTCPayServer
- [snap](https://github.com/arkade-os/snap) - Metamask Snap that brings Bitcoin, Lightning and Arkade to your browser

### Reading

#### Ark v2 reading
- [Arkade - technical Primer](https://docs.arkadeos.com/primer) 
- [Covenant-less Ark](https://github.com/arkade-os/arkd/releases/tag/v0.2.0)
- [Unlocking Liquidity Before Shared Output Expiration](https://blog.arklabs.xyz/unlock-liquidity-before-shared-output-expiration/)
- [First Ark transaction on mainnet](https://blog.second.tech/demoing-the-first-ark-transactions-on-bitcoin-mainnet/)
- [Introducing Erk and hArk - new Ark variants](https://blog.second.tech/erk-update/)

#### Ark v1 reading
- [ARK video from Bitcoin Miami 2023](https://bitcointv.com/w/pVk3bPfKZ7YqDzsNZjz9tf?start=4h9m28s)
- [ARK presentation from Bitcoin Miami 2023](https://docs.google.com/presentation/d/1xKIJt4CnUCFfxhIwDj_kW0Ecr0NcvN5bZ4SQexGJfmk/edit?usp=sharing)
- [[bitcoin-dev] Ark: An Alternative Privacy-preserving Second Layer Solution](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-May/021694.html)
- [Introducing Ark Blog Post](https://burakkeceli.medium.com/introducing-ark-6f87ae45e272)
- [Rijndael's write up on how Ark works](https://primal.net/thread/note1cuv7mg7z0w7jvwp9mlsu0zt6acnw54avaj5r5zgdkxlpjnqp3g0s5c0yht)
- [RubenSomsen's Simplest Ark Explanation](https://gist.github.com/RubenSomsen/a394beb1dea9e47e981216768e007454)
- [Ark Whiteboard Masterclass with Burak & Robin](https://youtu.be/EocWax43QgQ)
- [Bitcoin magazine: Introducing Ark](https://bitcoinmagazine.com/technical/how-ark-plans-to-scale-private-bitcoin-payments)
- [BitGo blog: Will Burak’s Ark Solve Bitcoin Scaling?](https://blog.bitgo.com/will-buraks-ark-solve-bitcoin-scaling-f31e65535c3f)
- [pippellia's Video Ark Explained - Bitcoin Layer 2 Protocol](https://rumble.com/v3nf9vd-ark-explained-bitcoin-layer-2-protocol.html)

### Blogs
- [Ark Labs' blog](https://blog.arklabs.xyz)
- [Second's blog](https://blog.second.tech/)

### Presentations and podcasts
- [Steven Roose on Ark](https://bitcointv.com/w/iSg88hQLVGKicujZQvvYc6) - BitDev conference at Taipei Tech Summit
- [Banking on Ark](https://www.youtube.com/watch?v=ag-z-29ptbI) - Banking on Ark talk by Marco Argentieri with [slides](https://docs.google.com/presentation/d/1HdWag6gMU4nFgB_s9RLmYLfBVERyZFjy3_xzd3hSmbk/edit#slide=id.g26fdbd1c56e_0_50)
- [SLP482 Burak – Ark: A new L2 protocol for Bitcoin](https://stephanlivera.com/episode/482/) - Burak on Stephan Livera Podcast
- [Ark announcement at Bitcoin 2023](https://www.youtube.com/watch?v=TRLFYb45q9U) - Burak's Ark announcement at Bitcoin 2023
- [Bitcoin Takeover Podcast S14 E1: Burak Keceli on Ark & Bitcoin 2nd Layers](https://www.youtube.com/watch?v=iQ7TLBhh9r4) 
- [The Kevin Rooke Show E109: Burak on Building Ark, Scaling Bitcoin, and Improving Privacy](https://www.stacksats.how/podcasts/e109-burak-on-building-ark-scaling-bitcoin-and-improving-privacy)
- [The ark-hashed podcast, episode 16](https://youtu.be/p3TzBci2CyI)
- [Updates on Ark development - one year later](https://stephanlivera.com/episode/584/)
- [Scaling Bitcoin to 2050 w/ Shinobi, Marco Argentieri, Simanta Gautam & Alex Bosworth](https://www.youtube.com/watch?v=IPmjIg7IaR8)
- [Transforming Bitcoin: Marco Agentieri’s Vision with Ark Labs](https://www.youtube.com/watch?v=GrvsENa9Zm4)
- [Ark explained in under 14 minutes](https://youtu.be/WvwmLv0SgAc?si=Nc0yo79MD-BJPhAZ)

### Communites
- [Telegram community](https://t.me/ark_bitcoin) - Ark protocol Telegram community
- [Ark Labs Discord](https://discord.com/invite/5XwckYtXAG) - Ark Labs' Discord community
- [Second community](https://community.second.tech) - Second's community forum
- [Second's bark chat](https://chat.second.tech) - Second's technical support chat, hosted on Zulip

### Related Resources
To explore other aspects of the Bitcoin and freedom tech ecosystem, check out these additional resource directories:
- [nostr.net](https://www.nostr.net) - A complete guide to Nostr - projects, implementations, developer tools and all other resources
- [liquidnetwork.wiki](https://liquidnetwork.wiki) - A curated list of Liquid Network resources, libraries, tools and applications
- [pubky.tech](https://pubky.tech) - Pubky, an open protocol for censorship resistant web applications
- [dlc.wiki](https://www.dlc.wiki) - Everything you need to know about Discreet Log Contracts
- [ungovernable.tech](https://ungovernable.tech) - A collection of resources on encryption, privacy tools, and decentralized technologies
- [lightning-network.tech](https://www.lightning-network.tech/)  - Essential tools, guides, and communities for Bitcoin Lightning Network node operators.
- [ark-protocol.com](https://ark-protocol.com) - A directory of Ark protocol resources, libraries, tools and applications

### Contributing

If you'd like to add something to this list, please submit a [Pull Request on GitHub](https://github.com/aljazceru/awesome-ark-protocol/).

This directory is maintained by [aljaz](https://disobey.dev/contact/). Your contributions help keep this information up-to-date and valuable.
