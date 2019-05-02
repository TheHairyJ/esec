# eSecurity Open Book Exam #2

## Table of Contents
 1. [Digital Certificates](https://github.com/TheHairyJ/esec/blob/master/esecurity.md#digital-certificates)

## Digital Certificates
### Learning Outlines
- Define how PKI is used to secure communications, and how digital certificates would be used in this.
- Understand the signing process involved within the trust infrastructrue.
- Understand the basics of the Code Signing Request (CSR).

### Sample Questions
-   Bob sends an encrypted message to Alice, and also sends his digital certificate to Alice to prove his identity. How does Alice prove that it is Bob who sent the message?
-   The core trust on the Internet is based around PKI (Public Key Infrastructure). Outline how digital certificates are used to provide a degree of trustworthiness.
-   Bob has just produced a key pair, in a Base-64 format, and now wants to send this to Alice. What advice would you give him on sending the key pair to Alice?
-   Bob sends an encrypted message to Alice, and also sends his digital certificate to Alice to prove his identity. How does Alice prove that it is Bob who sent the message?

___________________________________________

Student should mention that “Digital Certificate” is a digital document issued and digitally signed by the private key of a Certification Authority that binds the name of a subscriber to a public key.

Student should mention that the “Public Key Infrastructure” is a set of policies, processes, server platforms, software and workstations used for the purpose of administering certificates and public - private key pairs, including the ability to issue, maintain, and revoke public key certificates.

Public-key infrastructure (PKI) consists of the following components:
1. Digital certificates, 
2. Public-key cryptography, and 
3. Certificate authorities
The above components are integrated to provide a wide area network security infrastructure that is secure,
and widely used in todays Internet environment.


a. The main purpose of a PKI is to support distribution of public keys with authenticity. A PKI
binds public keys to named entities, and enables relying parties to verify this binding. A
specific public-key certificate is interpreted as: “Entity X owns public key K”
b. Respectively we have:
 Certification authorities (CA) create, issue and revoke certificates, maintain certificate
status information and issues CRLs, publish current certificates and CRLs and
maintain archives of status information.
 Registration authorities (RA) act as an interface between user and CA for public key
registration. The RA is trusted by the CA to verify the identity of the user and other
certificate contents.

How do Bitcoin Transactions Work?
https://www.bgmcrypto.com/bitcoin-transactions/


