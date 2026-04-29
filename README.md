# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

---

## Prompting Techniques Used

### 1. Zero-Shot Prompting
PROMPT:WRITE A WELL STRUCTURED, BEGINNER FRIENDLY ARTICLE ON THE BASICS OF BLOCKCHAIN TECHNOLOY FOR 200 WORDS

### 2. Few-Shot Prompting
"Here are 2 example summaries (simple + structured). Generate a similar summary for the blockchain article."

### 3. Chain-of-Thought Prompting
"Break the article into key concepts step-by-step, then produce a final summary."

### 4. Role-Based Prompting
“Act as a teacher explaining blockchain technology to beginner students. Describe what blockchain is, how it works, and its key features like decentralization, transparency, and security. Use simple language and include one real-life example.”

---

## LLM Outputs

---

# 🔹 ChatGPT

### Zero-Shot Output
Blockchain technology is a decentralized digital system used to record and store data securely. Instead of relying on a central authority like a bank or server, blockchain uses a network of computers (called nodes) to maintain a shared database. This makes it more transparent, secure, and resistant to tampering.

A blockchain is made up of blocks, where each block contains data, a timestamp, and a unique code called a hash. These blocks are linked together in a chain, hence the name “blockchain.” Once a block is added, it cannot be changed without altering all subsequent blocks, which makes the system highly secure.

One key feature of blockchain is decentralization. No single entity controls the data, and every participant in the network has a copy of the entire blockchain. This ensures trust among users without needing intermediaries.

Blockchain is best known for powering cryptocurrencies like Bitcoin, but it has many other uses. It can be applied in supply chain management, healthcare, voting systems, and digital identity verification.

In simple terms, blockchain is a secure, transparent, and distributed way of recording information, making it a powerful technology for the future.

### Few-Shot Output
**1. Simple Summary:**
Blockchain is a secure and decentralized way of storing data across multiple computers. It uses blocks linked together in a chain, making the data difficult to change. It removes the need for a central authority and ensures transparency and trust among users. It is widely used in cryptocurrencies and other fields like healthcare and supply chain.

**2. Structured Summary:**

* **Definition:** Blockchain is a decentralized digital ledger used to store data securely.
* **Structure:** Data is stored in blocks connected in a chain using hashes.
* **Key Feature:** Decentralization ensures no single authority controls the system.
* **Security:** Data cannot be easily altered once recorded.
* **Applications:** Used in cryptocurrencies, supply chain, healthcare, and more.

### Chain-of-Thought Output
**Step-by-Step Key Concepts:**

1. **Definition:**
   Blockchain is a decentralized system used to store and manage data securely across multiple computers.

2. **Structure of Blockchain:**
   Data is stored in blocks, and each block contains data, a timestamp, and a unique hash.

3. **Linking of Blocks:**
   Blocks are connected in a chain using hashes, ensuring continuity and security.

4. **Immutability:**
   Once data is added to a block, it cannot be easily changed, making the system reliable.

5. **Decentralization:**
   No central authority controls the blockchain; all nodes share and verify the data.

6. **Transparency and Trust:**
   All participants can view the data, which builds trust without intermediaries.

7. **Applications:**
   Blockchain is used in cryptocurrencies, supply chain management, healthcare, and voting systems.

---

**Final Summary:**
Blockchain is a decentralized and secure system for storing data in linked blocks. Its key features—immutability, transparency, and lack of central control—make it a trustworthy technology. It is widely used in cryptocurrencies and has growing applications in many industries.

### Role-Based Output
Blockchain is a digital system used to store information in a safe and organized way. Think of it like a shared notebook that many people can see and update, but no one can secretly change. Instead of being stored in one place (like a single computer), the data is stored across many computers, which makes it more reliable.

Blockchain works using **blocks** and **chains**. Each block stores some data, along with a timestamp and a unique code called a hash. When a block is filled, it is linked to the previous block, forming a chain. If someone tries to change the data in one block, the hash changes, breaking the chain. This makes tampering very difficult.

One important feature is **decentralization**, meaning no single person or organization controls the data. Another is **transparency**, where everyone in the network can see the records. Finally, **security** is strong because data cannot be easily changed once added.

A real-life example is **Bitcoin**. When you send Bitcoin to someone, the transaction is recorded on a blockchain. Everyone in the network can verify it, and once recorded, it cannot be altered. This builds trust without needing a bank.

---

# 🔹 Gemini

### Zero-Shot Output
## The Basics of Blockchain Technology

Imagine a digital notebook shared across thousands of computers worldwide. Whenever a new entry is added, every computer updates its notebook simultaneously. Once written, the entry cannot be erased or changed. This, in essence, is **blockchain technology**.

At its core, a blockchain is a decentralized, distributed public ledger. Instead of relying on a central authority—like a bank or a government—to verify and manage transactions, blockchain relies on a peer-to-peer network. 

Here are the foundational pillars that make blockchain unique:

* **Blocks and Chains:** Data is stored in "blocks." When a block reaches its storage limit, it is cryptographically sealed and linked to the previous block, forming a secure, chronological "chain."
* **Decentralization:** No single entity controls the network. Copies of the entire ledger are distributed across all participating computers (known as nodes).
* **Immutability:** Once a transaction is verified and recorded on the blockchain, it is virtually impossible to alter or delete, ensuring complete data integrity and fraud prevention.
* **Transparency:** Anyone with authorized access to the network can view the transaction history, fostering absolute trust without needing a middleman.

