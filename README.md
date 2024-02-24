# FINAL_PROJECT
Peers:
Network Participants: Peers are nodes in the blockchain network that maintain a copy of the ledger and execute chaincode (smart contracts).

Data Replication: Peers replicate the blockchain ledger, ensuring that each peer in the network has an identical copy of the ledger.

Endorsement and Validation: Peers endorse transactions by simulating their execution against the chaincode and validating their correctness before they are added to a block.

Different Types: In Hyperledger Fabric, there are two types of peers: endorsing peers (also known as endorsing nodes) and committing peers (also known as committing nodes).

Responsible for Transactions: Peers play a crucial role in processing transactions, maintaining the integrity of the ledger, and ensuring consensus among the network participants.

Users:
Entities Interacting with the Network: Users are entities outside of the blockchain network who interact with it to submit transactions or query data.

Initiating Transactions: Users initiate transactions by sending transaction proposals to endorsing peers. These proposals contain the necessary information for executing transactions (e.g., invoking chaincode functions, providing transaction parameters).

Identity and Authentication: Users have identities within the network, which are managed through cryptographic keys or certificates. Authentication mechanisms ensure that only authorized users can interact with the network.

Transaction Endorsement: While users initiate transactions, they do not directly endorse them. Instead, their transactions are endorsed by endorsing peers in the network.

Querying the Ledger: Users can also query the blockchain ledger to retrieve information about transactions, assets, or other relevant data stored on the blockchain.
