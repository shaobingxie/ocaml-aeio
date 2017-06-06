aeio — Asynchronous effect-based IO
-------------------------------------------------------------------------------
%%VERSION%%

aeio is TODO

aeio is distributed under the ISC license.

Homepage: https://github.com/kayceesrk/aeio  

## Installation

First [install multicore OCaml](https://github.com/ocamllabs/multicore-opam#install-multicore-ocaml). Then, aeio can be installed with `opam`:

    opam install aeio

If you don't use `opam` consult the [`opam`](opam) file for build
instructions.

## Documentation

The documentation and API reference is automatically generated by from
the source interfaces. It can be consulted [online][doc].

[doc]: https://kayceesrk.github.io/ocaml-aeio/doc

## Sample programs

If you installed aeio with `opam` sample programs are located in
the directory `opam config var aeio:doc`.

In the distribution sample programs and tests are located in the
[`test`](test) directory of the distribution. They can be built and run
with:

    topkg build --tests true && topkg test 
