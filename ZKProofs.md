## Introduction to Zero Knowledge Proofs
[Home](README.md)
### Introduction
Blockchain technologies are on the rise as the amount of instructions and calculations we are able to execute on processers grows continuously. The most famous example of this technology in use today is cryptocurrencies, namely Bitcoin. In 2009 when Satoshi Nakamoto was coming up with the idea for Bitcoin, he ran into the problem regarding security since blockchains are typically open to the public and decentralized. This is considered a great feature by many, however what if we want to use the blockchain but keep some or all of the pieces of the transaction private, like in an election for instance? This is where zero-knowledge proofs may play a critical role. 

### How do Zero Knowledge Proofs Work?
There are two examples that I think really stand out on how zero knowledge proofs work. The first, which can be seen in the 2018 talk given by Elad Verbin at the Web3 Summit (1), is the Find Waldo experiment which may also be the most famous example out there right now. Let's say I want to prove to you that Waldo is on the page in a Find Waldo book. I want you to be able to verify that Waldo is indeed on the page without revealing _where_ on the page he is. The best way for me to do this would be to go behind a big screen or something to where you cannot see me or the position the book is in. I can show you the cut out of Waldo on the page, you just don't know where he is relative on to the page in the book. 

Another great example was given by Zooko Wilcox at the a16z Crypto Summit in 2019 which can be found on YouTube (3). In this example, two different bits, a 0 and 1, are chosen by Alice. Bob does not know what the bits are but wants to know whether they are the same or not. Bob does not trust Alice to tell the truth, so instead he takes them and without looking at them, performs an operation on the bits. The operation in this example is swapping the bits and then asking Alice if the bits have been swapped. Bob knows if they have been swapped since he performed the operation. Alice knows if they are swapped if the bits are different, if they are the same she would not be able to tell. So if Bob verifies with Alice, hundreds or thousands of times, that the bits have been swapped we can confirm the answer to our question that yes the bits are the same or no they are not.

This is a very simplified version but that is the basic idea and I think those two examples give a great mental image for what is going on in the proof.

### Applications for Zero Knowledge Proofs other than Finance
#### Elections and Voting
I think one of the most promising and applicable tasks blockchains with zero knowledge proofs could be applied to is elections and voting. Whether it be on the local or national scale. It seems like this option would allow a faster voting process, which would allow for more frequent voting among all citizens, as well as more secure and trusting elections. If everyone can verify that the votes tally up the way they are supposed to there can be no disputes like we have seen recently in our political atmosphere. Zero knowledge proofs would allow citizens votes to still remain anonymous but still be counted and verified.

#### Healthcare
For regulatory purposes, most medical data is siloed away in each providers own databank. If you go to a different hospital, they would need to request your records from a previous provider. This could change if a patients data was in a "wallet" on a decentralized network accessible by all providers. The only issue with this is that blockchains are mostly visible to the public. ZK proofs could help change this and allow for medical providers and even first responders to get critical information about a patient without having to wait for another entity. 

### Conclusion
This blog post ignores the ethical questions we have to face and answer before moving forward with some of these applications, especially the notion of using blockchains to store health records. It also ignores the recent environmental concerns over blockchain use, some of which are being addressed with PoS networks.

With how many exploits and hacks have happened recently on blockchain networks, it is clear that we still have a long way to go before making anything like healthcare on a blockchain a reality. But that does not mean that there are not good use cases for the technology. 

Overall, I am excited to see the potential uses for ZK Proofs and how they may change the way we store data about ourselves and how it may bring improvements to the democratic process. 

## Youtube Videos
1. [ZK Proofs and Future Applications - Elad Verbin Web3 Summit 2018](https://www.youtube.com/watch?v=J3jKROwTPCs)
2. [5 Levels of Difficulty](https://youtu.be/fOGdb1CTu5c)
3. [Security and Privacy for Crypto with Zero-Knowledge Proofs](https://www.youtube.com/watch?v=3NL0ThdvWMU&t=269s) 

## Research Papers/Articles (AMA 11th Edition)
4. Sun X, Yu FR, Zhang P, Sun Z, Xie W, Peng X. A Survey on Zero-Knowledge Proof in Blockchain. _IEEE Network_. 2021;35(4):198-205. doi:10.1109/MNET.011.2000473
5. RUI ZHANG, RUI XUE, LING LIU. Security and Privacy on Blockchain. _ACM Computing Surveys_. 2019;52(3):1-34. doi:10.1145/3316481
6. https://venturebeat.com/2017/12/16/what-zero-knowledge-proofs-will-do-for-blockchain/
