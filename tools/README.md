# Tools related to HACS

## Formal Methods

[AutoG&P](https://autognp.github.io): tool for performing highly automated game-hopping proofs for pairing-based cryptographic primitives

[CBMC](https://github.com/diffblue/cbmc): a bounded model checker for C and Java

[CompCert](http://compcert.inria.fr/) A verified C compiler, written in Coq


The [Coq](https://coq.inria.fr/) Proof Assistant

*While you can install Coq with `apt-get install coqide` or executing the binary/dmg if you use Windows. The best way to install coq is to use [opam](https://opam.ocaml.org/)*:

```
sudo apt-get install gcc
sudo apt-get install opam
opam init
opam switch coq --alias-of 4.04.0
opam install coq
opam install coqide
opam repo add coq-released https://coq.inria.fr/opam/released
opam install coq-mathcomp-ssreflect
opam install menhir
```

[Crucible](https://github.com/GaloisInc/crucible): a language-agnostic library for performing forward symbolic execution of imperative progams

[Cryptol](http://cryptol.net/): a domain-specific language for specifying cryptographic algorithms

[EasyCrypt](https://www.easycrypt.info/trac/): a toolset for reasoning about relational properties of probabilistic computations with adversarial code

[Entroposcope](http://entroposcope.verifythis.org): a tool for finding entropy loss bugs in PRNGs

[F&ast;](https://www.fstar-lang.org/): an ML-like language with a type system for program verification

[Fiat Crypto](https://github.com/mit-plv/fiat-crypto/): automatic derivation of fast crypto-primitive code (for now just ECC) from specifications in Coq, generating proofs along the way

[Frama-C](http://frama-c.com/): an extensible and collaborative platform dedicated to source-code analysis of C software

[gfverif](http://gfverif.cryptojedi.org): fast and easy verification of finite-field arithmetic

[Ivory](http://ivorylang.org/): an eDSL for safe systems programming. You can think of Ivory as a safer C, embedded in Haskell

[Kami](http://plv.csail.mit.edu/kami/): tool for verified hardware design (ISA->RTL)

[KeY](http://www.key-project.org/): a deductive verifier of functional correctness of Java programs (wrt properties annotated in JML)

[Kremlin](https://github.com/FStarLang/kremlin): translate a subset of F&ast; to C

[Software Analysis Workbench (SAW)](https://saw.galois.com/)

[Verifast](https://people.cs.kuleuven.be/~bart.jacobs/verifast/): a verifier for single-threaded and multithreaded C and Java programs annotated with preconditions and postconditions written in separation logic

[Verified Software Toolchain (VST)](http://deepspec.org/research/VST/): software toolchain which includes static analyzers to check assertions about your program; optimizing compilers to translate your program to machine language; operating systems and libraries to supply context for your program

[ZooCrypt](https://www.easycrypt.info/trac/wiki/ZooCrypt): fully automated analysis of padding-based encryption

## Fuzzing

[AFL](http://lcamtuf.coredump.cx/afl/): a fuzzer
 
[libFuzzer](http://libfuzzer.info): a fuzzer
 
[OSS-Fuzz](https://github.com/google/oss-fuzz): fuzzing service for open-source software
