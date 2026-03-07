# shieldfi-api
API infrastructure for ShieldFi wallet risk intelligence
The ShieldFi API provides access to wallet risk scores and security intelligence for developers and Web3 platforms.

Example endpoint:

GET /wallet-score/{wallet_address}

Response example:

{
  "score": 82,
  "risk_level": "medium",
  "flags": ["suspicious interaction"]
}

Developers can integrate ShieldFi to detect risky wallets before transactions are executed.
