# Secure Digital Wallet Using Homomorphic Encryption

## Overview
# Homomorphic Encryption Digital Wallet
A privacy-preserving financial transaction system implementing Paillier Homomorphic Encryption to perform secure computations on encrypted balances.

## Key Features
- Encrypted balance storage
- Secure transaction validation
- Homomorphic addition on ciphertext
- Modular client-server architecture

## Architecture
Explain auth.py, server.py, client.py etc.


## How It Works

1. Key generation using Paillier cryptosystem
2. Client encrypts transaction amounts
3. Server performs homomorphic addition on ciphertext
4. Decryption reveals updated balance

## Tech Stack
- Python
- Paillier Homomorphic Encryption

## How to Run
python server.py
python client.py
