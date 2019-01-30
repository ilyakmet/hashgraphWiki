# Hedera: A Governing Council & Public Hashgraph Network
## The trust layer of the internet
### Leemon Baird, Mance Harmon, and Paul Madsen
> Whitepaper v1.4 last updated 17 Oct 2018 subject to further review & update  

## Vision 
The Hedera Hashgraph Council will provide governance for an open, fast and fair decentralized public ledger built on the hashgraph consensus algorithm. Governance will be maintained by a council of up to 39 known and reputable global organizations, committed to the support and evolution of a stable, predictable public ledger infrastructure. 

## Executive Summary 
Distributed ledger technologies (DLT) are disrupting and transforming existing markets in multiple industries. However, in our opinion there are five fundamental obstacles to overcome before distributed ledgers can be widely accepted and adopted across every industry and geography. In this paper we will examine these obstacles, and discuss why Hedera hashgraph is ideally suited to be the world’s first mass- adopted public distributed ledger, supporting a vast array of applications. 

1. **PERFORMANCE** – The most compelling use cases require hundreds of thousands of transactions per second in a single shard (perhaps millions of transactions per second (tps) in a fully-sharded solution), and many require consensus latency measured in seconds. These performance metrics are orders of magnitude beyond what current public DLT platforms can achieve. 
2. **SECURITY** – If public platforms are to facilitate the transfer of trillions of dollars of value, we have to expect them to be targeted, and we have to prepare for this. To do so requires a consensus algorithm that provides the best security one can achieve, with the security properties of the algorithm formally proven. Vectors of security vulnerabilities shouldn’t be mitigated; they should be eliminated entirely. Other public DLT platforms are trading off decentralization (and so potentially compromising security) for performance gains. 
3. **GOVERNANCE** – A general-purpose public ledger should be governed by representatives from a broad range of market sectors, each with world-class expertise in their respective industries, and also selected to provide global geographic representation for all markets. Those that are governing need technical expertise so they can competently manage 
the technical roadmap. They need business expertise so they can manage business operations of the organization. They need expertise in economics and currency markets so they can manage the cryptocurrency. They need legal expertise to help navigate the evolving regulatory environment. In other words, governance should be by those globally recognized as world leaders in their respective industries, and representative of every market in the world. 
4. **STABILITY** – Without technical and legal mechanisms to enforce the decisions of the governing body, public platforms are at risk of devolving into chaos. Strong security and mature governance will enable a stable platform - one that engenders the necessary trust and confidence among those that would build commercial or sensitive applications on it. 
5. **REGULATORY COMPLIANCE** – We expect that governments will continue to increase oversight of public ledgers and associated cryptocurrencies and tokens. We consider that a distributed public ledger must be capable of enabling appropriate Know Your Customer (KYC) and Anti Money Laundering (AML) checks. 

<br>
<p align="center">
  <img src="https://github.com/ilyakmet/hashgraphWiki/blob/master/img/1.jpg" width="620" height="438px">
</p>
<br>

What is required to move our industry forward and enable it to realize its full potential? 

A platform that provides a combination of high performance, strong security, industry-leading governance, and both technical and legal controls to ensure the stability of the platform. Only then do we think mainstream markets will trust the platform enough to adopt public DLT *en masse*. 


## Introducing Hedera – a governing body and public hashgraph network designed to address the needs of mainstream markets. 
Hedera will be governed by a council of renowned enterprises and organizations, across multiple industries and geographies. Its vision is a cyberspace that is trusted, secure, and without the need for central servers. Its licensing and governance model protects the community by eliminating the risk of splitting, guaranteeing the integrity of the codebase, and providing open access to the protected core. All Governing Members will have equal governing rights and each Governing Member (with the exception of Swirlds, Inc.) is expected to serve a limited term, ensuring that governance is decentralized.(2) 

Hedera is both an organization and distributed ledger platform that resolves the factors that constrain adoption of public DLT by the mainstream. 

1. **PERFORMANCE** – The platform is built on the hashgraph distributed consensus algorithm, invented by Dr. Leemon Baird. Hashgraph provides near-perfect efficiency in bandwidth usage and consequently can process hundreds of thousands of transactions per second in a single shard (a fully-connected, peer-to-peer mesh of nodes in a network). Consensus latency is measured in seconds, not minutes, hours, or days. 
2. **SECURITY** – Hashgraph achieves the gold standard for security in the field of distributed consensus: asynchronous Byzantine Fault Tolerance (aBFT). Other platforms that use coordinators, leaders, or communication timeouts tend to be vulnerable to Distributed Denial of Service (DDoS) attacks against those vulnerable areas. Hashgraph is resilient to these types of attacks against the consensus algorithm, and achieves the theoretical limits of security defined by aBFT. Achieving this level of security at scale is a fundamental advance in the field of distributed systems as it is the gold standard for security in this category. 

