# XIFtySense

XIFtySense builds **XIFty**, a modern metadata engine for media files.

XIFty is designed to make metadata extraction more reliable, explainable, and portable across applications and languages. The project centers on:

- a Rust core
- a narrow C ABI
- a CLI for direct use and debugging
- language packages built on top of the same core contract

## Start Here

- [XIFty](https://github.com/XIFtySense/XIFty)  
  Core engine, CLI, architecture docs, capability definitions, and the stable FFI seam.

## What XIFty Focuses On

- extracting metadata from images and media files with provenance preserved
- exposing `raw`, `interpreted`, `normalized`, and `report` views
- making ambiguity and malformed data visible instead of hiding it
- keeping bindings thin and consistent across languages

## Language Packages

- [XIFtyNode](https://github.com/XIFtySense/XIFtyNode)  
  Node.js package for XIFty
- [XIFtySwift](https://github.com/XIFtySense/XIFtySwift)  
  Swift package for XIFty
- [XIFtyPython](https://github.com/XIFtySense/XIFtyPython)  
  Python package for XIFty
- [XIFtyRust](https://github.com/XIFtySense/XIFtyRust)  
  Rust crate for XIFty
- [XIFtyGo](https://github.com/XIFtySense/XIFtyGo)  
  Go package for XIFty
- [XIFtyCpp](https://github.com/XIFtySense/XIFtyCpp)  
  C++ package for XIFty

## Current Direction

Today, XIFty is strongest as:

- a metadata engine for still images and bounded media metadata
- a CLI and embeddable core for application builders
- a foundation for consistent metadata handling across ecosystems

## For Evaluators

If you are comparing metadata solutions, start with:

1. the [core XIFty repo](https://github.com/XIFtySense/XIFty)
2. the [CLI usage in the README](https://github.com/XIFtySense/XIFty#readme)
3. the binding repo for your language/runtime

## Status

XIFty is actively evolving, but the project is already usable today through the core repo and public binding packages.
