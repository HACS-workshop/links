# Links to HACS-related code

[CertiKOS](http://flint.cs.yale.edu/certikos/): kernel with clean-slate design with end-to-end guarantees on extensibility, security, and resilience

[seL4](https://sel4.systems/) is an L4 kernel verified with Isabelle/HOL.

[hacl&ast;](https://github.com/mitls/hacl-star): an F&ast; verified cryptographic library.

WIP: [applying SAW to OpenSSL](https://github.com/benlaurie/openssl/tree/saw/proof).

[CompCert](http://compcert.inria.fr/) A verified C compiler, written in Coq.

[VST](http://vst.cs.princeton.edu/) allows proofs about C code in the CompCert semantics that then carry down to the generated assembly code, if built with CompCert.

[Fiat](https://github.com/mit-plv/fiat) is written in Coq and contains a formalisation of (currently) X25519 and Ed25519. It generates imperitative by using Coq notation directives that is suitable for, say, pasting into a C file.
