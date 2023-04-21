![Nois Banner](img/banner.jpeg)

# Nois Network
Nois is a layer 1 blockchain that Brings random beacons to Cosmos blockchains without compromising security or usability by leveraging drand and IBC.
Nois logic is written on smart-contracts formats with CosmWasm.
## Repositories
Some important repositories to check out:
* nois-contracts: This is where the smart contracts are. 
* noisd: This is the full node chain cosmos-sdk binary of Nois
* networks: This repository holds the genesis file for every Nois network
* deployments: Holds the contract deployment scripts aswell as the drand-bot allow list 
* nois-dapp-examples: Some examples of contracts that can use the randomness beacon of Nois
* website: The code for the actual https://nois.network website
* docs: The documentation of Nois under https://docs.nois.network
* pingpong: An end to wnd simulation/montoring tool where an app deployed on juno requests randomness from Nois and exports important time metrics. 
* nois-bot: A drand-bot implementation
* bot2: Another drand-bot implementation
* nois-oracle-dashboard: The dashboard you see here https://randomness.nois.network/
* address-generator: this UI https://address.nois.network/
* nois-randomness-simulator: An offchain randomness simulator https://simulator.nois.network/
* ibc-visualizer: A UI to check  what IBC clients/connections/channels Nois has with other chains. https://ibc.nois.network/ 
