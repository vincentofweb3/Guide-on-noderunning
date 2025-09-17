# Guide-on-noderunning
This Guide is for every person who w'd like to start noderunning.

𝗪𝗵𝗮𝘁 𝗮𝗿𝗲 𝗖𝗿𝘆𝗽𝘁𝗼 𝗡𝗼𝗱𝗲𝘀??

Crypto nodes are basically computers that keep a blockchain running. They help check transactions, store the records, and make sure the network stays secure and up to date.

Types of Crypto Nodes??

Here are the main ones you really need to know:

-•• **Full Nodes** :

- This Full Node Stores the entire blockchain history.

- Independently check and verify every transaction.

- Enforce the blockchain’s rules (called consensus rules).

Example: Bitcoin Core node.

-•• **Light Nodes** :

- Keep only part of the data (like block headers, not full blocks).

- it Depends on full nodes to confirm transactions.

- Commonly used in mobile wallets or lightweight apps.

-•• **Validator Nodes** :

- Take part in approving and adding new blocks to the chain actively.

- Common in Proof-of-Stake systems (Ethereum 2.0, Solana).

- Usually require staking coins as a security deposit.

-•• **Mining Nodes** :

- Try to solve cryptographic puzzles (Proof-of-Work).

- Used in Bitcoin and older networks to create new blocks.

- Basically a subset of full nodes with extra work.

-•• **RPC Nodes** :

“Remote Procedure Call” nodes - one of the most important ones.

They let apps talk to the blockchain by:

- Reading data (balances, blocks, transaction status).

- Sending transactions (token transfers, contract calls).

Think of them as the gatekeepers between your app and the blockchain.

-•• **Worker Nodes** : 

Worker nodes are nodes that Do the heavy lifting tasks in a network or perform actual tasks assigned to them, but don’t control the overall system.

1)  In centralized tech

- It Runs your apps or containers (e.g., Docker).

- It Gets instructions from a master node (control plane).

2)  In decentralized compute networks (like Gensyn, Akash, Render, Bittensor)

- Run AI models, ML training, or GPU-heavy tasks.

-> Example: Gensyn’s RL Swarm acts as worker nodes.

3)  In blockchain validator systems (Polkadot, Cosmos, L2 rollups)

- It Handle execution of transactions.

- Generate zero-knowledge proofs.

- Do tasks like sequencing, state updates, or fraud proofs.

These are the core nodes you should know. There are others like storage nodes, but these are the essentials. 