Many applications require that the consensus order of transactions match the actual order in which the transactions are received by the network. It should not be possible for a single party to prevent the flow of transactions into the network, nor influence the order of transactions in the eventual community consensus. A fair consensus algorithm ensures that if a user can submit a transaction to the network at all, then the transaction will be received by the network and the order in which it was received will be a fair ordering. Hashgraph uniquely ensures that the actual order transactions are received by the community will be reflected in the consensus order. In other words, hashgraph ensures both *Fair Access*and *Fair Ordering*. 

Formal proofs of the ABFT and fairness properties for the hashgraph consensus algorithm exist and have been available for public review since June, 2016. Furthermore, the hashgraph algorithm has been validated as ABFT by a math proof checked by computer using the Coq system in October, 2018.(3)

3. **GOVERNANCE** – Hedera governance is comprised of two parts: _Council Governance_, used for the management of the business of the council, and *Consensus*used in the Hedera platform for determining the consensus order of the transactions. The *Council Governance Model*concerns the election of the Board of Managers of Hedera (Governing Board). The Governing Board will establish policy for council membership, regulate the network tokens, and approve changes to the platform codebase. The *Consensus Model*concerns the process by which the nodes reach a consensus on the order of transactions in
the platform. Our proposed model is designed to prevent consolidation of power over consensus. It will prevent collusion by a few to attack the system (such as efforts to counterfeit the cryptocurrency, modify the ledger inappropriately, or influence the consensus order of transactions). 

**a.** _Council Governance Model:_ Hedera will be governed by up to 39 leading organizations in their respective fields, bringing needed experience in process and business expertise that has been absent in previous public ledger platforms. Membership criteria are designed (i) to reflect a range of industries and geographies, (ii) to have highly respected brands and trusted market positions, and (iii) to encompass competing perspectives. The Governing Members will elect the Board of Managers and also contribute expertise through subcommittee membership. The terms of governance ensure that no single member will have control, and no small group of members will have undue influence over the body as a whole. 

**b.** _Consensus Model:_ Loosely stated, each node casts one vote for each coin of the hbar cryptocurrency they own. New nodes will join the network, and be compensated for their services in maintaining the hashgraph. The number of nodes is expected to grow rapidly, ensuring consensus voting privileges are distributed to many thousands of nodes.

4. **STABILITY** – Hedera relies on both technical and legal controls to ensure the stability of the platform. 

Hedera technical controls enable two capabilities. 

**i)** First, the hashgraph technology ensures that software clients validate the pedigree of the Hedera hashgraph prior to use through a shared state mechanism. It isn’t possible for a network node to fork the official version of the Hedera hashgraph platform, make changes, and then have those changes accepted as valid. If the original hashgraph and the copy are changed independently, software clients will know which is the valid version and which is not. 

**ii)** Second, the hashgraph technology makes it possible for the Hedera governing body not only to specify the software changes to be made
to network nodes, but also to ensure precisely when those changes are adopted, and to guarantee that they are. When the Hedera governing body releases a software update, all honest network providers will have their software automatically update, and all will do so at exactly the same moment in history. Anyone with invalid software will no longer be able
to modify the hashgraph and have the world accept their version of the hashgraph as legitimate. 

Hedera legal controls ensure the platform will not fork into a competing platform and cryptocurrency. 

**iii)** The Hedera codebase will be governed by the council, and will be released for public review with Version 1.0. It will not be open source, but anyone will be able to read the source code, recompile it, and verify that it is correct. No license will be required to use the Hedera platform. No license will be required to write software that uses the services of the Hedera platform. No license will be required to build smart contracts on top of the Hedera platform. Applications built upon the Hedera platform can be open source or proprietary. They do not require any license or any approval from Hedera. Hedera will simultaneously embrace open review, while bringing stability by using the patents defensively. In this way, Hedera will provide a transparent codebase that will provide the stability that markets demand for mainstream adoption of a public ledger. 

The combination of technical and legal controls provide the governing body with the mechanisms needed to enable meaningful governance, and to bring the stability that we think is required for broad-based adoption. 

