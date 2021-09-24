# Personal collection of EAR notifications

The United States has Encryption and Export Administration Regulations (EAR). 

Publicly available source code is not subject to EAR, once an email notification is sent to `crypt@bis.doc.gov` and to `enc@nsa.gov`.

A more in-depth discussion is from [this article](https://www.eff.org/deeplinks/2019/08/us-export-controls-and-published-encryption-source-code-explained).

### Contents

The repository contains a number of notices for open-source projects:

| Repository | Notice | 
| ---------- | -------- |
| The ElGamal Encryption Library from Ristretto [\[link\]](https://github.com/oblivious-file-sharing/libristretto-elgamal) | [2020-06-22-libristretto-elgamal.md](./2020-06-22-libristretto-elgamal.md) |
| The Paillier Encryption Library with Constant-Time Decryption [\[link\]](https://github.com/oblivious-file-sharing/libpaillier-with-constant-time-dec) | [2020-06-22-libpaillier-with-constant-time-dec.md](./2020-06-22-libpaillier-with-constant-time-dec.md) |
| The Circuit Collections for TLS-in-SMPC [\[link\]](https://github.com/n-for-1-auth/circuits) | [2021-04-05-n-for-1-auth-circuits.md](./2021-04-05-n-for-1-auth-circuits.md) |
| The EMP-ZK fork for prime p=2^{62}-2^{16}+1 [\[link\]](https://github.com/ucb-holmes/emp-zk) | [2021-09-23-ucb-holmes-emp-zk.md](./2021-09-23-ucb-holmes-emp-zk.md) |

### Update since 3/29/2021

The Bureau of Industry and Security has modified the EAR notification rules, as shown in [this Federal Register's document](https://www.federalregister.gov/documents/2021/03/29/2021-05481/export-administration-regulations-implementation-of-wassenaar-arrangement-2019-plenary-decisions).

Now, only "non-standard cryptography" needs to be reported, as defined as follows:

```
Means any implementation of “cryptography” involving the incorporation or use of proprietary or unpublished cryptographic functionality, including encryption algorithms or protocols that have not been adopted or approved by a duly recognized international standards body (e.g., IEEE, IETF, ISO, ITU, ETSI, 3GPP, TIA, and GSMA) and have not otherwise been published.
```

