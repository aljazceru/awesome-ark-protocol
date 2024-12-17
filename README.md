Ark is a layer-two protocol for making off-chain Bitcoin transactions. Initially published on the bitcoin-dev mailing list as TBDXXX by Burak, is has since been named Ark and the protocol design has advanced significantly.

The goal and result of the Ark protocol is a payments system where people can make Bitcoin transactions at very low cost and without requiring any setup. The Ark model very closely resembles the UTXO model, which is a key differentiator with Lightning.

Ark is a scaling solution for Bitcoin that involves moving transactions off-chain. Ark executes transactions outside of the Bitcoin main chain but posts transaction data back on-chain in a compressed format. Ark servers bundle multiple off-chain transactions into large batches before submitting them to the Bitcoin blockchain. This method spreads fixed costs across multiple transactions in each batch, significantly reducing fees for end-users.


## Protocol
- [Ark protocol](https://ark-protocol.org/)
- [Introducting Ark v2](https://brqgoo.medium.com/introducing-ark-v2-2e7ab378e87b) - updated Ark protocol proposal 
- [Ark Protocol intro](https://docs.second.tech/protocol/intro/) - Intro to Ark protocol by Second
- [Ark deep dive](https://web.archive.org/web/20240328181345/https://www.arkpill.me/deep-dive) - Original Ark deep dive by Burak


## Implementations
- [ark](https://github.com/ark-network/ark)
- [bark](https://codeberg.org/ark-bitcoin/bark) - A Rust implementation of the Ark protocol on bitcoin

#### Deprecated implementations
- [clArk](https://github.com/ark-network/clArk)![stars](https://img.shields.io/github/stars/ark-network/clArk.svg?style=social)

## Reading
- [Covenant-less Ark](https://arkdev.info/blog/ark-release-v0.2)
- [Unlocking Liquidity Before Shared Output Expiration](https://arkdev.info/blog/unlock-liquidity-before-shared-output-expiration)
- [First Ark transaction on mainnet](https://blog.second.tech/demoing-the-first-ark-transactions-on-bitcoin-mainnet/)

### Ark v1 reading
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

  
## Blogs
- [arkdev.info blog](https://arkdev.info/blog)
- [Second's blog](https://blog.second.tech/)

## Presentations and podcasts
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

## Communites
- [Telegram community](https://t.me/ark_bitcoin)
- [Ark Labs discord](https://discord.com/invite/5XwckYtXAG)
