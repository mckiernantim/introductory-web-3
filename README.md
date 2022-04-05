# Introductory Crypto
Over the past decade the field of crypto currency has exploded in popularity.  Backed by a tecnology called 'blockchains' crypto technologies have emerged as a new player and a possible major disruptor to many tech sectors.  While originally designed for creating currency, blockchains have evolved and are now being used to power applications in a 'decentralized' network. The term Web 3 refers to a new phase of the internet focused on peer-to-peer networks with no central authority all secyred by powerful cryptography.

## Some History Of The Web
The history of the web can be broken down into three phases.

### Web 1.0 
The first stage of the internet  spanning roughly the years 1990-2000.  Web 1.0 is considered 'read-only' with very little user generated content. Users mostly navigated to websites and consumed static pages and rarely did they interact with one another or create financial transactions.

![Web 1.0 image.](./assets/web1.png)

### Web 2.0
The current version of the web roughly spanning the years 2000-present.   Increases if internet speed and fiber optic infrastructure allowed for the evolution of streaming content and coud based infrastructre.  Encryption technologies also made financial interactions via the internet far more secure than they were in web 1. Web 2.0 is also the era of the social web.


Web 2.0 made publishing content to the internet something everyone in the world could do with little to no training. Companies like Google, Amazon, and Facebook provide users services in exchange for their data. These companies then sell the user data for a profit and control is centralized in the hands of the companies that provide the service.  However, the rise of data as a commodity has rasied many ethical concerns over privacy, censorship, and ultimately what role companies that provide a service should have with the data they get from their users.
![Web 2.0 image.](./assets/web2.png)

### Web 3.0

The term Web 3 refers to a version of the interent that is fundamentally decentralized.  Rather than applications being controlled by massive companies like Google or Amazon, computational power is shared among numerous devices and blockchain technology insures that data is open, accessable, and decentralized, not hoarded by large companies.  In essence, the users dictate what is done with their data.  
Web 3 technology relies on the use of blockchain technology and something called Smart Contracts to execute applications that run on open and available data sources.  Web 3 apps are not controlled by any central authority but rather are linked to the blockchain that they exist on in order to run.  These blockchains are open and accessable meaning nothing is ever hidden from the users.

![Web 3.0 image.](./assets/web3.png)



## Web 3 Terminology
Web 3 has a lot of hype surrounding it and words like "Dapp", "Gas", and "Mining" are often thrown around.  In order to understand how web3 apps are structured we need to understand these concepts before we can begin to build applications for this new paradigm of the internet.
### Cryptocurrency
Cryptocurrency is a digital payment system that doesn't rely on banks to verify transactions. It’s a peer-to-peer system that can enable anyone anywhere to send and receive payments. Instead of being physical money carried around and exchanged in the real world, cryptocurrency payments exist purely as digital entries to an online database describing specific transactions. When you transfer cryptocurrency funds, the transactions are recorded in a public ledger. Cryptocurrency is stored in digital wallets.  Crypto curencies are the payments that fund all Web 3 apps and transactions.
### Blocks
A block is an individual unit of storage that holds information in a database known as a blockchain.  A Block is very similar to the node of a Linked List. Blocks have a limited ammount of storage but always have a link to the block that came before them, unless they are the original block (which we will never have to worry about!). When we organize blocks together we create a Blockchain, which is the backbone of all Web 3 technology.

### Blockchains

One way to think of a blockchain is like ledger for a bank.  Imagine a record of every financial transaction that ever happened involving the US Dollar since it was invented.  That list would be <em>enormous</em> but with powerful enough computers it would be possible.  The Bitcoin blockchain is essentially that same concept, a continual record of every bitcoin transaction that has every been made.