5. **REGULATORY COMPLIANCE** – The Hedera technical framework includes an Opt-In Escrow Identity mechanism that gives users a choice to bind verified identities to otherwise anonymous cryptocurrency accounts, which will in our opinion provide governments with the oversight necessary to ensure regulatory compliance. This is completely optional, and each user can decide what kinds of credentials, if any, to reveal. We intend to work with governments to provide the same level of protection to distributed public ledgers as is currently present in the financial system. 

> (2) Swirlds, Inc. (Swirlds) is a Delaware corporation that is the owner and licensor of the hashgraph consensus algorithm. Swirlds is currently the sole member of Hedera Hashgraph, LLC, the expected legal entity for the Hedera Hashgraph Council. Prior to launch of the Hedera Hashgraph public ledger and the establishment of the Hedera Hashgraph Council, Swirlds will retain control of governance and network development, and Swirlds will be a permanent member of the Hedera Hashgraph Council.  

> (3) See Appendix 3 for a full definition of the hashgraph algorithm, including proofs of ABFT. Furthermore, see https://hedera.com/platform#security for the formalized ABFT proof.  

# Part 1 An introduction to Hedera Hashgraph 
The hashgraph data structure and consensus algorithm provides a new platform for distributed consensus. This introduction gives an overview how hashgraph works, and of some of its properties. 
The goal of a distributed consensus algorithm is to allow a community of users to come to an agreement on the order in which some of
them generated *transactions*, when no single member is trusted
by everyone. In this way, it is a system for generating trust, when individuals do not already trust each other. Hashgraph achieves this in a fundamentally new way. 

<p align="center">
  <img src="https://github.com/ilyakmet/hashgraphWiki/blob/master/img/2.jpg" width="620" height="438px">
</p>

A blockchain is like a tree that is continuously pruned as it grows - this pruning is necessary to keep the branches from growing out of control. In hashgraph, rather than pruning new growth, it is woven back into the body. 

In both blockchain and hashgraph, any member can create a transaction, which will eventually be put into a container (the “block”), and will then spread throughout the community. In blockchain, those containers are intended to form a single, long chain. If two miners create two blocks at the same time, the community will eventually choose one to continue, and discard the other one. It’s like a growing tree that is constantly having all but one of its branches chopped off. 

In hashgraph, every container is used, and none are discarded. All the branches continue to exist forever, and eventually grow back together into a single whole. This is more efficient. 

Furthermore, blockchain fails if the new containers arrive too quickly, because new branches sprout faster than they can be pruned. That
is why blockchain needs proof-of-work or some other mechanism to artificially slow down the growth. In hashgraph, nothing is thrown away. There is no harm in the structure growing quickly. Every member can create transactions and containers whenever they want. So it is very simple, and tends to be very fast. 

Finally, because the hashgraph doesn’t require pruning and therefore is simpler, it allows more powerful mathematical guarantees, such
as *Byzantine agreement*and *fairness*. Distributed databases such as Paxos are Byzantine, but not fair. Blockchain is neither Byzantine nor fair. Hashgraph is both Byzantine and fair. 

The hashgraph algorithm accomplishes being *fair, fast, Byzantine, ACID compliant, efficient, inexpensive, timestamped, and DoS resistant.*

## Performance 
**COST**
The hashgraph is inexpensive, in the sense of avoiding proof-of-work. Individuals and organizations running hashgraph nodes do not need to purchase expensive custom mining rigs. Instead, they can run readily available, cost-effective hardware. The hashgraph is 100% efficient, wasting no resources on computations that slow it down. 

**EFFICIENCY**
The hashgraph is 100% efficient, as that term is used in the blockchain community. In blockchain, work is sometimes wasted mining a block that later is considered stale and is discarded by the community.
In hashgraph, the equivalent of a “block” never becomes stale. Hashgraph is also efficient in its use of bandwidth. Whatever is the amount of bandwidth required *merely*to inform all the nodes of a given transaction (even without achieving consensus on a timestamp for that transaction), hashgraph adds only a very small overhead beyond that absolute minimum. Additionally, hashgraph’s voting algorithm does not require any additional messages be sent in order for nodes to vote (or those votes to be counted) beyond those messages by which the community learned of the transaction itself. 

**THROUGHPUT**
The hashgraph is *fast*. It is limited only by the bandwidth. If each member has enough bandwidth to download and upload a given number of transactions per second, the system as a whole can handle close to that many. Even a fast home internet connection could be fast enough to handle all of the transactions of the entire VISA card network, worldwide. 

