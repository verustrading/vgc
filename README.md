# Verus Game Cartridge (VGC)
This Whitepaper Summary consolidates Seed Logic, VDXF Architecture, and Economic Model into a single roadmap for the Verus Game Cartridge Protocol.

[Discord discussion](https://discord.com/channels/1180350488256987177/1454957304696012860)

# Example Lemonade Stand/Stall
The example in the whitepaper has a focus on the lemonade stand (lemonade stall) game. It was an early ([original 1973](https://en.wikipedia.org/wiki/Lemonade_Stand)) pioneer of the economic game genre.

## Same data, different UI
This blockchain use case, as highlighted in the `ROGUE` link below, can use the same blockchain data across different user interfaces - text, web, phone, console, VR etc.

In 2009, even EA [ported a version to the iphone](https://www.cnet.com/tech/mobile/ea-turns-lemons-into-lemonade-tycoon-for-iphone/). Cool Math Games [has an online lemonade stand game](https://www.coolmathgames.com/0-lemonade-stand).

BitPay even had an [example lemonade stand](https://github.com/bitpay/lemonade-stand)

# Inspiration

It’s in a similar spirit to [jl777](https://github.com/jl777)’s [ROGUE](https://komodoplatform.com/en/blog/tt2019-7-rogue-blockchain-gaming-tournaments-tokenization-collectibles-trading/) featuring [proof-of-gameplay](https://medium.com/@jameslee777/cc-design-proof-of-gameplay-6a63b86da5e5) with extra thoughts in [part 2](https://medium.com/@jameslee777/cc-design-proof-of-gameplay-attack-vector-and-mitigation-aa8580364c) and related expansion for [multiplayer](https://medium.com/@jameslee777/cc-design-proof-of-gameplay-multiplayer-rng-for-realtime-synchronized-events-a074efbd00d3), but for a lemonade stand game as an example.

# Expansion
Can be reused for any single player gameplay, where the “character” has an auditable saved history.

Mint ID then the game logic runs deterministically.

Anyone is free to build it, and it’s open for discussion.

# Motivation
Initially I tried to design it as a decentralized multiplayer co-op, but it got too complicated for my goals, so I reverted back to the single player game design because it was easier & more cost effective to play/maintain. Maintenance is free of on-chain costs in the single player architecture.

