# PublicKeyCryptography

Welcome to the PublicKeyCryptography repository! This repository is part of the Alchemy Ethereum Developer Bootcamp and contains practical exercises that demonstrate the basics of public key cryptography, specifically tailored for Ethereum blockchain development.

## Repository Contents

### Scripts Overview

- **hashMessage.js**: Demonstrates how to hash messages using Keccak-256. This script is essential for creating a fixed-size hash from any input message, using the primary hashing algorithm of Ethereum.

- **signMessage.js**: Provides functionality to sign messages. This script is critical for generating cryptographic signatures that prove ownership of a message or transaction, using a private key.

- **recoverKey.js**: Used for recovering a public key from a signature. This allows the identification of the signer's public key from just their signature and the original message, which is crucial for verifying the authenticity of a signature without needing the signer to separately provide their public key.

- **getAddress.js**: Generates an Ethereum address from a public key. This is fundamental for creating addresses that can be used to receive and send transactions on the Ethereum network.

- **test.js**: Includes test cases for all the functionalities provided by the scripts. It ensures that each function performs as expected, demonstrating the utility of each script through practical applications.

### Testing

The `test.js` script validates the functionality of the other scripts by running predefined test cases that simulate real-world usage of hashing, signing messages, recovering keys, and generating Ethereum addresses.

## Getting Started

To get started with the PublicKeyCryptography repository, clone the repository and install the necessary dependencies. You can then run the test script to see how each part of the public key cryptography process works in an Ethereum context.

This repository serves as an educational toolkit for understanding and implementing public key cryptography in blockchain development, providing hands-on experience with key concepts that underpin security and functionality in the Ethereum ecosystem.
