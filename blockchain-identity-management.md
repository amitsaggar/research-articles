# Blockchain Technology & Identity/Auth Management

The Internet today lacks an identity protocol for identifying, authenticating people and organizations. As a result, enterprise/companies needed to build and maintain their own databases of user information. The current personal data ecosystem is feudal, fragmented, and inefficient. Too much leverage is currently accorded to service providers that enroll and register end-users. Their siloed repositories of personal data exemplify the fragmentation of the ecosystem, containing data of varying qualities.

### New Deal on Data

When thinking about opportunity in the financial business space, entrepreneurs may wish to consider the potential of creating these new forms of data brokers – “data exchanges” that re-empower the individual and provide new revenue opportunities


### Classification:
	Financial Institutions - Banks, Internet banks, Credit unions, Brokerage firms
	Credit bureau - Equifax, Experian and TransUnion
	Consumer tech - Credit karma, Credit sesame


## Keywords— blockchain; authentication; identity management; fintech; data quality; cost; fraud;

### Introduction: 

Authentication as a process of determining whether someone, in fact, who he/she is declaring to be, is the key component of any trustworthy online system which handles sensitive data or transactions. The process of authentication is visible to users and it directly corelated with their trust. An ideal authentication process should be efficient, reliable and able to verify data credentials while protecting user’s privacy. 

Identity management on the other hand is required to simplify the user provisioning process. Enabling new users to get access to services and de-provisioning users to ensure that only the rightful users have access to services and data.

Besides server-centric identity management, federated identity management is adopted currently where
many organizations allow users to use the same single identity on different online services. This comes in the form of single sign on or Facebook Login, Google ID etc.

We can also argue that identity management is a business issue but not a technology problem?

Blockchain can offer a solution by decentralizing the ownership of credentials and offering a universally available protocol for verifying one’s record in an immutable chain of data. Blockchain can create a secure platform for online service providers to authenticate users. Besides, this technology could also help to instill the trust back in users. Users should have full control over who has the right to use their data and what they can do with it once they gain access. To facilitate this peer-to-peer exchange of data and consent, routing of requests, mechanisms for discovery and recording of events, a decentralized network that is publicly accessible, immutable and resistant to faults and tampering is needed. Distributed ledger technology and Blockchain is the revolution that makes this possible. 

Increased transparency does not necessarily mean the end of privacy. Some cryptographic identity schemes offer strong privacy protection through identity anonymity and unlinkability of transactions.

Another long-running problem with identity is around the verification of user identity, in which there is no one responsible and liable for vetting data, fuzzy matching logic, the same problem where federated identity projects have become stuck. The solution to this problem is probably to extend the notion of zero knowledge proof in self-sovereign identity management. This leads to a mechanism in which the prover demonstrates possession of knowledge without conveying any information apart from the fact that he or she possess the knowledge...

A blockchain is a chain of blocks of valid transactions. Each block includes the hash to the prior block
in the blockchain. It uses a peer-to-peer network, which means every node in the network is connected to every other in the network. After the transaction is verified, it is broadcasted to the network and is added to everyone copy of the blockchain.

**Advantages of the blockchain technology includes:**
* Immutability: nothing on the blockchain can change. Any confirmed transaction cannot be altered.
* Permanence: A public blockchain will act as a public ledger, data will be accessible if the blockchain remains active.
* Removal of intermediaries: The peer-to-peer nature of the blockchain does away with the need of intermediaries.
* Speed: Transactions are much faster than a centrally controlled ledger.
* Security: Neither the node nor anyone else except the sender and the receiver can access the data sent across the blockchain. 

Let us discuss some basic concept of what a blockchain is and why it can be the best alternative to manage our data credentials and authentication process:

![Blockchain](/images/blockchain.jpg)

A block is referring to files where data pertaining to blockchain network is permanently stored. A block is like pages of a ledger or an account book. Each time a block is completed, it gives way to other block. Data stored in blocks cannot be altered. The genesis block, genesis.Json, is the first block of a blockchain. 

![Structured connections of Blockchain's blocks](/images/block1.png)

Merkle root is placed in the block header mentioned as “hashed list of all transactions that took place since the last created block”. “Merkling” the hashes of child nodes in the tree help verify contents for parents and generally large data structures.

The Merkle tree: The block is divided into two main categories which are the header and the body. The header has four components, a timestamp, a nonce, a hash reference to a previous block and a hashed list of all transactions that took place since the last created block. The blocks are stored in a multi-level data structure, a tree structure called the merkle tree. This structure is the key factor of the mining. The merkle tree or binary hash tree is a type of a binary tree, where the bottom of the tree contains the transactions (hashed), the intermediate tree nodes (leaves) contain the hash of the two nodes that made it, all the way till the top where it is a single hashed tree-node called the Merkle root (root hash). 

![An overview of merkel tree](/images/merkel.png)


*Depending on the consensus, there are three types of blockchain which are: public, private and consortium Blockchain*

Let us discuss private blockchains as it is relvant for our problem statement.

Private Blockchains are private and open only to a consortium or organizations that has decided to share the ledger among themselves like banks, credit bureau etc. Only the owner of the Blockchain has the right to make any changes to it. For example, Blockstack aims to provide the financial institutions with back office operations, including clearing and settlement on private Blockchain. There could be one related to credit monitoring and enrolling same user in different products by institutions(credit cards, loan etc.). 

However, the use cases of a private Blockchain are relatively small as compared to the public Blockchain. Some people may argue that private Blockchain is not of much used as the implementation concept does not differ much from that of the current systems. Nonetheless private blockchain can provide solutions to some of the problems which public blockchain cannot, such as know-your-customer (KYC), knowledge-based-auth KBA, reconcillation of data among all institutions involved as the entire network is continuously
verifying the integrity of it. This way, there is no breach of trust and a central entity, but security is guaranteed by the strength and computing power of the entire network/institutions participating in the blockchain. 

The immutable blockchain credit ledger verifies and ensures that the users, transactions, messages are legitimate, reconciled. This solution is saves cost for the service providers, efficient as
much of the information is not duplicated across different providers, very secure as evidenced by recent large-scale personal data breaches around the world.

*Note: Several blockchain startups are looking to use blockchain for online identity. A ShoCard, for example, is a digital identity that protects consumer privacy. ShoCard strives to be as easy to understand and use as showing a driver’s license; and simultaneously be so secure that a bank can rely on it. The key is that the ShoCard Identity Platform is built on a public blockchain data layer, so as a company it is not storing data or keys that could be compromised. According to ShoCard all identity data is encrypted, hashed and stored in the blockchain, where it cannot be tampered with or altered. A start-up in a similar vein that bridges the gap of both human and digital entities, is Uniquid. Uniquid allows for the authentication of devices, cloud services, and people.3 Uniquid’s aim is to provide identity and access management of connected things, as well as humans, utilizing biometric information for the latter*