THE FOLLOWING CHARTS GIVE REPRESENTATIVE PERFOMANCE RESULTS FOR THE HASHGRAPH.

<br>
<p align="center">
  <img src="https://github.com/ilyakmet/hashgraphWiki/blob/master/img/3.jpg" width="310px” height=“353px">
  <img src="https://github.com/ilyakmet/hashgraphWiki/blob/master/img/4.jpg" width="310px” height=“353px">
  <img src="https://github.com/ilyakmet/hashgraphWiki/blob/master/img/5.jpg" width="310px” height=“353px">
</p>
<br>

These tests were performed using Amazon AWS m4.4xlarge instances. The top-most figure was for a single region: Virginia. The middle was for two regions: Virginia and Oregon, on opposite sides of the continental United States, over 2,000 miles apart. The bottom-most figure was for 8 regions: Virginia, Oregon, Canada, Sao Paulo, Australia, Seoul, Tokyo, and Frankfurt. 
Each curve is for a different number of instances (computers) - this shown to the right of the curve. In every case, the instances were distributed evenly across the number of regions being used. 
The horizontal axis is the number of 100-byte transactions per second for which the ledger achieved consensus. In these experiments, this throughput ranges from less than 50,000 tps up to almost 500,000 tps. On most of the lines, the second dot from the left is 10,000 tps. 
The vertical axis is the average number of seconds from when a node first creates a transaction until it knows the exact consensus order and consensus timestamp for it. This isn’t just a time to a first confirmation. It is the time until a 100% certain finality is reached. 
In all of the experiments, this latency was under 11 seconds. And various experiments had latencies down to less than 0.04 seconds. 
In the graphs, there are clear tradeoffs between throughput, latency, number of computers, and geographic distribution. For 32 computers running at 50,000 transactions per second, consensus finality is reached in 3 seconds when the network is spread across 8 regions spanning the globe. When the network stretches only 2,000 miles across the US, this drops to 1.5 seconds. In a single region, it drops to 0.75 seconds. 
If it is desired to keep the latency under the 7 seconds required by credit cards, while still achieving 200,000 transactions per second, it is possible to use 32 computers in eight regions, or use 64 computers in two regions, or use 128 computers in one region. 
It is important to note that these tests are purely for achieving consensus on transaction order and timestamps. They do not include the time to process transactions. For example, if every transaction is digitally signed, then these results suggest that a great deal of processing power might be needed to verify hundreds of thousands of digital signatures per second. It is possible that GPU implementations could be helpful. 
In addition, if a transaction is of the form “store this gigabyte file”, then bandwidth limitations would greatly slow down the system. 

**STATE EFFICIENCY**
Once an event occurs, within seconds everyone in the community will know where it should be placed in history with 100% certainty. More importantly, everyone will know that everyone else knows this. At that point, they can just incorporate the *effects*of the transaction and, unless needed for future audit or compliance, then discard it. So in a minimal cryptocurrency system, each member would only need to store the current balance of each account that isn’t empty. They wouldn’t need to remember the full history of the transactions that resulted in those balances all the way back to ‘genesis’. 

## Security 
**CRYPTOGRAPHY**
All communications are encrypted with TLS 1.2, all events are digitally signed, and the hashgraph is constructed using cryptographic hashes. All the algorithms and key sizes were chosen to be compliant with the CNSA Suite security standard. This is the standard required for protecting US government Top Secret information. It specifies using AES-256, RSA 3072, SHA-384, and ECDSA and ECDH with p-384 and using ephemeral keys for perfect forward secrecy. 

**ASYNCHRONOUS BYZANTINE FAULT TOLERANCE**
The hashgraph is asynchronous Byzantine Fault Tolerant. This is a technical term meaning that no single member (or small group of members) can prevent the community from reaching a consensus. Nor can they change the consensus once it has been reached. Each member will eventually reach a point where they know for sure that they have reached consensus. Blockchain does not have a guarantee of Byzantine agreement, because a member never reaches certainty that agreement has been achieved (there’s just a probability that rises over time). Blockchain is also non-Byzantine because it doesn’t automatically deal with network partitions. If a group of miners is isolated from the rest of the internet, that can allow multiple chains to grow, which conflict with each other on the order of transactions. 

It is worth noting that the term “Byzantine Fault Tolerant” (BFT) is sometimes used in a weaker sense by other consensus algorithms. But here, it is used in its original, stronger sense that (1) every member eventually knows consensus has been reached, (2) attackers may collude, and (3) attackers even control the internet itself (with some limits). Hashgraph is Byzantine, even by this stronger definition. 

