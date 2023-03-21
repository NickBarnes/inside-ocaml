# Inside OCaml
## Documentation of the OCaml implementation

This repo contains documentation of the [OCaml](https://ocaml.org/)
[language implementation](https://github.com/ocaml/ocaml). It may also
grow to include notes on other parts of the broader OCaml ecosystem,
such as [opam](https://opam.ocaml.org/),
[dune](https://github.com/ocaml/dune),
[odoc](https://ocaml.github.io/odoc/),
[OCurrent](https://github.com/ocurrent/ocurrent), and so on.

I started this repo after starting work at
[Tarides](https://tarides.com/) in the OCaml compiler backend group,
with particular focus on the garbage collector and related systems. I
discovered there was very little structured documentation about the
system, so I started writing documentation for my own use. Now I am
starting a repo to contain and structure those notes. So there is
likely to be a focus on low-level aspects, at least at the outset, and
the repo is likely to grow in an ad-hoc way depending on what I'm
looking at.

The primary intended readership is primarily OCaml developers and
contributors. Hopefully this repo would also be of use to anyone
interested in language compilers and runtimes.

Forks and pull requests are absolutely welcome. The license is LGPL
v2.1 for maximum compatibility with [the ocaml/ocaml repo](https://github.com/ocaml/ocaml).

## Overview

- TODO: bytecode, native code, and runtime;
- TODO: essence of heaps and stacks;
- TODO: 4 vs 5; about Multicore OCaml.

## Object Layout

- TODO: Paste in my lengthy notes about mlvalues etc here.

## Stacks (and Exceptions?)

- TODO: ABI incompatibility;
- TODO: C stack vs Caml stack;
- TODO: exception handler records;
- TODO: exception propagation;
- TODO: backtraces, frametables, debuginfo.
- TODO: calling convention, currying, de-currying.

## Domains, Threads, and Effects

- TODO: memory model;
- TODO: systhreads;
- TODO: domains;
- TODO: backup threads;
- TODO: effect handling.

## The Heap and Garbage Collector

- TODO: Minor heap, pointer-bump allocation;
- TODO: major heap(s);
- TODO: GC phases;
- TODO: finalisation;
- TODO: weakness.

## Source Code and Build System

- TODO: Seb's braindump comes here.

## Compiler Structure

- TODO: phases;
- TODO: files;

## Debugging OCaml

- TODO: gdb, rr, lldb. gdb-macros (which hopefully I will have updated by
  the time I write this part).