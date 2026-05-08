# Solana Smart Money Hunter AI

AI-powered Solana trading agent built for the Agentic Wallet Trading Competition.

## Overview

This skill monitors smart money wallets on Solana and detects early meme coin opportunities with automated risk management.

The agent can:
- Detect smart money accumulation
- Filter low market cap tokens
- Run security checks
- Execute automated buys
- Manage take profit and stop loss
- Generate real-time trading reports

## Features

### Smart Money Tracking
Track wallets with profitable trading history and monitor new token activity.

### AI Risk Analysis
Analyze:
- liquidity
- holder distribution
- token taxes
- suspicious contracts
- whale accumulation

### Automated Trading
Example workflow:
1. Detect token
2. Security check
3. Auto buy
4. Monitor price
5. Auto take-profit
6. Auto stop-loss

## Example Strategy

```txt
Monitor Solana meme coins under $5M market cap.

Conditions:
- At least 2 smart money wallets buying
- Liquidity above $50k
- Security checks passed

Buy:
- 1 USDT position size

Risk Management:
- Take profit at +50%
- Stop loss at -20%
- Trailing stop enabled
```

## Example Commands

### Check Wallet Balance

```bash
onchainos wallet balance --chain solana
```

### Swap SOL to Token

```bash
onchainos swap execute \
--from 11111111111111111111111111111111 \
--to <TOKEN_ADDRESS> \
--readable-amount 0.01 \
--chain solana \
--wallet <YOUR_SOL_WALLET>
```

### Monitor Smart Money

```txt
Monitor smart money wallets buying meme coins on Solana.
```

## Security

This project does not store private keys or sensitive user credentials.

All execution is performed through Agentic Wallet authorization.

## Built For

OKX Agentic Wallet Trading Competition

## Creator

JasonDev
