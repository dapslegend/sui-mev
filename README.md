# Issues 

Convert to mev lib that can run on diff chains: feasibile

use graph+bellman algo to find shortest path so it avoids long path: feasibile with more trading algo

reduce simulations/ support more dex: feasibile

steal private orders from validators: expensive but feasibile

Goal: Build Mev bot that support most chains spotting wilder range of swap and bridge opportunities

# Sui MEV Bot


## Run 
Start the bot with your private key.

```bash
cargo run -r --bin arb start-bot -- --private-key {}
```

## Supports

- BlueMove
- FlowX
- Aftermath
- Cetus 
- Kriya
- Abex
- Navi
- Turbos
- Deepbook
- Shio

## Relay
If you have a validator, you can let the validator push mempool transactions to your relay, which then send to the bot.

```bash
cargo run -r --bin relay
```
