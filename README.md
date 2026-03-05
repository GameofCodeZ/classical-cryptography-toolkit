# Classical Cryptography Toolkit

## Overview

This project implements several classical cryptographic algorithms and basic cryptanalysis techniques using Python. Classical cryptography forms the foundation of modern encryption systems and helps in understanding the evolution of secure communication methods. In this project, multiple classical ciphers are implemented along with statistical analysis tools to study the properties of encrypted text.

The goal of this project is to demonstrate how encryption works and how statistical properties of language can be used to analyze and potentially break simple encryption schemes.

---

## Implemented Algorithms

The following classical encryption algorithms are implemented:

### Caesar Cipher
A substitution cipher where each letter of the plaintext is shifted by a fixed number of positions in the alphabet.

### Vigenère Cipher
A polyalphabetic cipher that uses a keyword to determine the shift applied to each letter of the plaintext.

### XOR Cipher
A simple encryption method where each character of the plaintext is XORed with a key value.

---

## Cryptanalysis

The project also includes basic cryptanalysis techniques such as:

### Frequency Analysis
Frequency analysis examines how often each letter appears in the ciphertext. Since natural languages have characteristic letter frequency distributions, this information can be used to analyze and break simple substitution ciphers.

The project visualizes letter frequencies using graphs to demonstrate how statistical patterns appear in encrypted messages.

---

## Technologies Used

- Python
- Google Colab / Jupyter Notebook
- Matplotlib for visualization

---

## Example Workflow

1. Input plaintext message
2. Encrypt the message using a selected cipher
3. Decrypt the ciphertext using the correct key
4. Perform frequency analysis on the encrypted text
5. Visualize the letter distribution

---

## Conclusion

This project demonstrates the implementation of classical encryption techniques and basic cryptanalysis methods. Although classical ciphers are no longer secure for modern applications, studying them provides important insights into the principles of cryptography and the development of modern encryption systems.

---


- Creating an interactive cryptography toolkit

---