There are different degrees of BFT, depending on the assumptions made about the network and transmission of messages. 

The strongest form of BFT is asynchronous BFT - meaning that it can achieve consensus even if malicious actors are able to control the network and delete or slow down messages of their choosing. The only assumptions made are that more than 2⁄3 are following the protocol correctly, and that if messages are repeatedly sent from one node to another over the internet, eventually one will get through, and then eventually another will, and so on. Some systems are partially asynchronous, which are secure only if the attackers do not have too much power and do not manipulate the timing of messages too much. For instance, a partially asynchronous system could prove Byzantine under the assumption that messages get passed over the internet in ten seconds. This assumption ignores the reality of botnets, Distributed Denial of Service attacks, and malicious firewalls. 

A full technical report describing the hashgraph data structure and algorithm, including mathematical proofs that Hashgraph is asynchronous BFT, is included in the Appendix. 

**ACID COMPLIANCE**
The hashgraph is ACID compliant. ACID (Atomicity, Consistency, Isolation, Durability) is a database term, and applies to the hashgraph when it is used as a distributed database. A community of nodes uses it to reach a consensus on the order in which transactions occurred. After reaching consensus, each node feeds those transactions to that node’s local copy of the database, sending in each one in the consensus order. If the local database has all the standard properties of a database (ACID), then the community as a whole can be said to have a single, distributed database with those same properties. In blockchain, there is never a moment when you know that consensus has been reached, so it would not be ACID compliant. 

**DISTRIBUTED DENIAL OF SERVICE ATTACK RESILIENCE**
One form of Denial of Service (DoS) attack occurs when an attacker is able to flood an honest node on a network with meaningless messages, preventing that node from performing other (valid) duties and roles. A Distributed Denial of Service (DDoS) uses public services or devices to unwittingly amplify that DoS attack - making them an even greater threat. 

In a DLT, a DDoS attack could target the nodes that contribute to the definition of consensus and, potentially, prevent that consensus from being established. 

The hashgraph is DDoS resilient as it empowers no single node or small number of nodes with special rights or responsibilities in establishing consensus. Both Bitcoin and hashgraph are distributed in a way that resists DDoS attacks. An attacker might flood one member or miner with packets, to temporarily disconnect them from the internet. But the community as a whole will continue to operate normally. An attack on the system as a whole would require flooding a large fraction of the members with packets, which is more difficult. There have been a number of proposed alternatives to blockchain based on leaders or round robin. These have been proposed to avoid the proof-of-work costs of Bitcoin. But they have the drawback of being sensitive to DDoS attacks. If the attacker attacks the current leader, and switches to attacking the new leader as soon as one is chosen, then the attacker can freeze the entire system while still attacking only one computer at a time. Hashgraph avoids this problem, while still not needing proof-of-work. 

## Fairness 
Hashgraph is fair because there is no leader or miner given special permissions for determining the consensus timestamp assigned to a transaction. Instead, the consensus timestamp for transactions are calculated via a voting process in which the nodes collectively and democratically establish the consensus. We can distinguish between three aspects of fairness. 

**FAIR ACCESS**
Hashgraph is fundamentally fair because no individual can stop a transaction from entering the system, or even delay it very much. If one (or few) malicious node attempts to prevent a given transaction from being delivered to the rest of the community and so be added into consensus, then the random nature of the gossip protocol will ensure that the transaction flows around that blockage. 

**FAIR TIMESTAMPS**
Hashgraph gives each transaction a consensus timestamp that reflects when the majority of the network members received that transaction. This consensus timestamp is “fair”, because it is not possible for a malicious node to corrupt it and make it differ by very much from that time.
Every transaction is assigned a consensus time, which is the median of the times at which each member says it first received it. Received here refers to the time that a given node was first passed the transaction from another node through gossip. This is part of the consensus, and so has all the guarantees of being Byzantine. If more than 2⁄3 of participating members are honest and have reliable clocks on their computer, then the timestamp itself will be honest and reliable, because it is generated by an honest and reliable member or falls between two times that were generated by honest and reliable members. Because hashgraph takes the median of all these times, the consensus timestamp is robust. Even if a few of the clocks are a bit off, or even if a few of the nodes maliciously give times that are far off, the consensus timestamp is not significantly impacted. 

This consensus timestamping is useful for things such as a legal obligation to perform some action by a particular time. There will be a consensus on whether an event happened by a deadline, and the timestamp is resistant to manipulation by an attacker. In blockchain, each block contains a timestamp, but it reflects only a single clock: the one on the computer of the miner who mined that block. 