While famous for powering cryptocurrencies like Bitcoin, blockchain’s potential extends far beyond digital money. From securing sensitive healthcare records to tracking global supply chains, this technology is actively revolutionizing how we store, verify, and share data in the modern world.
### Few-Shot Output
**1. Simple Summary:**
Blockchain is a secure and decentralized way of storing data across multiple computers. It uses blocks linked together in a chain, making the data difficult to change. It removes the need for a central authority and ensures transparency and trust among users. It is widely used in cryptocurrencies and other fields like healthcare and supply chain.

**2. Structured Summary:**

* **Definition:** Blockchain is a decentralized digital ledger used to store data securely.
* **Structure:** Data is stored in blocks connected in a chain using hashes.
* **Key Feature:** Decentralization ensures no single authority controls the system.
* **Security:** Data cannot be easily altered once recorded.
* **Applications:** Used in cryptocurrencies, supply chain, healthcare, and more.

### Chain-of-Thought Output
### Step-by-Step Key Concepts

**1. The Distributed Ledger**
The foundation of blockchain is a shared digital notebook synchronized across thousands of computers, eliminating the need for centralized management or storage.

**2. Decentralized Network**
Control and verification are distributed across a peer-to-peer network of participating computers (nodes) rather than a single governing entity, such as a bank or government.

**3. Cryptographic Linking (Blocks and Chains)**
Data is stored in capacity-limited "blocks." When full, these blocks are cryptographically sealed and permanently connected to the previous block, forming a secure, chronological timeline.

**4. Immutability**
Once data is verified and written to the chain, it becomes permanent. It cannot be altered, deleted, or tampered with, ensuring high security and fraud prevention.

**5. Transparency and Trust**
Authorized users can independently verify the transaction history on the public ledger. This open visibility creates absolute trust without requiring third-party middlemen to oversee the process.

**6. Broad Applications**
Beyond powering cryptocurrencies like Bitcoin, blockchain's secure framework is actively utilized in diverse, real-world sectors, including healthcare record-keeping and global supply chain tracking.

---

### Final Summary
Blockchain is a decentralized, peer-to-peer digital ledger that stores data in a chronological chain of cryptographically sealed blocks. This structure guarantees that recorded transactions are transparent, verifiable, and completely immutable. By removing the need for central authorities, blockchain provides a highly secure and trustless method for managing everything from digital currencies to supply chain logistics and sensitive health records.
### Role-Based Output
Hello everyone! Today, let's talk about **blockchain technology**.

Imagine you and all your classmates are keeping track of your shared allowance, and you use a magical digital notebook. Every time someone spends or adds money, they write it down. But here is the magic part: the moment they write something, a copy of that exact page instantly appears in everyone else's notebook. 

This magical notebook is what we call a **blockchain**. It is a digital record-keeping system, often called a "ledger."

**How It Works:**
Whenever new information (like a transaction) is recorded, it is packed into a digital box called a **"block."** Once that block is full of data, it gets securely locked and linked directly to the block that came right before it. This creates a permanent, chronological **"chain"** of blocks—hence the name, blockchain!

There are three key features that make this technology so powerful:

1. **Decentralization:** There is no single "boss" or central authority (like a traditional bank) controlling the notebook. Instead, the power is shared. Everyone in the network helps manage it, and everyone holds an identical copy.
2. **Transparency:** Because everyone in the network has a copy of the notebook, anyone can look back and see the history of what was written. Every transaction is visible to the participants. 
3. **Security:** Once a block is locked and added to the chain, the information inside is sealed using complex math. It cannot be erased, changed, or tampered with by anyone.

**A Real-Life Example:**
Think about buying a special, expensive pair of sneakers. Sometimes it is hard to tell if they are genuine or fake. If the sneaker company uses a blockchain, the factory records when the shoes were made (Block 1), the shipping company records when they were transported (Block 2), and the store records when they arrived (Block 3). When you buy the shoes, you can look at this blockchain. Because it is decentralized, transparent, and completely secure, you can trust that the history hasn't been faked, proving your sneakers are 100% authentic!
---

# 🔹 Claude

### Zero-Shot Output
Blockchain is a distributed ledger where transactions are recorded in blocks linked via cryptographic hashes. It ensures transparency and security.

### Few-Shot Output
Blockchain stores transactions in linked blocks secured through hashing. Consensus mechanisms validate entries. It supports applications like cryptocurrencies and smart contracts.

### Chain-of-Thought Output
Step 1: Identify blockchain as ledger  
Step 2: Explain block structure  
Step 3: Add consensus concept  
Step 4: Mention applications  

Final Summary:  
Blockchain is a decentralized ledger system ensuring secure and immutable records through cryptographic linking and consensus.

### Role-Based Output
As an academic explanation, blockchain is a distributed ledger that ensures immutability and trust through decentralized validation and cryptographic techniques.


## Result
<img width="1536" height="1024" alt="ChatGPT Image Apr 29, 2026, 08_51_03 PM" src="https://github.com/user-attachments/assets/68b104e0-9520-4258-b929-04e6a0914e4b" />


