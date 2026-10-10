# OpenSSL Certificate Signing Request Lab

**Objective:** Generate and validate a Certificate Signing Request (CSR) using OpenSSL on Linux.

**Environment:** Kali Linux or Ubuntu Linux

**Tools:** OpenSSL, Linux terminal, SHA-256 utilities

**Tasks performed:**
1. Generated a 2048-bit RSA private key.
2. Created a Certificate Signing Request using OpenSSL.
3. Inspected the CSR subject and public key information.
4. Verified the CSR's self-signature.
5. Compared public key hashes to confirm the private key and CSR correspond.
6. Captured command output and documented the results.

**Expected outcome:** A valid CSR is generated, its signature verification succeeds, and the public key extracted from the CSR matches the public component of the private key.

**Security considerations:** The private key must remain confidential and must not be uploaded to public repositories. A CSR is a request for a certificate, not a signed certificate itself.

**Conclusion:** The lab demonstrates foundational Linux command-line skills, public key cryptography, certificate enrollment preparation, and technical evidence documentation.
