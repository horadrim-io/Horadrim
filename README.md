# Horadrim
The Horadrim project uses zero-knowledge proof (zkSNARK) technology to implement confidential asset management based on smart contracts.

Taking the "off-chain computation, on-chain verification" approach, we avoid storing the entire world state in smart contracts, reducing GAS consumption.

The "Poseidon" hash algorithm is used to construct off-chain the world state based on "Incremental Merkle Tree", reducing the size of the zk-proof circuit. The nodes of the Horadrim project can synchronize the entire world state at any time.
