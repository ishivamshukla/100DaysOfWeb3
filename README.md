# # 100DaysOfWeb3

Language-specific interview questions are key to evaluating a candidate's programming skills. Check out the questions that apply to your tech stacks and see if 
your answers are on the right track.

> Click :star:if you like the project. Pull Requests are highly appreciated. Follow me [Shivam Shukla](https://twitter.com/itshivamshukla) for technical updates.

Go to [Coding Exercise](#coding-exercise) for coding specific questions



---

 [Blockchain ⛓](#-Blockchain)
---

In their ..............



### Table of Contents


| Day | Topices |
|---- | ---------
|1  | [What is Blockchain?](#what-is-blockchain?) |
|2  | [What is the consensus mechanism : Proof-Of-Work?](#what-is-the-consensus-mechanism-proof-of-work?)|
|3  | [What is Proof-Of-Stake?](#what-is-proof-of-stake?)|
|4  | [What is Web3?](#what-is-web3?)|
|5  | [What are Decentralized applications or dApps?💻](#What-are-decentralized-applications-or-dApps?)|
|6  | [What is DeFi or Decentralized Finance?](#What-is-DeFi-or-Decentralized-Finance?)|
|7  | [What are Smart Contracts?](#what-are-smart-contracts?)|
|8  | [As a beginner in the blockchain development space, one could face multiple challenges🛑](#As-a-beginner-in-the-blockchain-development-space,-one-could-face-multiple-challenges)|
|9  | [What is a DAO?](#what-is-a-DAO?)|
|10  | [What is a Crypto Wallet?](#what-is-a-Crypto-Wallet?)|
|11  | [What is Metaverse?](#what-is-metaverse?)|
|12  | [What is Ethereum?](#what-is-ethereum?)|
|13  | [Coming soon](#coming-soon)|
|14  | [Coming soon](#coming-soon)|
|15  | [Coming soon](#coming-soon)|
|16  | [Coming soon](#coming-soon)|
|17  | [Coming soon](#coming-soon)|
|18  | [Coming soon](#coming-soon)|
|19  | [Coming soon](#coming-soon)|
|20  | [Coming soon](#coming-soon)|
|21  | [Coming soon](#coming-soon)|
|22  | [Coming soon](#coming-soon)|
|23  | [Coming soon](#coming-soon)|
|24  | [Coming soon](#coming-soon)|
|25  | [Coming soon](#coming-soon)|
|26  | [Coming soon](#coming-soon)|
|27  | [Coming soon](#coming-soon)|
|28  | [Coming soon](#coming-soon)|
|29  | [Coming soon](#coming-soon)|
|30  | [Coming soon](#coming-soon)|
|31  | [Coming soon](#coming-soon)|
|32  | [Coming soon](#coming-soon)|
|33  | [Coming soon](#coming-soon)|
|34  | [Coming soon](#coming-soon)|
|35  | [Coming soon](#coming-soon)|
|36  | [Coming soon](#coming-soon)|
|37  | [Coming soon](#coming-soon)|

|100  | [Conclusion](conclusion)|

---


1. ### What is Blockchain?⛓


**📌Why was this technology even introduced?**

- To remove power from central authority 
- To prevent frauds
- To have more transparency 
- To have immutable records
  
  
**📌 When and how did it all start?**

This technology was introduced back in 2008 by an anonymous person(or group) called as "Satoshi Nakamoto"

**📌 What is Blockchain?**

Blockchain is a chained link of blocks  wherein each block contains data and those blocks are linked together via cryptography and in a chronological order

**📌 Why is it called a Decentralised technology?**

Since the complete list of data stored in the blockchain is not in control of any central authority but is like a distributed public ledger which anyone and everyone can have a copy of.

**📌 What all major information is stored in a block?**

- Data e.g. transaction information in case of Bitcoin
- Hash of the current block : Cryptographically aggregated transaction information of the block 
- Hash of previous block

**📌 How is it secure?**

Since every block contains the hash of the previous block, in order to make change in any one of the blocks the hacker will have to make changes to every other previous block as well, which is next to impossible & that's how it is secured

**📌 How does a transaction goes through?**

- Transaction is sent to the network
- All the nodes gets notified who then start solving a complex mathematical puzzle
-  Whoever solves it first let the rest of the nodes know who then start validating it
- If at least 50% nodes validate it to be true, the transaction is added to blockchain & the node who solved it is rewarded with crypto
- The nodes who participate in solving the puzzle are called "Miners"
- Also, once the information is added it can never be removed or edited


   **[⬆ Back to Top](#table-of-contents)**
 ---  
   
2. ### What is the consensus mechanism : Proof-Of-Work?

**📌 What is consensus?**

Let's understand it with an example :
If your family is planning to buy a car and if more than half of the persons in the family agree upon a certain model of the car, then we say 
we have reached a consensus or in simple terms agreement upon something.


**📌 What is blockchain consensus mechanism?**

Since blockchain is a public distributed ledger and an agreement is required from every node in the network to make any addition to the blockchain, 
it is nothing but a certain procedure to reach an agreement upon current state of network


**📌 Why is a consensus mechanism required?**

In a centralised world, where the central authority is solely responsible for everything & ensures trust. In a decentralised world, in 
order to prevent chaos a mechanism or system is required to reach to a consensus for any decision made


**📌 What is Proof-Of-Work?**

- Proof-Of-Work got it's name for the work the computer nodes called as miners do while competing to solve a complex mathematical puzzle by hit and 
- trail method to find a number called as nonce, in order to add the next block in blockchain
- Once the puzzle is solved by the fastest miner, it's sent to the network which is then validated & the solver is rewarded with newly mined crypto
- One key feature of this mechanism is the difficulty to solve the problem and ease to cross check the results by rest of the nodes



**📌 What is the problem with Proof-Of-Work?**

Since solving the puzzle requires a lot of computational power and hence high electricity consumption. Hence it is not good for the environment.
FACT : Bitcoin mining which uses PoW consumes more energy than some countries do in a year😨


   **[⬆ Back to Top](#table-of-contents)**
 
 ---  
   
3. ### What is Proof-Of-Stake? 🤔

**📌  Why we require Proof-of-Stake consensus mechanism if we have Proof-of-Work?**

If you have read my last tweet, you should have at least 1 answer😉

- Negative impact on the environment 🌍 
- Expensive to be a miner 💵
- Scalability : Less transactions processed per second⏱


**📌 What is Proof-of-Stake?**

- It does not have miners but instead validators
- Only who put their crypto on stake become validators
- There is no competition but a validator is picked in a pseudo-random way, who propose to add next block
- Other validators "attest" or checking it to be true
- Both type of validators are rewarded basis their stake
- If wrong block is proposed or attested, staked coins are slashed. Meaning loosing a portion of coins staked


**📌 What are the factors affecting validator selection?**

- How long a validator has been staking
- Randomisation
- And, highly on amount staked. Higher amount staked, higher chances of getting selected


**📌 Does it mean that whoever stakes more will most of the time gets selected? Leading to centralisation?**

Can you think or find answer to that? 🧐

If you can't find the answer, let me know in the comments. I'll answer to that 👻



**📌 What is the benefit of it?**

- Incentivised mechanism - More participation for becoming validators
- Fear of loosing the crypto staked indirectly forces the validators to act in the network’s best interests
- Increased scalability
- Don't require bigger machinery


**📌 Are there any cons of Proof-of-Stake?**

- It's relatively less tried and tested than Proof-of-Work
- Person need to have a minimum number of crypto coin to become a validator


   **[⬆ Back to Top](#table-of-contents)**
 ---  
   
4. ### What is Web3?🌐

**📌 What is Web?**

- World Wide Web commonly known as Web is something built on top of Internet.
- Collection of documents that can be requested by a browser from a server
- Each document can accessed by a web address


**📌 Why is it suffixed with 3? Are there any 1 and 2 as well?**

Yes there are✅

Web1 
- Static web pages
- Read-only : Not Interactive
- More consumers less creators

Web2 
- Interactive and social web
- Read/write
- Gave birth to more creators
- Largely handled by big tech firms


**📌 Why Web3?**

- In Web2, Centralisation by big techs providing services in exchange of personal data
- Have to abide by the rules of government/company's (You never know when your tweet might be taken down :p)


**📌 What is Web3?**

- A decentralised web
- Runs on blockchain technology
- Read/write/own
- No particular companies owning the data
- Platforms and apps not owned by central authority


**📌 Key features of web3**

- Open - Built from open source software
- Trustless - No intermediary required
- Permissionless - No authorisation required
- Secure - Not owned centrally
- Privacy - No direct data breach



   **[⬆ Back to Top](#table-of-contents)**
 
 ---
   
5. ### What are Decentralized applications or dApps?💻

**📌 Why do we even require dApps?**

Think about all apps you use or say Twitter which you're using rn. Who have the ultimate authority over them? Their Owners, right. Also, they do 
have access to all our data we upload or access on their apps. Do you now get it, why we need dApps?


**📌  What are dApps?**

- Looks like any other application you use
- They run on a blockchain
- Back end code runs on decentralized network instead of centralized server
- There are no big tech companies involved in between
- dApps exist almost exclusively on Ethereum blockchain rn


**📌 Key benefits of dApps**

- More secure apps as they have cryptography as their backbone
- Privacy & Data security
- No dependence on trustworthiness of third parties
- No single point of failure
- Open and transparent
- Controlled by logic written in the contract
- No Censorship


**📌 Possible cons of dApps**

- Challenges in initial increase in user adaptability
- Difficulty to make code modifications
- Scalability : Might face slow transaction speed


**📌 Some Popular dApps -Twitter**

- Brave Browser 
@brave

- Chainlink 
@chainlink

- MakerDAO 
@MakerDAO

- Uniswap 
@Uniswap

- Axie Infinity 
@AxieInfinity
 
and many other


**📌 My thoughts**

- Indeed a revolutionary idea
- Might take time to evolve
- It is going to make a place in people's life in the future


   **[⬆ Back to Top](#table-of-contents)**
  
---
   
6. ### What is DeFi or Decentralized Finance?💻🤔

**📌  Let's understand Why DeFi with examples**

1/ Many countries have declared Demonitization in past. Where existing national currency can no longer be used for exchange purposes
2/ Have you ever sent money to anyone staying in some other country and have paid extra amount as fee
3/ Have you feared that what will happen to your money if bank shuts down😱

The above examples quoted are direct implication of the loopholes of current traditional financial system.

But WHY?? Because the backbone of this system is centralization⨝


**📌 What is DeFi?**

- It's a collective term used for the financial products & services built on blockchain
- Just like in other financial institutions, you can transfer, borrow, invest or lend money but without any third party

In simple terms, it's like a peer-to-peer bank
- Database of each and every financial action is recorded on the public distributed ledgers
- Every action is verified by the network & gets executed only after the consensus
- It's a decentralized alternative to the existing financial system


**📌 But where are the rules written?**

Here comes the role of smart contracts. These are logic codes running in the background which add program logic into payments. These piece of code makes it possible to invest & earn interest, lending, borrowing, insurance etc on the blockchain


**📌  Key benefits of DeFi**

- Open : Unlike bank, no one can stop you from using any services
- Ownership : You become real owner of your money
- Transparent : No third party involved, trackable history
- Pseudonymous : No real identity disclosed
- Quick :  Faster processing speed


   **[⬆ Back to Top](#table-of-contents)**
---  
   
7. ### What are Smart Contracts?📝

**📌 Limitation of Bitcoin🤓**

On Bitcoin blockchain, we can only do peer-to-peer money transfer: X sends $10 to Y, X account credited & Y account debited

But how to execute more complicated logic than this: If X lend $10 to Y,Y return $15 to X in 6 months



**📌 How is the execution of complicated logic possible?🤔**

Many new blockchains are developed so that they can store logic in form of computer code to further support secured financial contracts and applications. These computer codes containing logic are called Smart contracts


**📌 What are Smart Contracts?⚙️**

- Similar to paper contracts but they are digital
- Immutable computer programs saved & processed on blockchain
- One can interact with it by submitting transactions that execute a function defined in it only if pre-defined conditions are met


**📌 Best example to understand smart contract🤩**

It's like a digital vending machine
If button 1 is pressed & x amount deposited, you'll get a cookie🍪

Similarly we can code, if the payment is received, deeds from a house sale will be transferred to the buyer.


**📌 Why do we need smart contracts?😎**

- Eliminates intermediaries- distributed, No trust required on third party
- Permissionless- Anyone can create a smart contract & deploy on blockchain
- Quick, efficient & secure
- Immutable- No one can make change to it  
- Trackable records


**📌 Popular domains where smart contracts are used✅**

1/ Finance
2/ Insurance
3/ Health Systems
4/ Supply Chain Management
5/ Government (Voting)
6/ Trading
7/ Gaming
& many more



**📌 Major Programming Languages in which smart contracts are written on different blockchains💻**

1/ Solidity
2/ Vyper
3/ Rust
4/ JavaScript
5/ Yul


**📌 Major cryptocurrencies with smart contracts💵**

1/ Ethereum
2/ Solana
3/ Polkadot
4/ Cardano
5/ Alogorand


   **[⬆ Back to Top](#table-of-contents)**

---

8. ### As a beginner in the blockchain development space, one could face multiple challenges🛑


1️⃣ If you've never heard of blockchain & it's associated terminology before. You'll have to put in some efforts to understand it first. 

It's not that complicated but it's something you must understand well.


2️⃣ There are a lot of pieces which one needs to understand in order to understand how one can build on blockchain like Solidity, Remix, Truffle, Ganache, web3, JS, react etc. 

This could be the primary challenge but once you deep dive into it you'll understand all gradually


3️⃣ You might face the dilemma to decide between learning how to build back end or front end. What should I learn first. Where should I invest more time.

Gradually you'll feel both are extremely important. The major thing is to start with something.


4️⃣ If you've not done any sort of app or web development prior to this, just like me. It could seem a bit difficult in the beginning to understand how the interaction between the front and back end works.

I felt a sense of accomplishment after learning this


5️⃣ You might hear a lot of terms around the blockchain space like DeFi, NFT, DAO, Ethereum, Web3 and many more which might seem confusing.

Don't try to delve into everything at once. Take it slow. I do post content around all of this, so don't forget to check it out.


   **[⬆ Back to Top](#table-of-contents)**

---   

9. ### What is a DAO?😎

After hearing so much about the word DAO, we have a sense that DAO is some sort of community.
We do see a lot of meet-ups organised by a DAO, they have discord channels but is it just that? 🤔


**📌 What is a DAO?🧐**

DAO stands for Decentralized Autonomous Organization

First, let's understand these words individually and then combine each of the word's meaning to have a better picture of what DAO exactly is.

1. Decentralized: Something which is not controlled by a central authority but the power is distributed among many
2. Autonomous: Self-governed, carried out without outside control 
3. Organization: Group of people working together with a particular purpose
 
 Combining all three, a DAO is a group of people who come together for a specific purpose and the community's activities like planning, decision making etc are distributed or delegated away from any central authority.


**📌 What's different about DAO?🤩**

- No hierarchy unlike any other organization. No CEO
- Rules and regulations are built using open-source code and carried out via smart contracts
- No special authority can modify rules of a DAO
- All activities are public and transparent


**📌 How does DAO work?⚙️**

- Rules are formed by core team members
- Rules get published on blockchain via smart contracts
- Funding is received by issuing crypto tokens
- Members having token gets the right to vote
- DAO is then deployed and considered functional & live


📌 How are decisions taken?📝

- Community members create proposals
- Voting is done on each proposal 
- Proposals that achieve some predefined level of agreement are then accepted and enforced by the rules written within the smart contract, without any trusted intermediary


**📌 Can anyone become a member of a DAO?👥**

Some DAOs let anyone join while for others, users need to first join the DAO by buying its token or NFT etc. One who holds the asset gives the member the power to vote on proposals and updates, proportional to the amount they hold


**📌 Purpose of forming DAOs✅**

There could be n number of purposes starting from Investment, Charity, Fundraising, Buying NFTs etc with the sole purpose of having a community in which purpose is achieved without having exclusive trust on anyone by relying on blockchain as backbone



   **[⬆ Back to Top](#table-of-contents)**
   
---  

10. ### What is a Crypto Wallet?💰


**📌 Let's understand it in simple terms**

Just like bank have net banking services to manage money kept in bank where Password act as a gateway to access/trade funds

Similarly, crypto wallet stores the keys to access your digital money where actual money is stored on blockchain



**📌 What is a Crypto Wallet?**

- It can be an online software or physical device which helps to access, manage & trade crypto
- Each wallet has a pair of keys called private and public keys
- Wallet facilitates interaction with the balances that exist and held on the blockchain



**📌 Type of keys**

Private Key - It's a password to access funds stored in wallet

Public Key - It is derived from private key. Can be thought of as bank account number which is shared with peers for receiving crypto


**📌 Two major types of Crypto Wallets**

1. Software/Hot wallets - Online software
2. Hardware/Cold wallets - Physical drive


**📌 Software/Hot Wallets**

These are desktop programs like Electrum wallet, mobile app like Coinbase or browser extension like Metamask that hold the keys online and makes transaction in crypto smooth and easy.



**📌 Hardware/Cold Wallets**

- Like a hard drive storing the keys which can be plugged into a computer 
- Assumed to be safer since it eliminates interaction of the wallet & the online network
- Sensitive information is not exposed because of extra protection built in the software



**📌 Pros of Crypto Wallet**

- Ownership: There is no bank which is actually keeping your money. You become the sole owner
- No Censorship: Crypto can be transferred from anywhere to anyone without any external pre-conditions or permission
- Open doors for NFT, DeFi and much more


**📌 Cons of Crypto Wallet**

- Anyone having your private key can access your funds - In order to keep your crypto safe, one need to keep private key safe
- If private key is lost, funds get locked and can't be accessed


   **[⬆ Back to Top](#table-of-contents)**
---

11. ### What is Metaverse? 🤯



- It's known be the next phase of internet. Just like internet was something revolutionary back in 90s, similar to that metaverse is going to be the next revolutionary thing of the 21st century.

- In most simple words, it's a "virtual world" where we'll have digital version of ourselves or avatars and we can can do almost everything which we're able to do in our real lives like learn, shop, play, work, meet friends and what not.

- If you want to get a feel of what metaverse is going to be like, you can definitely give this movie a watch : "Ready Player One".

My thoughts : We're heading towards a technology wherein we'd need highly need to use our conscience in order to not let it affect our real avatars 😁


   **[⬆ Back to Top](#table-of-contents)**

---

12. ### What is Ethereum?


The invention of Bitcoin blockchain popularised two major concepts
1. Decentralized currency
2. Blockchain technology

Limitation of Bitcoin: Usage limited to peer-to-peer money transfer over the internet

But can this blockchain technology be leveraged to do more than just that?


**📌 Possible solutions to overcome the limitation**

- Building a new blockchain with enhanced features: Difficult to implement with high development time
- Building something on top of Bitcoin: Less scalable
- Trying to use programming on top of Bitcoin: Limited capabilities



**📌 By whom and when was Ethereum invented?**

With the first approach taken to build a new blockchain network, Vitalik Buterin in 2014 published a white paper with the vision of Ethereum and on 30th July 2015, Ethereum was live.



**📌 What is Ethereum?**

- Decentralized, open-source blockchain with native crypto as Ether/ETH
- Establish peer-to-peer network securely executing & verifying application code called smart contracts
- Uses Proof-Of-Work consensus mechanism but soon moving to Proof-Of-Stake

📌 What is Proof-Of-Work?
 
 **[⬆ Back to Day02](#What-is-Proof-Of-Work)**

📌 What is Proof-Of-Stake?

 **[⬆ Back to Day03](#What-is-Proof-Of-Stake?)**

📌 What are Smart Contracts?

 **[⬆ Back to Day07](#What-are-Smart-Contracts?)**


📌 Key Features of Ethereum

- Not only a medium of exchange and a store of value but is a programmable blockchain which can do much more
- Allows developers to build and use decentralized applications:

 **[⬆ Back to Day05](#What-are-Decentralized-applications-or-dApps?)**
 
 

📌 What is an Ethereum account?

It is an entity with an ether(ETH) balance that can send transactions on Ethereum

Types of Ethereum accounts:
1. Externally Owned Accounts
2. Contract Accounts

Both can call any public function of a smart contract or create a new smart contract


📌 Externally Owned Accounts(EOA)

- Controlled by their private key
- Can initiate transactions
- New EOA account can be created anytime without cost
- It's public key is derived from it's private key


📌 Contract Accounts

- Controlled by contract code. No private key 
- Can send transactions in response to receiving transactions
- New contract account can only be created from EOA or from existing deployed contract with a cost
- Public address = EOA Public address + nonce

📌 Popular use cases of Ethereum

- Decentralized Finance(DeFi) https://twitter.com/GargEtisha/status/1506346204153536514
- Decentralized Autonomous Organization(DAO)
https://twitter.com/GargEtisha/status/1508514562504486913
- Non-Fungible Tokens(NFTs)
https://twitter.com/GargEtisha/status/1486725231611768832

and many more...



   **[⬆ Back to Top](#table-of-contents)**

---

13. ###



   **[⬆ Back to Top](#table-of-contents)**

---

14. ###


   **[⬆ Back to Top](#table-of-contents)**

---

15. ###



   **[⬆ Back to Top](#table-of-contents)**

---

16. ###
17. ###
18. ###
19. ###
20. ###
21. ###
22. ###
23. ###
24. ###
25. ###
26. ###
27. ###
28. ###
29. ###
30. ###
31. ###
32. ###
33. ###
34. ###
35. ###
36. ###
37. ###
38. ###
39. ###
40. ###
41. ###
42. ###
43. ###
44. ###
45. ###
46. ###
47. ###
48. ###
49. ###
50. ###
51. ###
52. ###
53. ###
54. ###
55. ###
56. ###
57. ###
58. ###
59. ###
60. ###
61. ###
62. ###
63. ###
64. ###
65. ###
66. ###
67. ###
68. ###
69. ###
70. ###
71. ###
72. ###
73. ###
74. ###
75. ###
76. ###
77. ###
78. ###
79. ###
80. ###
81. ###
82. ###
83. ###
84. ###
85. ###
86. ###
87. ###
88. ###
89. ###
90. ###
91. ###
92. ###
93. ###
94. ###
95. ###
96. ###
97. ###
98. ###
99. ###
100. ###
101. ###
102. ###
103. ###
104. ###
