# The Open-Immutable-Storage-Solution-Standard LayerOne (OISS-STD-L1) Whitepaper: A New Standard For Immutable, Permanent Storage Of Data on Blockchains Without Requiring Any Finances

## Abstract

With the invention of Bitcoin came a new decentralized financial system where there no longer needed to be trust in a third party. This was the introudction of blockchains, a powerful tool designed to help ensure integrity of data in a linear fashion. Blockchains have come a long way, offering potential benefits to many sectors including financial, health, data, trust, contracting, and more. In this paper, we will discuss an open standard for defining blockchains for use in storing immutable data permanently without requiring any use of finances to be involved. Advances like Arweave, IPFS, and Filecoin have created a market for these type of technologies. In opposition to requiring an incentive to store data, this paper offers a standard for defining blockchains to store data using simple proof-of-work and proof-of-history.

We introduce the **Open-Immutable-Storage-Solution Standard (OISS-STD)** as the standaridzed methodology of storing data in a decentralized manner that remains immutable, stores pieces of the data in 256kb segments or lower blobs, does not duplicate data, and remains an open standard for storing/retrieving data with high-integrity without censorship. It has several versions that can be implemented and should remain simple at its root, being easy to implement anywhere. It also provides timestamping to the data using Proof-of-History (PoH), a consensus mechanism that measures using hash functions. It uses proof-of-work for uploading data to the chain and has u4, u8, and u16, sizes, making it easier to find the data on the chain by hash, allowing one to download a full blockchain containing only pieces that are hashes using a certain prefix of numbers.

## 2. Standard OISS

We introduce the standard **OISS**, the standard method of storing data using the following parameters:

**Number of Blockchains:** 256 (00-FF)
**Byte Size:** u8
---
**Hash Function:** BLAKE3
**PoW:**
---
**Blob Size:** 256kb (encoded in Base64)
**Mini-Blob Size:** 16kb (encoded in Base58)
