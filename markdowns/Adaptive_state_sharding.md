# Adaptive state sharding

Adaptive state sharding is the optimal approach to blockchain [sharding](sharding) where all three types of sharding are combined: 

 •	**State sharding:** <br>
 Where the “state” or history of the entire network is split across different “shards” or sections of the network. Each shard has its history/ledger, and nodes (computers connected to the network) only need to hold the state of the shard they are in, dramatically reducing the amount of latent storage capacity they require.
 
 •	**Transaction sharding:** <br>
In which transactions are mapped to shards for processing based on criteria like the sender’s address, and each shard processes transactions in parallel to other shards. Here, each node keeps a record of the state of the entire network.
 
 •	**Network sharding:** <br>
 Handles the way nodes are grouped into shards and can optimize communication, as sending messages to nodes in a shard can be done much faster than to the entire network.
 
Adaptive state sharding works as a solution to the scalability conundrum by improving communication inside shards and increasing the network’s performance and efficiency. It does this by combining all three sharding types into a solution that enables parallel processing on all levels. 
Shards are smaller sections of the network and are used for scaling. Each shard handles a portion of the state (accounts, smart contracts, blockchain) and transaction processing so that each shard can process only a fraction of the transactions in parallel with other shards.
