## Header
This is the course header. This will be added on top of every page. Go to [DoDAO.io](https://www.dodao.io) to know more.

 ---
 
 ## Blockchain Intro
 
 **What is Blockchain?**        
Blockchain is a decentralized, distributed digital ledger that records transactions across a network of computers. Transactions are verified and recorded through cryptography, making it nearly impossible for any one user to alter the record retroactively without being detected by the network. The result is a system that is transparent, secure, and resistant to censorship, and one that allows multiple parties to have a shared and consistent view of a database without requiring a central authority. This makes it particularly useful for applications such as cryptocurrencies, digital contracts, and other applications that require a secure and transparent way of tracking transactions.

 
 **Blockchain Ledger**        
A blockchain ledger works by maintaining a growing list of records, called blocks, which are linked and secured using cryptography. Each block contains a cryptographic hash of the previous block, a timestamp, and transaction data. This creates a chain of blocks, hence the name "blockchain."

When a new transaction is initiated, it is broadcast to the network of nodes (computers) that maintain the ledger. These nodes then validate the transaction using algorithms built into the blockchain protocol, such as checking that the sender has enough funds to complete the transaction. Once validated, the transaction is added to a block and the block is added to the blockchain.

Each node in the network has a copy of the entire blockchain, and all nodes must reach consensus on the state of the ledger before any new block can be added. This ensures that the ledger is consistent and tamper-proof, as any attempt to alter a block would require a majority of nodes to agree to the change, which is highly unlikely.

The decentralized and secure nature of the blockchain ledger makes it ideal for a wide range of applications, including secure record keeping, smart contracts, and digital currencies.

 
 **Hashing**        
Hashing is an essential concept in blockchain technology and plays a crucial role in maintaining its security and integrity.

A hash is a mathematical function that takes an input (or "message") and returns a fixed-size string of characters, which is typically a "digest" that is unique to the unique values of the input. In the context of blockchain, hashes are used to represent the data stored in a block, such as transaction data.

When a new block is added to the blockchain, the hash of the block is calculated using the hash function. The hash of the previous block is also included in the calculation of the new block's hash. This creates a chain of blocks, each with a unique hash, and a reference to the previous block's hash. As a result, any change to the data in a block will result in a different hash for that block, which would be easily detected.

This is why hashes are important in blockchain technology. They ensure that once a block has been added to the blockchain, its data cannot be altered without also changing the hashes of all subsequent blocks, which would be noticed by the network and rejected.

In summary, hashing is a key component of blockchain technology that helps to ensure the integrity and security of the data stored in the blockchain by creating a chain of hashes that reference each other and can detect any changes to the data. 
 **Transactions**        
In a blockchain, money is transferred through a process called a "transaction." A transaction is simply a transfer of value from one person (or address) to another.

Here's how a typical transaction works on a blockchain:

1. The sender creates a new transaction with the details of the recipient (their address), the amount to be transferred, and the sender's private key to sign the transaction.
2. The transaction is broadcast to the network, where it is verified by nodes (computers) that make up the network.
3. The verified transaction is then added to a block along with other transactions, and the block is added to the blockchain.
4. The recipient can now access the funds by using their private key to unlock the transaction.

In a blockchain network that uses a cryptocurrency, such as Bitcoin, the value being transferred is in the form of digital coins. The transaction updates the balance of the sender and recipient's addresses on the blockchain.

It's important to note that in a public blockchain network like Bitcoin, transactions are transparent and can be seen by anyone. However, the identity of the individuals behind the addresses remains anonymous, as only the address is recorded on the blockchain.

 
 **Smart Contracts**        
Smart contracts are self-executing contracts with the terms of the agreement directly written into code. They are a fundamental building block of blockchain technology and are used to automate the process of executing the terms of a contract when certain conditions are met.

Smart contracts are stored on the blockchain and are executed automatically by the network. They are transparent, secure, and tamper-proof, as the code and terms of the contract are visible to everyone on the network.

Once a smart contract is deployed on the blockchain, it can be used to automate various processes, such as:

- Transferring funds between parties when certain conditions are met, such as the delivery of a product or the completion of a task.
- Managing the ownership of assets, such as real estate or art.
- Automating the process of voting, by counting votes automatically and transparently.
- Enforcing the terms of an agreement, such as an insurance policy or a loan agreement.

Smart contracts have the potential to disrupt many industries by eliminating the need for intermediaries and speeding up transactions while making them more secure and transparent. 
 
