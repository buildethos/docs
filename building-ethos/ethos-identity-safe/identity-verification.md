---
description: Verifying who you are without compromising what you know.
---

# Identity Verification

Digital Identity Verification is the process of confirming the authenticity of an online entity. Digital verification uses cryptography and mathematical proofs to establish trust.

## How Ethos Enables Robust Identity Verification:

* **Import and Integrate:** Begin by integrating your diverse digital profiles into the Ethos Identity Safe.
* **Encryption  & Unique Hashing:** For every imported profile, Ethos generates a unique cryptographic hash. This hash acts as a distinct identifier, proving the existence and ownership of a profile.
* **Zero-Knowledge Proofs:** Ethos allows you to authenticate your identity without exposing the underlying data. Third parties can validate that you have specific information without seeing the actual information itself.
* **Retrieval & Validation**: When verification is needed, the unique hash, combined with the user's private key stored locally, can be used to prove ownership. Enterprises or platforms requesting verification never access raw data directly, only the cryptographic proof of validity.

## Activity Diagram

<figure><img src="../../.gitbook/assets/ethos diagrams (3).png" alt=""><figcaption><p>ethos activity diagram</p></figcaption></figure>



