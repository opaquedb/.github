# OpaqueDB

**Run SQL over encrypted data without revealing the query.**

A client encrypts the value it is searching for. The server runs the query over encrypted data and returns an encrypted result only the client can decrypt. The operator never sees the query value or the key.

Built on Microsoft SEAL (BFV). Privacy rests on Ring-LWE, a lattice assumption with no known quantum attack.
