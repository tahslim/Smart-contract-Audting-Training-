# Chapter 1: What is Ethereum???

According to the Ethereum Yellow Paper, Ethereum is a project which attempts  to build the generalized technoocy; technolgy on which all transaction-based state machine concepts may be built. Unlike Bitcoin, Ethereum's main goal is an ecosystem where developers can creatively build softwares via a template(smart contracts) using a peer-to-peer network integration.
All transactions are erified uisng sets of consensus rules/mechanisms. While Ethereum started as a Proof of Work(PoW) consensus protocol, it has been disocntinued for a more preferred protocol, Proof of Stake(PoS) following a hard fork. Whenever the word "Ethereum" is been mentioned, the closest attribute that comes to mind for most people, is blockchain. But blockchain goes a step deeper n describing Ethereum, as its an open, public and decentralized blockcbhain, unlike many others in the blockcahin space.


# Chapter 2: Ethereum Basics

Ethereum creates a medium of accountability for several actions in the ecosystem, which we all know as ether. It is important to note that ether comes in sub-units with the smallest unit called "wei". Before one can transact on the Ethereum blockchain, you need a "trusted: wallet. Some popular examples are Metamask, Emerald wallet and Jaxx, to name a few. And though, Ethereum prides itself as an open blockchain, it also poses a risk as control becomes a huge responsibility on the part of the user/developer. These responsibilities include protecting one's private keys and never saving them digitally.
As stated earlier, transacions on the Ethereum blockchain requires a wallet or a contract. Wallets are also known as Externally Owned Accounts(EOA) while other accounts are known as contract accounts. One of the key differences between these two types of accounts, is thatEOAs can intitiate transactions while contract accounts can only "react" to transactions.
It is encourages to get a feel of what transactions look like, for beginners, using a test faucet. Due to the recent hard forks, the availabke test faucets are Goerli and Sepolia.


# Chapter 3: Ethereum Clients

Remember we defined Ethereum as been  a world computer which simply means it has to run on some form of software often referred to as "Ethereum Clients". It also has the minimum specification requirements just like most softwares we run on our perosnal of enterprise computers. The Ethereum Yellow Paper does enough justice prescribing the minimum and recommended requirements for running the Ethereum Client. It is also important to note that the clients comes in different languages such as 

- Geth, written in Go
- Parity, written in Rust
- cpp-ethereum, written in C++
- Mantis, written in Scala
- Harmony, written in Java
- pyethereum, written in Python


# Chapter 4: Cryptography

One of the main goals of Ethereum was to achieve a decentralized network where transactions were done without 3rd party trustees, and with a certain level of anonymity via a branch of mathematics called " cryptography". Cryptography, as most computer science folks know, is a means of encrypting mssages/data in plan sight for the protection of account users/developers. The widely used type of crytography in the Ethereum ecosystem, is the Public Key Cryptography(PKC).
keys are an essential part of the Ethereum ecosystem and are never transmitted or stored on Ethereum, nevertheless, in order to keep private keys secure, there is a need for strict "control and responsibility" which will be discussed in later chapters. It is worthy to note that the method of transaction on the Ethereum system works with both private and public keys, to ensurea secure channel at all times. When a transaction is inititiated, the datat is encrypted as a cryptographic hash function, which maps the data to a fixed-size string of bits. This form of encryption holds certain properties such as:

- Determinism
- Verifiability
- Non correlation
- Irreversibility, and
- Collision protection


# Chapter 5: Wallets

Interactions within the Ethereum blockchain involves the use of ethereum wallets. While wallets have several definitions from different perspectives, that of a developer refers to a system used to store and manage user's keys. This swerves as a simple solution for managing tokens as well, thoughcomes with its own sets of risk. There are two types of wallets; non-deterministic and deterministic wallet, and the difference between the two been that keys are independently generated from a random number for non-deterministic wallets, while for determinstic wallets,the keys are derived from a single master key known as the seed.
In order to add layers of security to wallets,common standards have been enforced such as;

- Mnemonic code words based on BIP-39
- HD wallets based on BIP-32
- Multipurpose HD wallets structure based on BIP-43
- Multicurrency and multi-account wallets based on BIP-44
    
