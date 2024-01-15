# Polar-mempool

Adds mempool.space webapp to a local polar regtest environment

## Prerequisites

- install docker
- install docker-compose
- install https://github.com/jamaljsr/polar
- setup a local testnet with at least one bitcoin-node

Note
If you have more than one local testnets, you can specify the network by changing it in the docker-compose.yml file. By default the first polar-network-1_default ist used.

## Usage

```
git clone https://github.com/ngutech21/polar-mempool.git
cd polar-mempool
docker-compose up -d
open browser at http://localhost:8080

```