**FAIR TRANSACTION ORDER**
Transactions are put into order according to their timestamps. Because the timestamps assigned to individual transactions are fair, so is the resulting order. This is critically important for some use cases. For example, imagine a stock market, where Alice and Bob both try to buy the last available share of a stock at the same moment for the same price. In blockchain, a miner might put both of those transactions in a single block, and have complete freedom to choose what order they occur. Or the miner might choose to only include Alice’s transaction, and delay Bob’s to a future block. In hashgraph, there is no way for an individual to unduly affect the consensus order of those transactions. The best Alice can do is to invest in a better internet connection so that her transaction reaches everyone before Bob’s. That’s the fair way to compete. 

## Governance 
A governance model for a public ledger will define the rules and policies that control the evolution of the node software, issuance of coins, and the reward model by which participants are incentivized. The stakeholders whose interests and motivations must be balanced are those running the consensus nodes, those building applications on the platform, those businesses relying on those applications, the end-users of those applications, and relevant regulatory bodies. 

Hedera Hashgraph Council is a for-profit LLC that will be governed by up to 39 renowned enterprises and organizations, across multiple industries and geographies. Its vision is a cyberspace that is trusted, secure, and without the need for central servers. Its licensing and governance model protects the community by eliminating the risk of splitting, guaranteeing the integrity of the codebase, and providing open access to the protected core. Under the governance model, all Governing Members will have equal governing rights and each Governing Member (with the exception of Swirlds) is expected to serve a limited term, ensuring that no single Governing Member or group of Governing Members has centralized control. The Hedera Hashgraph Council guarantees the wide, equitable distribution of the hash cryptocurrency, and that nodes in the network are being fully utilized. 

Hedera has a Permissioned Governance Model with Permissionless or Open Consensus. 

The _Governance Model_ concerns the election of the Governing Board and placement of representatives on subcommittees. The Governing Members are responsible for electing the Board of Managers of Hedera.
The board establishes policy for council membership, regulates the network rules and tokens, and approves changes to the platform codebase. Our governance model is based on the original model used by National BankAmericard Inc., founded in 1968, which was later renamed VISA. We are designing our governance model in a way that ensures the Governing Members can be trusted to do what’s in the best interest of Hedera, and not be unduly influenced by individual council members or node operators. In addition to Governing Members, Hedera will have a set of Advisory Members that contribute by providing advisory services as appropriate, but do not have voting privileges. 

The Open _Consensus model_ relates to the process by which the nodes join the network and reach a consensus on the order of transactions in the platform. The model is designed to prevent consolidation of power over consensus by encouraging the emergence of a decentralized network with, eventually, millions of nodes. It prevents collusion by a few to attack the system such as by counterfeiting the cryptocurrency, modifying the ledger inappropriately, or influencing the consensus order of transactions. We inhibit collusion by weighting the votes within the hashgraph algorithm of a particular node based on the node’s stake. Loosely stated, each node casts one vote for each coin of Hedera currency itowns. New node operators will join the network, and be paid for their services in maintaining the hashgraph. The number of nodes is expected to grow 
large very quickly, ensuring consensus voting privileges are distributed to many thousands of nodes. A full discussion of the staking model is included in the section below. 

This system of Permissioned Governance with Open Consensus will build more public trust than a purely closed system. This is essential to the success of a global cryptocurrency. 

**PERMISSIONED GOVERNANCE**
We designed the Hedera governance model to ensure that the organization can be trusted. The founding Governing Members will elect a Governing Board, and will decide if and when to expand the membership. As noted, Governing Members will have equal governing rights and limited terms, ensuring that governance is decentralized. Deliberation and debate will be open to all and controlled by none. 

The Governing Members will also elect or appoint members to subcommittees that provide oversight of Hedera operations. The subcommittees will include but are not limited to the Technical Steering Committee, the Finance Committee, Joint Marketing and PR, and the Legal / Regulatory Oversight committee. The Governing Members are organizations that span a broad range of business sectors, and our objective is that, collectively, the membership will contribute industry-leading representation to the range of Hedera subcommittees. 
Governing Members receive fees from operating nodes on Hedera. Node operators that are not Governing Members can also receive fees for their contribution to the network, but non-members do not receive council governance votes. 

