EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:

ARTICLE 

The Basics of Blockchain Technology

Blockchain technology has emerged as one of the most transformative innovations in the digital era. Initially introduced as the underlying technology behind cryptocurrencies like Bitcoin, blockchain has since expanded its applications across multiple industries including finance, healthcare, supply chain management, and governance. At its core, blockchain is a decentralized and distributed digital ledger that records transactions in a secure, transparent, and immutable manner.

A blockchain consists of a chain of blocks, where each block contains a list of transactions. These blocks are connected using cryptographic techniques. Every block includes three main components: the transaction data, a timestamp, and a cryptographic hash of the previous block. The hash functions as a unique identifier, linking blocks together and ensuring that the data cannot be altered without affecting the entire chain. This structure makes blockchain highly secure and resistant to tampering.

One of the defining characteristics of blockchain technology is decentralization. Traditional databases are usually controlled by a central authority such as a bank, government, or organization. In contrast, a blockchain is maintained by a distributed network of computers known as nodes. Each node holds a copy of the entire blockchain ledger. When a new transaction occurs, it is broadcast to all nodes in the network for verification. Once the majority of nodes validate the transaction through a consensus mechanism, it is added to a new block and appended to the chain.

Consensus mechanisms play a crucial role in maintaining the integrity of blockchain networks. These mechanisms ensure that all participants agree on the validity of transactions before they are recorded. Popular consensus methods include Proof of Work (PoW) and Proof of Stake (PoS). In Proof of Work, miners compete to solve complex mathematical problems to validate transactions and add new blocks to the chain. In Proof of Stake, validators are selected based on the amount of cryptocurrency they hold and are willing to “stake” as collateral. These mechanisms help prevent fraudulent activities such as double-spending.

Another important feature of blockchain is transparency. Since the ledger is distributed across multiple nodes, every participant in the network can access and verify the transactions recorded on the blockchain. This transparency increases trust among users, as no single entity has exclusive control over the data. At the same time, blockchain also maintains privacy by using cryptographic techniques that allow users to interact through digital addresses instead of revealing personal information.

Blockchain technology also enables the use of smart contracts. Smart contracts are self-executing programs stored on the blockchain that automatically enforce the terms of an agreement when predefined conditions are met. For example, in a supply chain system, a smart contract could automatically release payment to a supplier once goods are delivered and verified. This automation reduces the need for intermediaries, lowers transaction costs, and increases efficiency.

Despite its advantages, blockchain technology faces certain challenges. Issues such as scalability, energy consumption, regulatory uncertainty, and integration with existing systems still need to be addressed. For instance, some blockchain networks require significant computational power, leading to high energy usage. Researchers and developers are actively working on solutions such as energy-efficient consensus mechanisms and improved network architectures.

In conclusion, blockchain technology provides a secure, transparent, and decentralized method for recording and verifying transactions. Its ability to eliminate intermediaries, enhance data security, and build trust among participants makes it a powerful tool for digital transformation. As the technology continues to evolve, blockchain is expected to play a significant role in shaping the future of global digital systems.


Zero shot Prompt :

Summarize the following article about Blockchain Technology in 120–150 words for undergraduate students. 
Focus on the key concepts and keep the explanation simple.

[Paste article here]

SUMMARY :

ChatGPT

Blockchain technology is a decentralized digital ledger that records transactions securely and transparently. It was first introduced as the technology behind cryptocurrencies like Bitcoin, but it is now used in many fields such as finance, healthcare, and supply chain management. A blockchain is made up of blocks that store transaction data, timestamps, and a cryptographic hash linking each block to the previous one. This structure makes the data highly secure and difficult to alter.

Unlike traditional systems controlled by a central authority, blockchain is maintained by a network of computers called nodes. Transactions are verified through consensus mechanisms such as Proof of Work (PoW) or Proof of Stake (PoS) before being added to the chain. Blockchain also supports smart contracts, which automatically execute agreements when conditions are met. Although it offers benefits like transparency and security, challenges such as scalability and energy consumption still need improvement.

Gemini

Understanding Blockchain Technology

Blockchain is a decentralized digital ledger that records transactions across a network of computers. Unlike traditional databases managed by central authorities like banks, blockchain uses a distributed network of "nodes" to verify and store data.

The technology relies on three core pillars:
     Security: Each "block" contains data and a unique cryptographic hash of the previous block. This creates an unbreakable chain where altering one entry would require changing the entire history.
    Consensus: To ensure validity, the network uses mechanisms like Proof of Work or Proof of Stake, requiring nodes to agree before any new data is added.
    Transparency: All participants can view the ledger, fostering trust without needing intermediaries.
    
