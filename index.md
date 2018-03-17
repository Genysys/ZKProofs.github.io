# Science!

![](/images/underconstruction/HeHeartlandPark5787imagesConstruction1.gif)
[![](/images/underconstruction/ArArea51Station9771rulersconstructionconstruction_wide.gif)](https://textfiles.com/underconstruction/)
[![](/images/underconstruction/ArArea51Shadowlands2297ST-underconstruction_anm.gif)](https://en.wikipedia.org/wiki/History_of_cryptography#Modern_cryptography)

## What is a zero-knowledge proof?

- [Zero Knowledge Proofs: An illustrated primer](https://blog.cryptographyengineering.com/2014/11/27/zero-knowledge-proofs-illustrated-primer/)
- [What are zk-SNARKs?](https://z.cash/technology/zksnarks.html)

## Zero-knowledge proving systems

- [Pinocchio [PGHR13]](https://eprint.iacr.org/2013/279.pdf)
- [[BCTV14b]](https://eprint.iacr.org/2014/595)
- [[CTV15]](https://eprint.iacr.org/2015/377)
- [ZKBoo [GMO16]](https://eprint.iacr.org/2016/163.pdf)
- [[Groth16]](https://eprint.iacr.org/2016/260.pdf)
- [Bootle proofs [BCC+16]](https://eprint.iacr.org/2016/263.pdf)
- [ZKB++ / Picnic [CDGORRSZ17]](https://eprint.iacr.org/2017/279.pdf)
- [Ligero [AHIV17]](https://acmccs.github.io/papers/p2087-amesA.pdf)
- [Hyrax [WTSTW17]](https://eprint.iacr.org/2017/1132.pdf)
- [zk-STARKs [BBHR18]](https://eprint.iacr.org/2018/046)

## Implementations

- [libsnark](https://github.com/scipr-lab/libsnark)
  - Pinocchio (implements [[BCTV14a]](http://eprint.iacr.org/2013/879) approach)
  - [BCTV14b]
  - [CTV15]
- [bellman](https://github.com/ebfull/bellman/)
  - [Groth16]
- [ZKBoo](https://github.com/Sobuno/ZKBoo)
- Bootle proofs
  - [BulletProofLib](https://github.com/bbuenz/BulletProofLib) (implements [Bulletproofs [BBBPWM17]](https://web.stanford.edu/~buenz/pubs/bulletproofs.pdf) approach)
  - [secp256k1-zkp (experimental)](https://github.com/ElementsProject/secp256k1-zkp/pull/16) (implements [Bulletproofs [BBBPWM17]](https://web.stanford.edu/~buenz/pubs/bulletproofs.pdf) approach)
- Picnic
  - [Reference implementation](https://github.com/Microsoft/Picnic)
  - [Optimized implementation](https://github.com/IAIK/Picnic)
- [libSTARK](https://github.com/elibensasson/libSTARK)
  - zk-STARKs
- [emmy](https://github.com/xlab-si/emmy)
  - ZKP primitives for [Camenisch-Lysyanskaya anonymous credentials](https://eprint.iacr.org/2001/019.pdf)
  - Camenisch-Lysyanskaya anonymous credentials (work in progress)
  - client-server (prover-verifier) communication based on Protobuffers and gRPC
  - TODO: pairing-based schemes for anonymous credentials

## So are they fast yet?

Stay tuned! 😁

## I'd like to add another proving system / write a short explainer / remove those awful 90's images

You can make a pull request [here](https://github.com/ZKProofs/ZKProofs.github.io)!
