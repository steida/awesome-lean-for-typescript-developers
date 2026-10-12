# Awesome Lean for TypeScript Developers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Programming language and proof assistant whose types can state what code does, checked by the compiler.

[Lean 4](https://lean-lang.org) types go further than TypeScript's. They can say that a list is sorted, that a socket is open, or that a value is in range, and the compiler checks it. That matters more now that coding agents write much of the code. This is a curated reading list for TypeScript developers. For Lean libraries and broader learning paths, see [Related Lists](#related-lists).

Curated by [Daniel Steigerwald](https://github.com/steida), author of [Evolu](https://www.evolu.dev).

## Contents

- [Start Here](#start-here)
- [Why Lean](#why-lean)
- [Learning Lean](#learning-lean)
- [Coding Agents](#coding-agents)
- [Types as Specifications](#types-as-specifications)
- [Verifying TypeScript](#verifying-typescript)
- [Web and Apps](#web-and-apps)
- [Verified Software](#verified-software)

## Start Here

Don't read everything below. Read these in order.

1. [Lean Explained with TypeScript](https://gruhn.me/blog/2026-08-29/) - Proofs written as ordinary TypeScript types, before any Lean.
2. [Beyond Booleans](https://overreacted.io/beyond-booleans/) - The same idea in Lean, where `2 + 2 = 4` is a type whose values are proofs.
3. [A Lean Syntax Primer](https://overreacted.io/a-lean-syntax-primer/) - How to read Lean code, compared with JavaScript and TypeScript syntax.
4. [Don't Vibe — Prove](https://ngrislain.github.io/projects/2026-3-12-dont-vibe--prove/) - Types as the specification an agent must satisfy, shown with sorting algorithms.
5. [Functional Programming in Lean](https://lean-lang.org/functional_programming_in_lean/) - The book that teaches Lean as a programming language before proofs.

## Why Lean

- [The Math Is Haunted](https://overreacted.io/the-math-is-haunted/) - A first proof, and why one false axiom breaks everything that depends on it.
- [Why Am I Betting on Lean 4 for Agentic Coding?](https://theoric.com/blog/why-lean-4-for-agentic-coding/) - Agents lose track of system-wide invariants, and types that prove behavior catch it.

## Learning Lean

- [The Hitchhiker's Guide to Reading Lean 4 Theorems](https://blog.lambdaclass.com/the-hitchhikers-guide-to-reading-lean-4-theorems/) - Tactics explained as programming ideas, starting from a TypeScript function.
- [My Experience with Lean 4 for General Programming](https://quamserena.com/2025-12-10/my-experience-with-lean-4-for-general-programming) - A TypeScript and React developer builds a reactive HTML library in Lean and reports the rough edges.

## Coding Agents

- [How I Vibed a Proof of Conway's Conjecture](https://overreacted.io/how-i-vibed-a-proof-of-conways-conjecture/) - A month of steering coding agents to a kernel-checked proof, with lessons on workflow and trust.
- [Vibe-Coding a Debugger for a DSL](https://www.joachim-breitner.de/blog/819-Vibe-coding_a_debugger_for_a_DSL) - An agent builds an embedded language with an editor debugger in about a day.
- [Vibe Under Constraint](https://ngrislain.github.io/projects/2026-6-22-vibe-under-constraint/) - Resource budgets in types push an agent from load-everything to an external merge sort.

## Types as Specifications

- [Zero-Cost POSIX Compliance](https://ngrislain.github.io/blog/2026-3-25-zerocost-posix-compliance-encoding-the-socket-state-machine-in-lean-4s-type-system/) - The socket lifecycle as a typestate, with no runtime checks in the generated C.
- [Like Terraform, but in Lean 4](https://ngrislain.github.io/blog/2026-9-6-like-terraform-but-in-lean-4/) - Infrastructure as code where dangling references and invalid configurations fail to compile.
- [Safe JSON in Lean](https://josephmckinsey.com/jsonschemalean.html) - Validating untrusted JSON with JSON Schema or with subtypes that carry proofs, compared with TypeScript narrowing.

## Verifying TypeScript

- [LemmaScript](https://github.com/midspiral/LemmaScript) - Verifies TypeScript annotated with specifications by translating it to Lean or Dafny.
- [Thales](https://github.com/jessealama/thales) - Compiles a strict, pure subset of TypeScript into Lean modules you can prove things about.

## Web and Apps

- [LeanReact](https://theoric.com/blog/leanreact_introduction/) - React components written in Lean and compiled to JavaScript, with component state as inductive types.
- [LeanDB](https://theoric.com/blog/leandb_a_strongly_typed_sql_frontend/) - Schemas and queries in Lean, run as SQL on SQLite, with domain rules in types.
- [Lean Web and Networking](https://leangineer.com/awesome/web-networking/) - Directory of Lean HTTP servers, frameworks, protocols and clients.

## Verified Software

- [Lean Into Verified Software Development](https://aws.amazon.com/blogs/opensource/lean-into-verified-software-development/) - How AWS builds the Cedar authorization language with Lean models, proofs and differential testing.
- [Verifying Rust Cryptography in SymCrypt](https://www.microsoft.com/en-us/research/blog/verifying-rust-cryptography-in-symcrypt-from-standards-to-code/) - Microsoft proves its Rust ML-KEM and SHA-3 correct in Lean through Aeneas, with agents writing proofs.
- [Sal](https://github.com/fplaunchpad/sal) - Mergeable replicated data types, including collaborative text, verified in Lean and implemented in JavaScript.

## Related Lists

- [Awesome Lean Programming](https://github.com/saviorand/awesome-lean-programming) - Lean 4 libraries, tools and projects for programmers.
- [Leangineering](https://leangineer.com) - Searchable directory of Lean libraries and tools for software engineers.
- [Lean 4 Learning Roadmap](https://gist.github.com/theTyster/b694f85d269b5564a75dc1fb2fd0ee53) - Phased path from the basics to Mathlib and software verification.
- [Lean for Python Programmers](https://gvwilson.github.io/l4py/) - Lessons that teach Lean by building small tools, written for Python developers.