Beyond currency, blockchain enables smart contracts—automated programs that execute agreements when specific conditions are met. While challenges like high energy consumption exist, its ability to provide secure, tamper-proof records is transforming global digital systems

Claude

Blockchain Technology: A Simple Summary

Blockchain is a digital record-keeping system that stores transactions securely across a network of computers, rather than in one central location. Think of it as a shared notebook that thousands of people hold simultaneously — no single person controls it, and no entry can be erased.

Each "block" holds transaction data, a timestamp, and a unique code linking it to the previous block, forming a tamper-proof chain. Before any transaction is added, the network's computers must collectively agree it's valid — a process called a consensus mechanism.

Key features include transparency (anyone in the network can verify records), security (cryptographic techniques protect data), and smart contracts (self-running programs that execute agreements automatically without middlemen).

Originally powering cryptocurrencies like Bitcoin, blockchain now serves finance, healthcare, and supply chains. Challenges like energy use and scalability remain, but its potential to build trust in digital systems is enormous

<img width="648" height="248" alt="image" src="https://github.com/user-attachments/assets/be46b761-a624-4c1a-a1cc-151ed358d91b" />

Few Shot Prompt :

Example:

Article: Artificial Intelligence is a technology that enables machines to learn from data and perform tasks such as recognition and decision-making.

Summary: Artificial Intelligence allows computers to learn patterns from data and perform tasks like identifying images or making decisions without being explicitly programmed.

Now summarize the following article in a similar style for undergraduate students in 120–150 words.

[Paste blockchain article]

SUMMARY :

ChatGPT

Blockchain technology is a decentralized digital system used to record transactions securely and transparently. It was first introduced as the technology behind cryptocurrencies such as Bitcoin, but today it is used in many fields including finance, healthcare, and supply chain management. A blockchain stores data in blocks that are linked together using cryptographic hashes, forming a secure chain that prevents data from being easily altered. Unlike traditional databases controlled by a central authority, blockchain is maintained by a network of computers called nodes. These nodes verify transactions using consensus mechanisms like Proof of Work and Proof of Stake before adding them to the blockchain. The technology also supports smart contracts, which automatically execute agreements when certain conditions are met. Although blockchain offers advantages such as security, transparency, and reduced intermediaries, it still faces challenges like scalability, energy consumption, and regulatory concerns.


Gemini

Understanding Blockchain Technology

Blockchain is a decentralized digital ledger that records transactions across a network of computers, rather than relying on a central authority like a bank. Each "block" in the chain contains data linked by unique cryptographic hashes; if one block is altered, the entire chain breaks, making the system highly secure and tamper-proof.

To maintain integrity, the network uses consensus mechanisms—such as Proof of Work—where participants must agree on a transaction's validity before it is recorded. This process ensures transparency, as every user can verify the ledger. Beyond simple data storage, blockchain supports smart contracts, which are self-executing agreements that automate tasks like payments. While challenges such as high energy consumption and scalability remain, blockchain’s ability to remove intermediaries and build digital trust makes it a foundational tool for the future of global finance, healthcare, and governance.

Claude

Blockchain Technology: Summary

Blockchain is a digital record-keeping system that stores transaction data across a network of computers, rather than in one central location — much like a shared notebook that thousands of people hold simultaneously, where no entry can ever be erased or altered.
Each "block" stores transaction data, a timestamp, and a unique code linking it to the previous block, forming a tamper-proof chain. Before any transaction is recorded, a network of computers must collectively verify it through a process called a consensus mechanism — methods like Proof of Work or Proof of Stake prevent fraud and double-spending.

Key features include transparency (all participants can verify records), privacy (users interact via digital addresses), and smart contracts (self-running programs that automate agreements without middlemen).
Originally powering Bitcoin, blockchain now serves finance, healthcare, and supply chains. Challenges like energy consumption and scalability remain, but its potential to build trust in digital systems continues to grow.

<img width="647" height="249" alt="image" src="https://github.com/user-attachments/assets/4102d52e-2753-4b77-825c-d44cc28429b1" />

Chain of thought Prompt :

Read the following article about Blockchain Technology.

Step 1: Identify the main concepts.
Step 2: Identify supporting ideas.
Step 3: Create a simple explanation suitable for undergraduate students.
Step 4: Write a final summary in 120–150 words.

