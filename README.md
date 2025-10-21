SubLockX
SubLockX is a decentralized subscription and recurring payment protocol on the Stacks blockchain.
It allows creators, developers, or platforms to receive automated STX payments from subscribers at fixed intervals — fully on-chain and transparent.

Features
On-chain recurring subscriptions
Start, renew, or cancel anytime
Time-based payment locking
Transparent payment history via events
Supports multiple subscribers per provider

Technical Overview
Language: Clarity
Core Functions:
create-subscription → Start a new subscription
renew-subscription → Extend active period
cancel-subscription → Cancel future payments
check-status → Verify if active
withdraw → Provider withdraws collected funds
Data Stored:
Amount per cycle
Interval (in blocks or timestamps)
Next renewal date
Subscription status (active/inactive)

Roadmap
Add FT (token) payment support
Enable multi-tier subscription plans
Introduce DAO-based provider governance
Integrate with decentralized identity (DID) for verification
