# Cybersecurity-CTF-Labs-Collection-Cryptanalysis-Hash-Forensics-Classical-Ciphers
A curated, searchable index of hands-on CTF labs covering hash identification, digest analysis, password breach triage, classical cipher breaking (Vigenère, Caesar, historical encryption), and cryptographic artifact hunting from Learn SecByte.
# Cryptanalysis, Hash Forensics & Classical Ciphers CTF Labs Collection

A structured, searchable index of hands-on cybersecurity labs focusing on Cryptographic Hash Forensics & Digest Analysis (Digest Analysis Workshop, Password Breach Investigation, Hash Identification, Digest Trace Tracking, Operation Hash Crack, Digital Fingerprinting & Identity Clues, Hash Hunting) and Classical Cryptanalysis & Historical Ciphers (The Cipher Collector, Vigenère Cipher Investigation, Cracking King's Messages, Forgotten Encryption Methods, Cipher Museum Heist) hosted on Learn SecByte.

This collection is designed for cryptanalysts, forensic investigators, SOC analysts, penetration testers, and security researchers seeking practical experience in hash algorithm triage, offline credential recovery, and classical cipher decryption.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
  - [Hash Forensics, Digest Analysis & Credential Cracking](#hash-forensics-digest-analysis--credential-cracking)
  - [Classical Cryptanalysis & Historical Ciphers](#classical-cryptanalysis--historical-ciphers)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Cryptographic digests and cipher systems form fundamental pillars of security, but misconfigurations or obsolete implementations expose critical assets to discovery. Understanding how to identify hash types (MD5, SHA-1, SHA-256, NTLM, bcrypt), analyze digest chains, and perform dictionary or rule-based attacks is essential for assessing password security and triaging breach leaks. Simultaneously, studying classical ciphers—such as substitution/transposition variations, Vigenère polyalphabetic systems, and historical encryption schemes—builds core intuition for frequency analysis, key length estimation, and modern cryptanalysis.

This repository organizes hands-on hash forensics and classical cryptanalysis labs from Learn SecByte into structured learning paths covering cryptographic artifact recovery and cipher breaking.

---

## Lab Collection & Index

| Lab Title | Domain Focus | Primary Category | Access Link |
| :--- | :--- | :--- | :--- |
| **Digest Analysis Workshop** | Cryptography | Hashing Mechanics, Entropy & Verification | [Access Lab](https://learn.secbyte.org/ctf/digest-analysis-workshop) |
| **Password Breach Investigation** | DFIR / Hash | Credential Dump Analysis & Triage | [Access Lab](https://learn.secbyte.org/ctf/the-password-breach-investigation) |
| **Hash Identification Lab** | Hash Forensics | Pattern Recognition & Hash Type Detection | [Access Lab](https://learn.secbyte.org/ctf/hash-identification-lab) |
| **Following the Digests** | DFIR / Crypto | Trace Chains & Digest Evidence Tracking | [Access Lab](https://learn.secbyte.org/ctf/following-the-digests) |
| **Operation Hash Crack** | Cracking / Hash | Dictionary Attacks, Rules & Salt Exhaustion | [Access Lab](https://learn.secbyte.org/ctf/operation-hash-crack) |
| **Digital Fingerprints** | DFIR / Identity | Traces, Artifacts & Identity Clues | [Access Lab](https://learn.secbyte.org/ctf/digital-fingerprints-traces-artifacts-identity-clues) |
| **The Hash Hunter** | DFIR / Hash | Hunting Malicious & Compromised Hashes | [Access Lab](https://learn.secbyte.org/ctf/the-hash-hunter) |
| **The Cipher Collector** | Cryptanalysis | Cipher Classification & Payload Extraction | [Access Lab](https://learn.secbyte.org/ctf/the-cipher-collector) |
| **The Vigenère Investigation** | Cryptanalysis | Polyalphabetic Decryption & Index of Coincidence | [Access Lab](https://learn.secbyte.org/ctf/the-vigenere-investigation) |
| **Cracking the King's Messages** | Cryptanalysis | Monoalphabetic Substitution & Frequency Analysis | [Access Lab](https://learn.secbyte.org/ctf/cracking-the-kings-messages) |
| **Forgotten Encryption Methods** | Cryptanalysis | Historical Ciphers, Transposition & Obsolete Codes | [Access Lab](https://learn.secbyte.org/ctf/the-forgotten-encryption-methods) |
| **Cipher Museum Heist** | Cryptanalysis | Multi-Stage Classical Decryption Challenge | [Access Lab](https://learn.secbyte.org/ctf/cipher-museum-heist) |

---

## Categories

### Hash Forensics, Digest Analysis & Credential Cracking
Hands-on CTF labs detailing hash identification techniques, password leak triage, digest tracing, and rule-based cracking:

* **Digest Analysis Workshop:** Evaluating cryptographic hash collision risks, verifying payload integrity, and calculating digest entropy across different algorithms.
  * Lab Link: https://learn.secbyte.org/ctf/digest-analysis-workshop
* **Hash Identification Lab & The Hash Hunter:** Differentiating raw hash structures (MD5, SHA-1, SHA-256, NTLM, MySQL, bcrypt), using signature patterns, and hunting compromised hash artifacts in system dumps.
  * Lab Links:
    * Hash Identification Lab: https://learn.secbyte.org/ctf/hash-identification-lab
    * The Hash Hunter: https://learn.secbyte.org/ctf/the-hash-hunter
* **Password Breach Investigation & Following the Digests:** Triaging leaked password databases, tracking digest chains across logs, and mapping compromised user accounts.
  * Lab Links:
    * Password Breach Investigation: https://learn.secbyte.org/ctf/the-password-breach-investigation
    * Following the Digests: https://learn.secbyte.org/ctf/following-the-digests
* **Operation Hash Crack:** Executing GPU/CPU password recovery using Hashcat and John the Ripper, constructing custom mutation rules, and analyzing salted hashes.
  * Lab Link: https://learn.secbyte.org/ctf/operation-hash-crack
* **Digital Fingerprints (Traces & Artifacts):** Correlating digital file hashes, fuzzy hashing (`ssdeep`), and system artifact signatures to identify user activity and malware footprints.
  * Lab Link: https://learn.secbyte.org/ctf/digital-fingerprints-traces-artifacts-identity-clues

### Classical Cryptanalysis & Historical Ciphers
Practical security labs focused on monoalphabetic substitution, polyalphabetic Vigenère decryption, transposition grids, and historical cipher breaking:

* **Cracking the King's Messages:** Performing frequency analysis on monoalphabetic substitution ciphers and breaking historical Caesar/Shift variations.
  * Lab Link: https://learn.secbyte.org/ctf/cracking-the-kings-messages
* **The Vigenère Investigation:** Utilizing Kasiski examination, the Index of Coincidence (IoC), and key-length estimation to break polyalphabetic Vigenère ciphers.
  * Lab Link: https://learn.secbyte.org/ctf/the-vigenere-investigation
* **Forgotten Encryption Methods:** Analyzing historical cipher techniques (Playfair, Rail Fence, Bifid, Columnar Transposition) and identifying forgotten cryptographic protocols.
  * Lab Link: https://learn.secbyte.org/ctf/the-forgotten-encryption-methods
* **The Cipher Collector & Cipher Museum Heist:** Dissecting unknown ciphertexts, categorizing encryption styles, and solving multi-stage cryptanalysis puzzles in a scenario-driven environment.
  * Lab Links:
    * The Cipher Collector: https://learn.secbyte.org/ctf/the-cipher-collector
    * Cipher Museum Heist: https://learn.secbyte.org/ctf/cipher-museum-heist

---

## Learning Path

Follow this structured roadmap to master hash forensics and classical cryptanalysis:

1. **Hash Identification & Digest Mechanics**
   - Study Digest Analysis Workshop and Hash Identification Lab to identify hash structures.
   - Trace digest evidence across logs using Following the Digests and Digital Fingerprints.
2. **Credential Breach Triage & Password Cracking**
   - Triage credential dumps in Password Breach Investigation.
   - Master Hashcat/John the Ripper rule generation and wordlist mutations in Operation Hash Crack.
3. **Classical Substitution & Transposition Decryption**
   - Apply frequency analysis in Cracking the King's Messages.
   - Master polyalphabetic cryptanalysis using Index of Coincidence in The Vigenère Investigation.
4. **Historical Cipher Breaking & Scenario Challenges**
   - Decrypt complex historical ciphers in Forgotten Encryption Methods.
   - Solve multi-layered cryptanalysis challenges in The Cipher Collector and Cipher Museum Heist.

---

## How to Use the Labs

1. Select a practice scenario from the index table or category breakdown above.
2. Launch the target lab environment directly on Learn SecByte using the provided access link.
3. Complete hands-on tasks using cryptanalysis and hash recovery tools (CyberChef, Hashcat, John the Ripper, `hash-identifier`, `ssdeep`, Python crypto scripts, and dcode.fr analysis tools).
4. Review post-lab writeups, hashing defense benchmarks, and cipher analysis guidelines to apply in production enterprise environments.

---

## Disclaimer

This repository is strictly intended for educational research, authorized cryptographic auditing, and digital forensics training. All concepts, tools, and lab environments are provided to help cybersecurity practitioners build practical expertise and defend enterprise infrastructure. Unsanctioned password cracking, unauthorized decryption of external data, or malicious use of recovered credentials are strictly illegal.
