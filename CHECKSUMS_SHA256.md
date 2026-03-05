# PFIP Protocol File Integrity Verification

This document records SHA256 checksums and content identifiers for core PFIP protocol specification files.

These values allow independent verification of file integrity across distributed systems and storage networks.

---

# Protocol Specification Files

## Core Specification (JSON)

File Path  
/spec/pfip-v1.2-core-specification.json

SHA256  
5bbbe6b1c5dafa06a5e1b4f8f0f3eb205b5cb4d25e56c82872a0991a7b1238c0

---

## Core Specification (Markdown)

File Path  
/spec/pfip-v1.2-core-specification.md

SHA256  
5bbbe6b1c5dafa06a5e1b4f8f0f3eb205b5cb4d25e56c82872a0991a7b1238c0

Note  
The JSON and Markdown versions contain identical protocol content.  
Therefore the SHA256 checksum is identical.

---

## Protocol Specification (PDF)

File Path  
/spec/pfip-core-protocol-specification-v1.2.pdf

SHA256  
aff4b9c42b494b3747bc4d2332063f1a942043385cacacbdc726e2b2b233759c

IPFS CID  
bafybeib7ana6hpid3gqwalzvj52to4zr6uhvk6zb633sy3opdjowaxllky

---

# Verification Example

File integrity can be verified using standard SHA256 tools.

Example:

# shasum -a 256 pfip-v1.2-core-specification.md


The resulting hash should match the value listed in this document.

---

# Verification Purpose

These checksums support:

- file integrity verification
- reproducible protocol distribution
- distributed storage verification
- independent protocol validation

---

# Notice

Hashes and content identifiers are provided solely for integrity verification and content-addressed referencing.

They do not define governance authority, protocol interpretation rules, or system identity.
