# Substitution Cipher Implementation

## Overview

This project implements a Substitution Cipher in Java, providing a secure method for encrypting and decrypting messages. The cipher replaces each character in the message with another character from a randomly shuffled list.

## Introduction

The Substitution Cipher is a classic cryptographic technique that involves replacing each character in a message with a different character, creating an encrypted version of the original message. This implementation employs Java to provide a secure and efficient encryption and decryption process.

## Key Features

- Generation of unshuffled and shuffled character lists.
- Utilization of Java's Random class for added randomness in character shuffling.
- Comprehensive testing to ensure accurate and reliable encryption and decryption.
- Extensible framework for incorporating additional cipher algorithms.

## Installation

To use this Substitution Cipher implementation, follow these steps:

1. Clone the repository to your local machine using Git:
`git clone https://github.com/your-username/substitution-cipher.git`

2. Open the project in your preferred Java IDE.

3. Compile and run the code to start using the Substitution Cipher.

## Usage

### Encryption

To encrypt a message using the Substitution Cipher, follow these steps:

1. Instantiate a `SubstitutionCipher` object with a specified key.

2. Use the `encrypt()` method, passing the original message as a list of characters.

3. The method will return a list of characters representing the encrypted message.

### Decryption

To decrypt an encrypted message, follow these steps:

1. Instantiate a `SubstitutionCipher` object with the same key used for encryption.

2. Use the `decrypt()` method, passing the encrypted message as a list of characters.

3. The method will return a list of characters representing the original message.

## Cipher Classes

The project includes a `Cipher` class that serves as a framework for various cipher algorithms. Currently, it supports the Substitution Cipher, but additional cipher algorithms can be easily integrated by extending the `Cipher` class.

## Contributing

If you'd like to contribute to the development of this project, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch for your contributions.
3. Make your changes and commit them with clear, concise commit messages.
4. Push your changes to your forked repository.
5. Create a pull request to submit your contributions for review.

