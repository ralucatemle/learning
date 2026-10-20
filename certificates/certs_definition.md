What is a software certificate?
A digital certificate is an electronic document that binds an identity to a public key. It is usually encoded in the X.509 format.
Think of it as an identity document for a computer, service, application, or sometimes a person.

Certificate
“This public key belongs to api.example.com, according to the certificate issuer.”

A typical certificate contains
- Subject / Subject Alternative Name (SAN): the identity or identities it represents.
- Public key: used in cryptographic protocols.
- Issuer: the CA (Certificate Authority) that signed it.
- Validity period: when the certificate becomes valid and expires.
- Key usage / Extended Key Usage: what the certificate is permitted to be used for.
- Signature: evidence that the issuer signed the certificate contents.
