# ShannonCipherPoC

A concise Python Proof-of-Concept (PoC) demonstrating fundamental principles of cryptographic logic inspired by Claude Shannon's work.

This repository contains a basic implementation illustrating concepts like:

* **Confusion:** Obscuring the relationship between the key and ciphertext (through a simple Substitution Box - S-Box).
* **Diffusion:** Spreading the influence of plaintext bits across the ciphertext (through a basic Permutation).
* **Iterative Block Cipher Structure:** Processing data in fixed-size blocks through multiple rounds.
* **Basic Key Schedule:** Generating round keys from a main key.

**Warning:** This is an educational PoC **ONLY**. It is **NOT** cryptographically secure and should **NOT** be used for any real-world security applications.

**Disclaimer:** This code is for learning purposes only and lacks the robustness and security features of production-ready cryptographic libraries.

**Further Exploration:**

This PoC can be a starting point to understand the foundational ideas behind modern cryptography and the significance of Shannon's contributions to the field.