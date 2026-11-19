# Mark Husiev

**Smart contract engineer** · Solidity, Foundry & TypeScript

I build Web3 products. My work ranges from paying freelancers one milestone at a time on Base to reconstructing a Polymarket trading session from events on Polygon.

## Lancerium

Lancerium is a freelance marketplace on Base that I built with a team at the Pond hackathon. Freelancers can start with a CV or an AI interview. Clients and freelancers swipe through recommendations, and a mutual match opens a conversation about the job.

I developed the matching logic and the USDC escrow flows. A client can fund milestones separately, release a payment when work is accepted, or open a dispute over a single milestone.

Our team won **Most Commercially Promising** at the Pond hackathon. [Pond’s announcement ↗](https://x.com/JoinPond/status/1955358461799305510)

[![Watch the Lancerium product demo on YouTube](assets/lancerium-demo.jpg)](https://youtu.be/8izlhSf17vg)

## Other systems I've built

| Project | My work |
| --- | --- |
| **WhaleHunt** · Polymarket | I built a Polygon indexer that turns onchain trades into historical datasets, and a visual editor for connecting and testing strategy rules. The team placed **third in the Prediction Markets track** at the Synth hackathon. [Hackathon results ↗](https://x.com/SynthdataCo/status/2034679657803784695) |
| **Multi-Signature Treasury** · Solidity | I built a treasury where the owners set how many confirmations a transfer needs. I tested what happens when an owner signs twice, an outsider tries to confirm, or an executed transfer is submitted again. |

## Selected work under NDA

### DeFi lending protocol

I implemented collateral and debt accounting, health-factor checks, and liquidations. I integrated Chainlink price feeds, including stale-price and decimal checks, and used Foundry to verify how a liquidation changes the borrower's debt and collateral.

### Token vault & rewards platform

I implemented reward-per-share accounting so an ERC-20 vault could calculate each depositor's claim without looping over every account. I tested rounding and failed transfers in Hardhat and connected contract events to a TypeScript service for transaction tracking.
