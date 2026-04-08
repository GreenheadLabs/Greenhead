# Greenhead Labs

**A Transparent Private Treasury – Wyoming LLC**  
Building [greenhead.io](https://greenhead.io)

Open-source autonomous AI Agent that lives on **XRPL + EVM**.  
The agent continuously scans for profitable opportunities (arbitrage, yield farming, DEX trades) and executes tasks through `https://greenhead.io/x589/services`.

All treasury actions are secured by a 2-of-quorum XRPL multisig wallet with Tangem hardware (master key disabled).

## DID Identity
- **Primary DID**: `did:xrpl:1:rULKtUz2mA191LfxtzKvcHmzyNwzfNNU5J`
- **Treasury Account**: `rULKtUz2mA191LfxtzKvcHmzyNwzfNNU5J`

## Quick Start

```bash
git clone https://github.com/GreenheadLabs/Greenhead.git
cd Greenhead
cp .env.example .env
# Add your LLM API keys and node URLs to .env
pip install -e .
greenhead-agent
