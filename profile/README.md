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
- [Live Browser Demo](https://xiftysense.github.io/XIFty/)  
  Local-in-browser inspection of still-image metadata through the same four-view model.

## Production Today

- [XIFtyNode](https://github.com/XIFtySense/XIFtyNode)  
  The most production-ready package today, including the first-party Node-on-Lambda path built on `@xifty/xifty`.
- [AWS Lambda adoption docs](https://github.com/XIFtySense/XIFty/blob/main/docs/adoption/AWS_LAMBDA_NODE.md)  
  Official Node Lambda guidance, SAM example, and layer packaging path.

## What XIFty Focuses On

- extracting metadata from images and media files with provenance preserved
- exposing `raw`, `interpreted`, `normalized`, and `report` views
- making ambiguity and malformed data visible instead of hiding it
- keeping bindings thin and consistent across languages

## Language Packages

- [XIFtyNode](https://github.com/XIFtySense/XIFtyNode)  
  Official Node package for XIFty
- [XIFtySwift](https://github.com/XIFtySense/XIFtySwift)  
  Official Swift binding for XIFty (source-first today)
- [XIFtyPython](https://github.com/XIFtySense/XIFtyPython)  
  Official Python binding for XIFty (source-first today)
- [XIFtyRust](https://github.com/XIFtySense/XIFtyRust)  
  Official Rust binding for XIFty (source-first today)
- [XIFtyGo](https://github.com/XIFtySense/XIFtyGo)  
  Official Go binding for XIFty (source-first today)
- [XIFtyCpp](https://github.com/XIFtySense/XIFtyCpp)  
  Official C++ binding for XIFty (source-first today)

## Current Direction

Today, XIFty is strongest as:

- a metadata engine for still images and bounded media metadata
- a CLI and embeddable core for application builders
- a browser demo that proves the model in a product-shaped UI
- a Node package with a first-party AWS Lambda adoption path
- a foundation for consistent metadata handling across ecosystems

## For Evaluators

If you are comparing metadata solutions, start with:

1. the [core XIFty repo](https://github.com/XIFtySense/XIFty)
2. the [live browser demo](https://xiftysense.github.io/XIFty/)
3. the [CLI usage in the README](https://github.com/XIFtySense/XIFty#readme)
4. the binding repo for your language/runtime

## Status

XIFty is actively evolving, but it is already usable today through the core repo, the live browser demo, and the public binding repos. Node is currently the most turnkey binding; the others are usable and CI-backed, but still more source-first than fully packaged.