The Governing Board will appoint a Chief Executive Officer of Hedera, who will be a member of the Governing Board by right of that appointment, but cannot hold the chairmanship of the Governing Board. The Chairman will be elected by the Governing Board, but will have no executive or operating authority. The President will be responsible for preparing the agenda for the board meetings. Any matter can be put on the agenda by any member of the Governing Board. 

## Stability 
The hard forks that Bitcoin and Ethereum have experienced have arguably damaged the network effect of their corresponding currencies, creating confusion and uncertainty in the marketplace. Similarly,
the explosion of altcoins (and the dubious legitimacy and value of many of them) does not engender the necessary confidence in businesses and consumers considering adopting cryptocurrencies. 

Historically, open source software developers have recognized the value of maintaining a single baseline, and ensuring that the best ideas from the community are included for the benefit of the whole. However, when combining an open source project with a cryptocurrency, the traditional incentive structure is turned upside down. The distributed ledger technologies that have been most widely adopted are also those that have split the most. This dynamic causes chaos in the industry, and directly impedes the adoption of public ledgers by mainstream markets. 

**Hedera technical and legal controls** ensure the platform will not fork into a competing platform and cryptocurrency. 

## Technical controls 
There is a shared state that is maintained by every node in the ledger (or in the shard, when the ledger is sharded). At the end of each round, each node calculates the shared state after processing all transactions that were received in that round and before. It then digitally signs a hash of that shared state, puts it in a transaction, and gossips it out to the community. Then it collects those signatures from all other nodes. 

In this way, a node can have a copy of the state with a set of signatures that proves to a third party that this is the true, consensus state. This allows the node to construct a small file which is a verifiable proof that the state was truly the consensus. 

The state is organized as a Merkle tree, so a third party can be given a proof that consists of a small part of the state, plus the path from there to the root of the Merkle tree (including siblings of those vertices in the tree), plus the signatures, and an address book history for the public keys. 

The diagram below represents how a third party can be confident that the state it receives from one of the nodes does indeed represent the consensus state of the full network. 

<br>
<p align="center">
  <img src="https://github.com/ilyakmet/hashgraphWiki/blob/master/img/6.jpg" width="620" height=“322px">
</p>
<br>

**LEDGER ID**
The proof must also include an “address book”, which is list of the public keys of all the members, along with each member’s stake (owned directly or by proxy). A third party will need this address book in order to check the signatures on the state (or portion of state). 

The proof must also include an “address book history”. This is a sequence of address books, where each address book is signed by members from the previous address book. Any given address book must be signed by a set of members that own more than 2/3 of the stake, according to the membership and stake from the previous address book. This chain of address books extends back to the genesis address book, which is the initial members who created the ledger at the beginning. 

The hash of the genesis address book is important. It serves as a unique identifier of the ledger. It is the “name” of the ledger. 

**HANDLING FORKS**
If a small number of members want to split off from the group and create a new ledger that is a fork of the current one, they have the technical ability to do so, and can even create the initial state of their new ledger to be identical to the old ledger. So it is a fork. However, they will not be able to create an address book history reaching back to the genesis address book, with the members of each address book signing the next one, because the majority of members (who are not forking) will not sign the address book for the minority of members who are forking. This forces the new fork to have a new genesis address book, and therefore a new unique identifier, and therefore a new name. Consequently, those creating the fork will be unable to fool anybody into thinking the fork is the legitimate ledger. 

When a client submits a transaction to a node to send to the ledger, the client receives in response from the node the cryptographic proof that their transaction has affected the shared state correctly. When Alice transfers cryptocurrency to Bob, both of them can receive a cryptographic proof that the transaction succeeded. This proof includes the signatures reaching back to the genesis address book. So they not only verify that the transfer occurred, they verify that it occurred on the correct ledger. If a ledger forks, no client will ever be confused about which ledger they are dealing with because only one ledger at a time can have that name. 

Furthermore, if a 50/50 split were to happen, then neither side would be able to prove a connection to the genesis address book. It wouldn’t be a fork; it would be the complete destruction of one ledger, and the creation of two unrelated ledgers. This would greatly reduce the value to the nodes, because they would no longer be able to earn fees from the clients who want to access the original ledger. And all of the original cryptocurrency would, in a very real sense, cease to exist. This creates an enormous disincentive to forking. 

In this way, confusing forks simply become impossible. Non-confusing forks become unappealing for the nodes. So there are strong incentives to avoid forks, even aside from any legal incentives. 

The cryptographic proofs and unique identifiers are also critically important for secure sharding. They allow shards to send each other messages, with assurance that the message from a given shard was truly the consensus of that shard. 