Article:
[Paste article]

ChatGPT

Step 1: Main Concepts
Blockchain Technology – A decentralized digital ledger used to record transactions securely.
Blocks and Cryptographic Hashing – Data is stored in blocks linked together using cryptography.
Decentralization and Nodes – The network is maintained by multiple computers instead of a central authority.
Consensus Mechanisms – Methods like Proof of Work (PoW) and Proof of Stake (PoS) used to validate transactions.
Transparency and Security – Transactions are visible and tamper-resistant.
Smart Contracts – Automated programs that execute agreements when conditions are met.
Challenges – Issues like scalability, energy consumption, and regulation.

Step 2: Supporting Ideas
Each block contains transaction data, a timestamp, and a hash of the previous block.
Nodes verify transactions before adding them to the blockchain.
Consensus mechanisms ensure agreement among network participants.
Cryptography protects user identity through digital addresses.
Smart contracts reduce intermediaries and improve efficiency.
Blockchain is used in industries like finance, healthcare, and supply chains.

Step 3: Simple Explanation for Undergraduate Students
Blockchain is a digital system used to store transaction records securely across many computers instead of one central database. Information is stored in blocks that are linked together using cryptography, forming a chain. When a transaction occurs, network participants verify it through a consensus process before it is added to the blockchain. This system ensures that records cannot easily be changed or tampered with. Blockchain also allows automated agreements called smart contracts. Although it offers transparency and security, challenges such as high energy use and scalability still exist.

Step 4: Final Summary (120–150 words)
Blockchain technology is a decentralized digital ledger used to securely record and verify transactions across a network of computers. Instead of relying on a central authority, blockchain distributes data among many nodes, each holding a copy of the ledger. Transactions are stored in blocks that contain data, timestamps, and cryptographic hashes linking them to previous blocks, ensuring data integrity and preventing tampering. Before a transaction is added to the blockchain, it must be validated through consensus mechanisms such as Proof of Work or Proof of Stake. Blockchain also supports smart contracts, which automatically execute agreements when specific conditions are met, reducing the need for intermediaries. This technology improves transparency, security, and trust in digital systems. However, challenges like scalability, energy consumption, and regulatory issues remain. Despite these limitations, blockchain has significant potential to transform industries such as finance, healthcare, and supply chain management.

Gemini

Step 1: Main Concepts
Definition: A decentralized, distributed digital ledger.
Structure: A chain of blocks linked by cryptographic hashes.
Mechanism: Verification through network nodes and consensus.
Utility: Applications like smart contracts and secure data management.

Step 2: Supporting Ideas
Immutability: Data cannot be changed once a block is added without breaking the chain.
Consensus Models: Methods like Proof of Work (PoW) and Proof of Stake (PoS) prevent fraud.
Transparency vs. Privacy: Publicly verifiable records combined with cryptographic anonymity.
Current Challenges: Scalability and high energy consumption.

Step 3: Simple Explanation
Imagine a shared Google Doc that everyone can see, but no one can delete or edit previous entries. Instead of one "boss" (like a bank) owning the document, thousands of computers (nodes) across the world keep a copy. To add a new page (block), the computers must agree the information is true. Once added, the page is "glued" to the previous one with a digital seal (hash). This makes the record permanent and trustworthy without needing a middleman.

Step 4: Final Summary (138 words)
Blockchain technology is a decentralized digital ledger that records data across a vast network of computers, eliminating the need for central authorities like banks. Each "block" contains transaction data and a unique cryptographic hash that links it to the previous one, creating an immutable chain where information cannot be tampered with. For a new transaction to be added, a majority of network nodes must reach an agreement using consensus mechanisms like Proof of Work.

Beyond security, blockchain offers transparency by allowing all participants to verify records while maintaining privacy through encryption. It also enables smart contracts, which are self-executing programs that automate agreements. Although the technology faces hurdles like high energy usage and scalability, its ability to provide secure, transparent, and intermediary-free transactions makes it a cornerstone of modern digital transformation across various global industries.

Claude

Step 1: Main Concepts
Blockchain as a decentralized digital ledger
Block structure (data, timestamp, cryptographic hash)
Decentralization via a network of nodes
Consensus mechanisms (Proof of Work & Proof of Stake)
Transparency and privacy
Smart contracts
Challenges (scalability, energy, regulation)


