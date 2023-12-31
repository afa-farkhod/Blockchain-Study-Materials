# Blockchain-Study-Materials
Blockchain Study Materials &amp; Resources

### [Blockchain](https://en.wikipedia.org/wiki/Blockchain)

- `Blockchain` is a distributed ledger with growing lists of records (blocks) that are securely linked together via cryptographic hashes. Each block contains a cryptographic hash of the previous block, a timestamp, and transaction data (generally represented as a Merkle tree, where data nodes are represented by leaves). Since each block contains information about the previous block, they effectively form a chain (compare linked list data structure), with each additional block linking to the ones before it. Consequently, blockchain transactions are irreversible in that, once they are recorded, the data in any given block cannot be altered retroactively without altering all subsequent blocks.

<p align="center">
  <img src="https://github.com/af4092/Blockchain-Study-Materials/assets/24220136/f4e302ac-94b8-46a2-8efb-8967309e3d71" alt="Image">
</p>

- `BFT`(Byzantine Fault Tolerance) - the ability of a network or system to continue functioning even when some components are faulty or have failed. With a BFT system, blockchain networks keep functioning or implementing planned actions as long as most network participants are reliable and genuine.

<p align="center">
  <img src="https://github.com/af4092/Blockchain-Study-Materials/assets/24220136/ecca685f-c48a-449b-b2a9-fef910c7d063" alt="Image">
</p>

- `PoW`(Proof Of Work) -  is a blockchain consensus mechanism that incentivizes network validation by rewarding miners for adding computational power and difficulty to the network. It is a lottery system where miners increase their likelihood of receiving the reward the more power they add. In a PoW system, miners compete to solve complex mathematical problems associated with creating a new block. The first miner to successfully solve the problem gets to add a new block to the blockchain and is rewarded with a certain number of newly created cryptocurrency coins (e.g., bitcoins). This process is often referred to as `mining`.

<p align="center">
  <img src="https://github.com/af4092/Blockchain-Study-Materials/assets/24220136/abe372f4-cf69-4554-89c0-636a7558d13f" alt="Image">
</p>

- `PoS`(Proof Of Stake) - is a consensus algorithm used in blockchain networks to achieve agreement on the state of the system. Unlike Proof of Work (PoW), where participants (miners) solve complex mathematical problems to validate transactions and create new blocks, PoS relies on validators who hold and "stake" a certain amount of cryptocurrency to create new blocks and validate transactions.

<p align="center">
  <img src="https://github.com/af4092/Blockchain-Study-Materials/assets/24220136/db363307-228c-4b82-af13-14ec7c9c287d" alt="Image">
</p>

- `PoA`(Proof Of Authority) - is a consensus algorithm used in blockchain networks to secure and validate transactions. It's a variation of the more well-known Proof of Work (PoW) and Proof of Stake (PoS) algorithms. In a PoA consensus mechanism, validators or nodes are chosen based on their authority(reputation) or identity.

<p align="center">
  <img src="https://github.com/af4092/Blockchain-Study-Materials/assets/24220136/a71d1758-59c0-4c64-8d1d-c2b9671d2226" alt="Image">
</p>

- `DPoS`(Delegated Proof of Stake) - is a consensus algorithm used in blockchain networks to achieve agreement on the validity of transactions and create new blocks. It is a variation of the Proof of Stake (PoS) consensus mechanism. In a DPoS system, token holders in the blockchain network can vote for a limited number of delegates (often referred to as "witnesses" or "validators") who are responsible for validating transactions and creating new blocks. These delegates play a critical role in the network's operation and are elected based on the number of tokens they hold or the number of votes they receive from other token holders. A DPoS blockchain uses a voting system where the stakeholder community outsources its work to third parties. They regain the right to vote for a few delegates who will care for network security on their behalf. The delegates are also called witnesses, and they are responsible for achieving consensus. In doing so, they ensure the generation and validation of new blocks.

<p align="center">
  <img src="https://github.com/af4092/Blockchain-Study-Materials/assets/24220136/ab08bb03-2341-495a-b486-b60be5da5c62" alt="Image">
</p>

- `dApp`(decentralized application) - is a software application that operates on a decentralized network (usually a blockchain) rather than a central server. It leverages the principles and features of blockchain technology to provide decentralized and distributed functionality.

<p align="center">
  <img src="https://github.com/af4092/Blockchain-Study-Materials/assets/24220136/1a4ea8b3-2f85-4794-9551-fb3b73fc21cf" alt="Image">
</p>

- `ABCI`(Application BlockChain Interface) - The purpose is to provide a clean interface between any finite, deterministic state transition machine on one computer and the mechanics of a blockchain-based replication engine across multiple computers (aka consensus engine, which involves the consensus and networking layers).

<p align="center">
  <img src="https://github.com/af4092/Blockchain-Study-Materials/assets/24220136/6cb4e929-d4f0-460b-82c9-fec7a8c66d93" alt="Image">
</p>

- `MEV`(Maximum Extractable Value) - refers to the maximum value that can be extracted from block production in excess of the standard block reward and gas fees by including, excluding, and changing the order of transactions in a block.

<p align="center">
  <img src="https://github.com/af4092/Blockchain-Study-Materials/assets/24220136/52995e95-6321-4a4a-b4ec-27bc54688d61" alt="Image">
</p>
