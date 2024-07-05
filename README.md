# BlockchainProject

This blockchain project lays a strong foundation by implementing the core structure of blocks and the blockchain itself. Key features include:
1. Block Structure: Well-defined block headers contain metadata like version, previous block hash, timestamp, and more. Blocks encapsulate transaction data, header, height, and hash.
2. Blockchain Management: We provide functions to add new blocks to the blockchain after verifying their integrity and provide placeholders for listening for blocks and propagating newly added blocks on the network.
3. Immutability: SHA-256 hashing provides unchangeable identification for blocks, preventing alterations.
4. Dynamic Difficulty Adjustment: A key feature, the system automatically adjusts mining difficulty based on previous block generation times. This ensures a consistent pace of block creation, even as computational power on a potential network fluctuates.
5. User Interface: An interactive loop offers users several ways to interact with the blockchain. They can add new blocks with custom data, insert sample blocks for testing, visualize the blockchain's structure, and directly witness the effects of difficulty adjustments.