## Legal Controls and Transparency 
The Hedera codebase will be governed by the Hedera Hashgraph Council, and will be released for public review with Version 1.0. The codebase will be open review, meaning that anyone will be able to read the source code, recompile it, and verify that it is correct. 

No license will be required to use the Hedera platform. No license will be required to write software that uses the services of the Hedera platform. No license will be required to build smart contracts on top of the Hedera platform. Applications built upon the Hedera platform can be open source or proprietary. They do not require any license or any approval from Hedera. Software developed using the platform APIs will not be encumbered in any way. Software developers will have complete ownership and discretion on the licensing they choose for their applications that use the Hedera platform. 

Swirlds owns the intellectual property rights in the hashgraph consensus algorithm. Hedera Hashgraph Council has a license from Swirlds to use the hashgraph consensus algorithm and associated technology for the Hedera distributed public ledger platform. As part of that license, Hedera Hashgraph Council will pay Swirlds 10% of revenue (with monthly minimums) and Swirlds will own 5% of Hedera coins. Swirlds will continue to require licenses for use of the hashgraph technology in permissioned networks, but no license will be required for distributed applications that run on Hedera’s public platform. Hedera and Swirlds will use the patent rights associated with the hashgraph algorithm defensively to legally prohibit the forking of the codebase and the creation of a competing platform and currency. Developers are free to build distributed applications on top of the Hedera platform with associated native tokens. 

In summary, Hedera will simultaneously embrace open review, while bringing stability to the platform and cryptocurrency by controlling the license. In this way, Hedera will provide a transparent codebase that will provide the stability that markets demand for mainstream adoption. 

## Regulatory Compliance 
We expect that governments will soon require comparable visibility and oversight into public ledger financial transactions that they have now for traditional banking. In our view, for a public ledger to be adopted widely, it must be capable of enabling appropriate Know Your Customer (KYC) and Anti Money Laundering (AML) checks. 

Hedera will enable KYC and AML through an Opt-In Escrowed Identity system. 

The Escrowed Identity system allows a user’s real identity (as asserted by an accredited party acting as a Certificate Authority) to be logically bound to their ledger account so that, when using that account to move funds, appropriate KYC checks can be performed and AML protections enforced. The identity is escrowed because only on defined criteria or schedule need the government be informed. 

The system is Opt-In - a user must explicitly choose to avail themselves of the mechanism and, if they do not, their account transactions will remain anonymous. This choice however may prevent them from engaging in certain financial transactions. 

The system is designed to provide the appropriate balance of :

1. Government visibility 
2. Security 
3. User privacy 

Comparable to showing a driver’s license when creating a new bank account, the model has a user attach a hash of a digital certificate created by a recognized identity provider to their account. This attachment will take the form of a transaction sent out to the network. This transaction :

1. May need to be signed by both the user’s private key and that of the identity provider.
2. Can stipulate what parties are authorized to subsequently detach the hash (and so revoke 
the binding between the identity and the account). 

As long as the attachment between account and certificate has not been revoked, by either the user or the identity provider, it can be used to establish that the account is bound to a known user whenever funds move in or out of that account. If and when appropriate, the identity provider can revoke the binding simply by sending a signed transaction to the network. 

As an example of how it might work, consider a user trying to send money from their Hedera account
to a US bank. The user would provide to the bank the certificate as well as their account address. The bank would look up the account and confirm that the account had the corresponding hash for the certificate, and that the certificate was issued by a trusted identity provider. Only if all these checks were confirmed would the bank authorize the transaction and accept the funds.The bank might be asked by the corresponding government to send the certificate and transaction details, either in real-time (perhaps based on the amount of the transfer) or on a schedule. 

Critically for privacy, the user can revoke the binding at any time as well - removing the binding between their identity and the account. Doing so might prevent them from using that account in certain situations but that would be their choice. 

Hedera is a founding member of the Distributed Ledger Foundation and will work with the broader DLT community and governments there to ensure that regulatory requirements can be satisfied, while maintaining privacy and security. 

## Conclusion 
Hedera directly resolves the five fundamental obstacles to mainstream market adoption of public ledger technology: Performance, Security, Stability, Governance, and Regulatory Compliance.
The hashgraph data structure and consensus algorithm provides a best-in-class, unmatched combination of performance and security. The Hedera platform and governance council will provide transparency, open innovation with platform stability, tools to enable opt-in KYC and AML, and global, cross-industry expertise to provide governance and decision making for a globally distributed network and cryptocurrency. 