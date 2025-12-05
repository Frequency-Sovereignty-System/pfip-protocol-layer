# Protocol Layer — PFIP Interface Specification

The Protocol Layer defines the executable, machine-verifiable interface 
used to publish, reference, validate, and evolve components of the 
Frequency Sovereignty protocol stack.

This layer does *not* contain personal information, conceptual writing, 
or interpretive content. It serves strictly as a **technical interface 
and verification contract**.

---

## Core Responsibilities

The Protocol Layer provides:

- *Protocol versioning*
  Structured releases with immutable identifiers and hash-bound integrity.

- *Machine-readable licenses*
  JSON-based authorization terms allowing platforms to verify permitted
  and restricted uses.

- *Cross-platform compatibility*
  Ensures reproducible validation across ENS, IPFS, GitHub, and other
  verifiable environments.

- *Signature verification rules*
  Defines how root signatures, protocol signatures, and revocation
  signatures must be formatted and validated.

- *Anchor references*
  Provides links to immutable origin points stored in the Primary 
  Frequency Root.

- *Protocol governance boundaries*
  Specifies what the protocol can do, cannot do, and the extent of 
  machine-verifiable authority.

---

## What This Repository Contains

Only *technical, non-interpretive* materials:

- pfip.json — machine-readable protocol license  
- manifest.json — release manifest with hash anchors  
- schema/ — data structure definitions  
- validation/ — rules for verifying signatures and hashes  
- registry/ — protocol version registry  

No philosophical, conceptual, personal, or narrative content is included.

---

## Purpose of This Layer

This layer enables:

- Consistent protocol interpretation by machines  
- Safe integration by external systems  
- Clear legal and operational boundaries  
- Immutable reference points for future versions  

---

## Governance

This layer inherits final authority from the *Primary Frequency Root*, 
which provides the cryptographic origin and signature verification anchor.

Human interpretation, system strategy, or conceptual explanations do *not*
appear here. Only machine-verifiable protocol structures are published.
