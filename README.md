# Comparative Analysis of Cryptographic Hash Functions: Evaluating SHA-256 and BLAKE-256 within Cryptocurrency Applications

## Dagmawi Zerihun

### Department of Computer Science, Denison University

---

## Abstract

This paper explores the crucial role of cryptographic hash functions in cryptocurrencies such as Bitcoin. These functions, crucial for securing transactions without a centralized authority, illustrate the advanced capabilities of digital signatures and hash algorithms. Cryptocurrencies leverage cryptographic hashing algorithms to ensure the security and decentralization of their networks. Through a detailed examination and comparison of SHA-256 and BLAKE-256, two notable cryptographic hash functions in the cryptocurrency space, this study highlights their vital features and comparatively analyzes them with regard to speed, security, application space, and complexity within digital currency systems.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Background](#background)
3. [Cryptographic Hash Functions](#cryptographic-hash-functions)
   - [Properties of Cryptographic Hash Functions](#properties-of-cryptographic-hash-functions)
   - [Notable Cryptographic Hash Algorithms](#notable-cryptographic-hash-algorithms)
4. [A Survey of Select Cryptographic Hash Functions Used in Cryptocurrencies](#a-survey-of-select-cryptographic-hash-functions-used-in-cryptocurrencies)
   - [SHA-256](#sha-256)
   - [BLAKE](#blake)
   - [Comparative Analysis of SHA-256 and BLAKE-256](#comparative-analysis-of-sha-256-and-blake-256)
5. [Conclusion](#conclusion)
6. [References](#references)

---

## Introduction

In the digital financial landscape, secure transaction processing poses a significant challenge. Cryptographic hash functions play a crucial role in cryptocurrencies by providing a mechanism for transaction security without centralized oversight. The emergence of cryptocurrencies like Bitcoin and Ethereum introduces complexities to digital transactions that operate independently of central authorities.

This paper surveys select cryptographic hash functions, their properties, and their use cases in the networks of cryptocurrencies. These functions are integral to the security framework of cryptocurrencies. After a brief overview of cryptographic principles, this paper gives a detailed overview of two important cryptographic hash functions used in the security of popular cryptocurrencies: SHA-256 and BLAKE. This will be followed by a comparative analysis of these algorithms, evaluating their critical features and performance regarding security and efficiency.

---

## Background

Cryptocurrency is a digital asset that utilizes blockchain technology or a distributed ledger to ensure secure transactions. It utilizes cryptography to secure transactions and effectively "eliminate" the intermediaries in financial transactions such as central banks or other comparable traditional financial institutions while ensuring security and performing the functions of a traditional currency (store of value, medium of exchange). Unlike traditional financial transactions, which are controlled and verified by a central entity, cryptocurrencies are decentralized, using a network of nodes and a distributed ledger to verify transactions, making them secure and reliable. The concept of the first cryptocurrency – Bitcoin – was first introduced in 2008 under the pseudo-name "Satoshi Nakamoto". It was designed based on the principles of cryptography – decentralization, cryptographic hashing, asymmetric key cryptography, and digital signatures. These principles are foundational to Bitcoin’s underlying blockchain technology - a decentralized way of recording transactions across a network of computers.

---

## Cryptographic Hash Functions

### Properties of Cryptographic Hash Functions

Cryptographic hash functions must fulfill certain properties beyond the basic hash function properties for use cases such as ensuring transaction integrity and security in cryptocurrencies.

- **One-Way Property**: A hash function is deemed one-way if it is computationally infeasible to reverse-engineer the original input from its hash value.
- **Collision Resistance**: A hash function should be computationally infeasible to find any two distinct inputs that hash to the same output.
- **Second Pre-Image Resistance**: Given one input value, it should be computationally infeasible to find a second distinct input that produces the same output.

### Notable Cryptographic Hash Algorithms

#### SHA (Secure Hashing Algorithm) Family

The SHA family is a fundamental group of cryptographic hashing algorithms with extensive use in cryptocurrencies. This family of algorithms encompasses several different hash functions: SHA-1, SHA-224, SHA-256, SHA-384, SHA-512, SHA-512/224, and SHA-512/256. Among these, the SHA-256 algorithm is particularly notable for its use in Bitcoin.

#### BLAKE

BLAKE is a cryptographic hash function notable for its efficiency and security. Although not selected as the final standard in the NIST SHA-3 competition, BLAKE's design was highly appreciated for its robustness and efficiency. The algorithm is known for its high security and speed in software implementations.

---

## A Survey of Select Cryptographic Hash Functions Used in Cryptocurrencies

### SHA-256

The SHA-256 algorithm is an iterative hash function designed to condense an input message into a compact summary known as a message digest. It is best known for its use in the first cryptocurrency Bitcoin among others. The algorithm can be described in two stages: preprocessing and hash computation.

### BLAKE

BLAKE is a cryptographic hash algorithm notable for its efficiency and security. Designed for the SHA-3 competition but not ultimately selected, BLAKE has since been refined into the BLAKE2 version, which includes BLAKE2b and BLAKE2s. The BLAKE-256 variant processes 512-bit blocks into a 256-bit hash output, similar to SHA-256 in terms of output size.

### Comparative Analysis of SHA-256 and BLAKE-256

- **Complexity**: SHA-256 is characterized by a fixed block size and a relatively complex series of bitwise operations and permutations. BLAKE’s design is simpler and more streamlined.
- **Speed**: BLAKE outperforms SHA-256 in terms of speed on similar hardware configurations.
- **Application Space**: SHA-256 dominates the application space in established cryptocurrencies like Bitcoin. BLAKE is used in cryptocurrencies that prioritize fast block generation.
- **Security**: SHA-256’s security is well-tested. BLAKE’s security features, including built-in defenses against side-channel attacks, make it equally robust.

---

## Conclusion

This paper has presented a comprehensive comparative analysis of SHA-256 and BLAKE-256 cryptographic hash functions within the cryptocurrency space, emphasizing their roles in securing digital transactions without centralization. These hash functions enhance the security and integrity of blockchain technologies, each bringing unique strengths to the table. SHA-256, deeply embedded in the architecture of Bitcoin, offers unmatched security and reliability, tested by rigorous real-world applications. On the other hand, BLAKE-256 distinguishes itself with its design efficiency, providing superior performance, particularly in terms of speed making it advantageous for systems with high demand.

---

## References

1. Decred: A Hybrid Proof-of-Work, Proof-of-Stake System. [Link Placeholder]
2. Antonopoulos, Andreas M. "Mastering Bitcoin: Unlocking Digital Cryptocurrencies." O'Reilly Media, Inc.
3. Aumasson, Jean-Philippe, et al. "The Hash Function BLAKE." [Link Placeholder]
4. Aumasson, Jean-Philippe, et al. "BLAKE2: Simpler, Smaller, Fast as MD5." Springer, Berlin, Heidelberg.
5. Barker, Elaine. "Guideline for Using Cryptographic Standards in the Federal Government: Cryptographic Mechanisms." NIST Special Publication 800-175B Revision 1. National Institute of Standards and Technology. [Link Placeholder]
6. Chandra, Sourabh, et al. "A comparative survey of Symmetric and Asymmetric Key Cryptography." 2014 International Conference on Electronics, Communication and Computational Engineering. [Link Placeholder]
7. Courtois, Nicolas T., and Lear Bahack. "On Subversive Miner Strategies and Block Withholding Attack in Bitcoin Digital Currency." [Link Placeholder]
8. Härdle, Wolfgang Karl, et al. "Understanding Cryptocurrencies." Journal of Financial Econometrics, 2020. [Link Placeholder]
9. Mallouli, Fatma, et al. "Comparative Study of Cryptocurrency Algorithms: Coronavirus Towards Bitcoin’s Expansion." Advances in Science, Technology and Engineering Systems Journal, 2020. [Link Placeholder]
10. Nakamoto, Satoshi. "Bitcoin: A peer-to-peer electronic cash system." [Link Placeholder]
11. Salas, S.L., and Einar Hille. "Calculus: One and Several Variable." John Wiley and Sons, New York.
12. Sobti, Rajeev, and Geetha Ganesan. "Cryptographic Hash Functions: A Review." International Journal of Computer Science Issues, 2012. [Link Placeholder]
13. Steffen Thomsen, Søren. "Cryptographic Hash Functions." Ph.D. Dissertation.
14. Vorick, David, and Luke Champine. "Sia: Simple Decentralized Storage." [Link Placeholder]
15. Yli-Huumo, Jesse, et al. "Where Is Current Research on Blockchain Technology?—A Systematic Review." PLoS ONE, 2016. [Link Placeholder]
16. Ünsal, Erkan, et al. "A Review of Hashing Algorithms in Cryptocurrency." International Conference on Frontiers in Academic Research, 2023. [Link Placeholder]