Fun fact: as of 3/26/2022 the current [bitcoin ledger](https://ycharts.com/indicators/bitcoin_blockchain_size) is 397.53 GB of data.  This very large file is then distributed across an entire network of computers all over the world.

![Web 3.0 image.](./assets/blockchain.png)

Each Block has a limited amount of storage.  Once filled, a new block is created and the new block points to the previous block which in turn points to its previous block forming a chain or Blockchain.
This ordering creates a chronological record of everything that happens on the blockchain and as a result, an open record of every transaction that the blockchain has ever made.  

When we refer to Web 3 applications we are most often refering to building applicaitons on the [Ethereum Blockchain](https://ethereum.org/en/)

In 2008, Satoshi Nakamoto created the [Bitcoin Whtepaper](https://bitcoin.org/bitcoin.pdf) which outlined the basics of what became known as "Blockchain" and led to the worlds first cryptocurrency.

### Nodes

A Node is a device on a blockchain network that allows the blockchain to remain open and decentralized.  All Nodes on a blockchain have a copy of the entire blockchain  that they belong to.  Every Bitcoin node has the entire Bitcoin ledger stored locally and the same is true of every Ethereum Node and the Ethereum ledger. This widely dispersed network ensures that information is secrure and readily available.  Nodes provide the computational infrastructure needed to make web3 possible.

### Wallet

A wallet is a string of numbers and letters like the following
```
18c177926650e558898003c320e136f22373b75
```
This string serves an adress that will appear on blocks as transactions occur on the blockchain.  This string is <strong>public</strong> and is one of the requirements for a transaction to occur.  This wallet is what is used to send money to a blockchain that is then distrubited to other wallets in order to send or recieve funds.  

### Private Key

To carry out a transaction you need two things: a wallet, which is basically an address, and a private key. The private key is another string of random numbers but unlike the wallet this <strong>must be kept secret</strong>.

A private key is an extremely large number that is used in cryptography, similar to a password. Private keys are used to create digital signatures that can easily be verified, without revealing the private key. Private keys are also used in cryptocurrency transactions in order to show ownership of a blockchain address. Essentially, the private key is how a user can access their secure transactions and <em>only theirs</em>.

### Minning

The term mining can mean different things on different blockchains but always refers to some form of computational work being done to the distributed ledger.  Minnig can be energy spent creating new coins to add to the ledger or for validating transactions on the blockchain between different parties.  The two common forms of mining are Proof Of Work (Bitcoin) and Proof Of Stake (Ethereum 2.0).  Mining refers to the actual <strong>work</strong> done to make a blockchain function.

### Proof-Of-Work

Crypto mining is similar to the work done in actual physical mining.  Rather than pulling precious metals or gems from the ground, crypto miners trigger the release of new coins into circulation or use their power to validate certain transactions or smart contracts.

For miners to be rewarded for their work, they must use their machine to solve incredibly complex mathemetical equiations.  Each transaction on the blockchain will create a specific signautre, called a Hash.  
Once a transaction has been created miners will compete with one another to zero in on the hash value it created.  The first miner to crack the code adds the block to the ledger and the new ledger is distributed across all the nodes in the network and the miner who did the work receives a reward, usually in the form of cryptocurrency or in some cases a small transaction fee sometimes refered to as "gas".

As Bitcoin grew in popularity, the ammount of miners attempting to validate new transactions grew as well.  This growth meant a huge uptick in power required to consistently mine bitcoin and as a result Bitcoin Hashes became much much more difficult to solve.


While the sucess of Bitcoin has shown that Blockchains and proof of work do in fact work, the proof of work paradigm has created an arms race between miners.  As a result the amount of power needed to effectively mine bitcoin has skyrocketed and currently the amount of power used just to mine Bitcoin now equals the output of the entire nation of [Chile](https://www.dallan.com/en/news/bitcoins-energy-consumption-greater-than-chile-austria-and-the-czech-republic/)
<img  src="./assets/pow.png" style="width:400px; height:350px"/> 
![Proof of work diagram](./assets/pow.png)
### Proof-Of-Stake

Another, new method for validating transactions on the Blockchain is Proof Of Stake.  Rather than having miners compete to be the first to solve a very complicated math equation, when a block of transactions is ready to be processed, the cryptocurrency's proof-of-stake protocol will choose a validator node to review the block. The validator checks if the transactions in the block are accurate. If so, they add the block to the blockchain and receive crypto rewards for their contribution. However, if a validator proposes adding a block with inaccurate information, they lose some of their staked holdings as a penalty.  

This model rewards miners for staking more of their coin and uses much less electricity than Proof of work.  Additionally, miners are not required to obtain powerful, specialized computers in order to mine.



![Proof of stake diagram](./assets/pos.png)
