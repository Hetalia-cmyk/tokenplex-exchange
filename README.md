# tokenplex-exchange
Tokenplex: Bridging Ethereum and Solana for Seamless Cross-Chain Liquidity

**Introduction**

Tokenplex is a pioneering Solana-based application designed to expand cross-chain liquidity by bridging the gap between the Ethereum and Solana ecosystems. By leveraging the capabilities of Wormhole, Tokenplex facilitates the seamless migration of popular Ethereum tokens onto the Solana platform, where users can enjoy faster transactions, reduced fees, and increased scalability.

Tokenplex includes an inbuilt exchange- which is a novel, Oracle based exchange with built-in LP rewards(LP rewards will be 2.5 of trade value), specifically designed for easy buying of bridged tokens without slippage. This repo consists of the exchange programs, which can be tested using `anchor test`

The deployed program ID on devenet is: 84eo5XmbNUVgW32SxwA3Hzc8mH94HdyWg2m5bDPGT863

You can test it directly on devnet using:
```
yarn
anchor test --skip-build --skip deploy
```

**Key Features:**

🌉 Ethereum to Solana Bridge: Tokenplex uses Wormhole to ensure a smooth and secure transfer of tokens from Ethereum to Solana.

💱 Swap with Confidence: Rely on our robust price feed oracle to get the most accurate and up-to-date prices for your swaps.

💡 LP Rewards: Hardcoded 2% rewards for all LPs to incentivise bridged wormhole liquidity on solana.

💰 Reduced Transaction Fees: Say goodbye to exorbitant gas fees on Ethereum and enjoy the low-cost benefits of the Solana network.

**How It Works**
Bridge Your Tokens: Use our intuitive interface to transfer your favorite Ethereum tokens to the Solana network via Wormhole. If you supply liquidity to tokenplex, you will get LP rewards when others swap.

Access Tokenplex Pools: Once your tokens are on Solana, you can add them to Tokenplex's liquidity pools or swap them for other tokens.

Swap Based on Oracle Price Feeds: Ensure you get the best rates for your swaps, backed by our reliable price feed oracle from Switchboard.
Withdraw or Continue Trading: After your swap, you can either withdraw your tokens or continue trading on our platform.

Security: Our platform prioritizes the safety of your assets. With Wormhole's secure bridging mechanism and our robust infrastructure, your tokens are in safe hands.
Community-driven: Tokenplex believes in the power of the community. Our platform is built with the community in mind, ensuring it caters to the needs of its users.
Getting Started


**To start using Tokenplex:**
_frontend coming soon_

Connect Your Wallet: Link your Ethereum and Solana wallets to Tokenplex.
Transfer and Swap: Start transferring your Ethereum tokens and swapping them on Solana!
Support & Community
Join our growing community on Discord and Telegram. For any queries or support, reach out to our dedicated support team.

**Roadmap**
Our vision for Tokenplex is to serve as an incentivised hub of cross chain liquidity on solana. Whitepaper coming soon.

Contribute
Tokenplex is always on the lookout for passionate contributors. If you believe in our mission and want to be a part of our journey, check out our GitHub repository and contribute or give us feedback!

🌐 Visit our official website for more information. _coming soon_


© 2023 Tokenplex. All Rights Reserved.





