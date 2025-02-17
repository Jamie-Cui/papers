# awesome-secure-computation [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This repo is a paper summary for cryptography-based secure computation papers (I prefer published papers 😛), including topics like [*Multiparty Computation*](https://en.wikipedia.org/wiki/Secure_multi-party_computation), [*Homomorphic Encryption (or Lattice)*](https://en.wikipedia.org/wiki/Homomorphic_encryption) and [*Differential Privacy*](https://en.wikipedia.org/wiki/Differential_privacy). If you are looking for hardware solutions like Trusted Platform Module (TPM), or Trusted Execution Environment (TEE), I'm sorry this repo is not what you're looking for :(.

Here's a good place to ask questions about cryptography/cryptanalysis, or answering one (if you are capable of doing so): [https://crypto.stackexchange.com/](https://crypto.stackexchange.com/), and finding papers [Cryptology ePrint Archive](https://eprint.iacr.org/).

**Useful Links**:

- [Security Conferences Ranking](http://faculty.cs.tamu.edu/guofei/sec_conf_stat.htm) (By Prof. Guofei Gu)
- [Security and Privacy Conference Deadlines](https://sec-deadlines.github.io/)
- [Crypto21: Mentoring Videos about how to do research in cryptography](https://mentor-crypto-2021.github.io/)

**Texbooks**:

- A Pragmatic Introduction to Secure Multi-Party Computation  
  *David Evans, Vladimir Kolesnikov, and Mike Rosulek*  
  [eprint avaliable](https://www.cs.virginia.edu/~evans/pragmaticmpc/pragmaticmpc.pdf) 
- Foundations of Cryptography  
  *Oded Goldreich*  
  [author's notes](https://www.wisdom.weizmann.ac.il/~oded/foc.html)
- Introduction to Modern Cryptography  
  *Jonathan Katz and Yehuda Lindell*  
  [author's notes](http://www.cs.umd.edu/~jkatz/imc.html)

**Open-source Tools (mostly in C++)**:
- [[yacl-r]](https://github.com/Jamie-Cui/yacl-r): OT(e), OPRF, VOLE, PSI (DISCLAIMER: I participant in the develop of yacl and yacl-r)
- [[emp-toolkit]](https://github.com/emp-toolkit): OT(e), ZKP, MPC
- [[libOTe]](https://github.com/osu-crypto/libOTe): OT(e), VOLE
- [[libPSI]](https://github.com/osu-crypto/libPSI): PSI
- [[MP-SPDZ]](https://github.com/mc2-project/MP-SPDZ): Generic MPC

## Contents

- [MPC](mpc.md)
  * [Summaries and Talks](mpc.md/#summaries-and-talks)
  * [OT](mpc.md/#ot)
  * [OLE/vOLE](mpc.md/#vole)
  * [OPRF and PSI](mpc.md/#oprf-and-psi)
  * [PIR](mpc.md/#pir)
  * [PFE](mpc.md/#pfe)
  * [FSS](mpc.md/#fss)
  * [Semi-honest MPC](mpc.md/#semi-honest-mpc)
  * [Malicious MPC](mpc.md/#malicious-mpc)
- [ZKP](zkp.md)  
  (Big shout out to [Austin Wu](https://github.com/xfap)!)
  - [Survey \& Tutorial](zkp.md/#survey--tutorial)
  - [Milestones](zkp.md/#milestones)
  - [Specific ZKP](zkp.md/#specific-zkp)
    - [Traditional \& simple relations (over logarithm)](zkp.md/#traditional--simple-relations-over-logarithm)
    - [Membership(Range) Proof](zkp.md/#membershiprange-proof)
  - [General purpose ZKP](zkp.md/#general-purpose-zkp)
    - [Frameworks](zkp.md/#frameworks)
    - [with SRS(Structured Reference String), including ZKSNARK](zkp.md/#with-srsstructured-reference-string-including-zksnark)
    - [with updatable universal SRS](zkp.md/#with-updatable-universal-srs)
    - [with URS(Uniform Reference String), including ZKSTARK](zkp.md/#with-ursuniform-reference-string-including-zkstark)
      - [DL-based](zkp.md/#dl-based)
      - [MPC-in-the-head-based](zkp.md/#mpc-in-the-head-based)
      - [VOLE-based (Commit-and-prove type)](zkp.md/#vole-based-commit-and-prove-type)
  - [Applications on ZKP systems](zkp.md/#applications-on-zkp-systems)
    - [For Machine Learning(Federated Learning)](zkp.md/#for-machine-learningfederated-learning)
    - [For Web3(Authentication)](zkp.md/#for-web3authentication)
    - [For Blockchains](zkp.md/#for-blockchains)
    - [Signature from ZKP](zkp.md/#signature-from-zkp)
  - [ZKP Standard Efforts](zkp.md/#zkp-standard-efforts)
- TODO [Lattice]

## License

see [LICENSE](LICENSE).