Step 2: Supporting Ideas
Originally built for Bitcoin; now used in finance, healthcare, supply chains, and governance
Each block links to the previous one via a hash, making tampering nearly impossible
Nodes collectively verify transactions before they are recorded
PoW uses computational puzzles; PoS uses staked cryptocurrency as collateral
Users interact through digital addresses, protecting personal identity
Smart contracts automate agreements without needing a middleman
Energy consumption and scalability are active research problems


Step 3: Simple Explanation
Think of blockchain as a digital notebook shared among thousands of people at once. Every time someone writes a new entry (transaction), everyone in the network checks and approves it before it's added. Once written, the entry can never be changed or deleted. No single person or organization is in charge — the whole network manages itself. Special automated rules called smart contracts can even carry out actions (like releasing a payment) the moment certain conditions are met.

Step 4: Final Summary (120–150 words)
Blockchain is a decentralized digital ledger that records transactions securely across a network of computers, with no single authority in control. Each "block" contains transaction data, a timestamp, and a unique code linking it to the previous block — making the chain tamper-proof and transparent.
When a transaction occurs, all computers (nodes) in the network verify it through a consensus mechanism such as Proof of Work or Proof of Stake, preventing fraud like double-spending. Every participant can view the ledger, while personal identity stays protected through digital addresses.
Smart contracts — self-executing programs on the blockchain — automate agreements without intermediaries, reducing cost and increasing efficiency. Originally powering cryptocurrencies like Bitcoin, blockchain now serves healthcare, finance, and supply chains. Despite challenges like energy consumption and scalability, it remains a powerful tool for building trust in digital systems.

<img width="647" height="246" alt="image" src="https://github.com/user-attachments/assets/709cea38-991a-41dc-94f2-fb52e6720cee" />

Role Based Prompt :

You are a university professor explaining complex technologies to first-year undergraduate students.
Summarize the following article about Blockchain Technology in a clear and simple way (120–150 words).
Avoid technical jargon and focus on the main ideas.

Article:
[Paste article]

SUMMARY :

ChatGPT

Blockchain is a digital system used to record and store information in a secure and transparent way. It was first developed to support cryptocurrencies like Bitcoin, but today it is used in many fields such as finance, healthcare, and supply chains. Instead of being controlled by a single authority, blockchain works through a network of computers that share and verify the same data.

Information is stored in blocks, and each block is linked to the previous one, forming a chain. This structure makes the data difficult to change or tamper with. When a new transaction occurs, the network checks and confirms it before adding it to the chain.

Blockchain also allows the use of smart contracts, which are programs that automatically execute agreements when certain conditions are met. Overall, blockchain improves security, transparency, and trust, although challenges like energy use and scalability still need to be solved.

Gemini

Welcome to your first lecture on modern digital architecture. To understand blockchain, think of it as a shared, digital record book that doesn't belong to any single "boss" like a bank or government. Instead, thousands of computers globally hold an identical copy.

When a new transaction occurs, the entire network must agree it is valid before it is permanently "locked" into a chain of data. Because every entry is linked to the one before it, the history is virtually impossible to change or fake. This creates digital trust without needing a middleman.

Beyond just money, this technology uses "smart contracts"—automated programs that trigger actions, like a payment, only when specific conditions are met. While it currently faces hurdles like high energy use, blockchain’s core strength lies in its ability to provide a secure, transparent, and unchangeable way to manage information in our digital world.

Claude

Professor's Summary
Imagine a digital record book shared simultaneously across thousands of computers worldwide — that's essentially what blockchain is. Unlike a bank or government that controls a single central database, blockchain has no single owner. Every computer in the network holds an identical copy, and all must agree before any new entry is added, making fraud nearly impossible.

Each record, called a "block," is permanently linked to the one before it. Altering even one entry would break the entire chain — so the data stays secure and trustworthy forever.
Blockchain also supports "smart contracts" — automatic agreements that execute themselves when conditions are met, eliminating the need for middlemen like lawyers or banks.

Originally built for Bitcoin, blockchain now powers healthcare, supply chains, and governance. Challenges like high energy use and scalability persist, but its ability to create trust without a central authority makes it one of the most promising technologies of our time

<img width="646" height="247" alt="image" src="https://github.com/user-attachments/assets/70ac9ac5-1910-4e22-a645-e47047c1fadf" />


RESULT:

Thus the following combination of provides the best summary :
  1. ZERO SHOT - GEMINI
  2. FEW SHOT - GEMINI
  3. CHAIN OF THOUGHT - GEMINI
  4. ROLE BASED - GEMINI





