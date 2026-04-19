<div align="center">

# Nova Native Chinese Compiler

**Chinese-Native Compiler & System Software Engineering**

[![CI](https://github.com/nova-awakening/nova-awakening/actions/workflows/ci.yml/badge.svg)](https://github.com/nova-awakening/nova-awakening/actions/workflows/ci.yml)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/nova-awakening/nova-awakening/badge)](https://scorecard.dev/viewer/?uri=github.com/nova-awakening/nova-awakening)
[![License](https://img.shields.io/badge/License-Nova--CSL%201.1-blue.svg)](NOTICE)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-Stage2%20≡%20Stage3-success.svg)]()
[![Language](https://img.shields.io/badge/Lang-Chinese%20Native-red.svg)]()
[![Platform](https://img.shields.io/badge/Platform-x86__64%20Linux-lightgrey.svg)]()
[![Repo Size](https://img.shields.io/github/repo-size/nova-awakening/nova-awakening)](https://github.com/nova-awakening/nova-awakening)
[![Last Commit](https://img.shields.io/github/last-commit/nova-awakening/nova-awakening)](https://github.com/nova-awakening/nova-awakening/commits/master)
[![Commit Activity](https://img.shields.io/github/commit-activity/m/nova-awakening/nova-awakening)](https://github.com/nova-awakening/nova-awakening/commits/master)

[🇨🇳 中文](README.md) | **🇬🇧 English**

</div>

## About

Nova is an engineering project focused on **Chinese-native programming, native compilation, and system software development**.

- **Native Compiler**: Complete compilation pipeline from Chinese syntax to native machine code generation
- **Pure System**: System-level modules, runtime environment, and native software stack co-evolution
- **Chinese-First Expression**: Keywords, identifiers, error messages, and engineering semantics in native Chinese
- **Long-Term Engineering**: Emphasis on maintainability, module boundaries, and foundational software autonomy

## Repository Structure

```
Nova编译器/    ← Compiler core: IR, optimization, code generation, memory & toolchain
Nova觉醒/    ← System modules: runtime, native software stack engineering
```

## Publish Boundary

- The GitHub release surface of this repository is intentionally limited to formal root files, `Nova编译器/`, and `Nova觉醒/`
- Local experiment directories, bootstrap helper directories, process notes, and temporary artifacts are kept out of the GitHub release surface by default
- The final native compiler binary that passes fixed-point bootstrap verification will be managed as a separate versioned release artifact instead of being kept long-term inside the source release surface

## Current Release Status

- **Native Compiler**: this repository currently publishes source code and fixed-point evolution status; the authoritative native compiler seed will be identified by later versioned release artifacts
- **Pure System**: this repository currently publishes the system source tree, not a formal system image
- **Image Status**: as of the current version, `Nova觉醒/` has not yet been stably compiled by the current authoritative native compiler into a formally releasable system image, so no system image download is provided in this repository yet

## Core Value

- **Chinese-Native Development**: Reducing semantic friction in Chinese-context expression, learning, and collaboration
- **Native Compilation**: Targeting native code generation and foundational software, not just interpretation
- **System-Level Co-Design**: Compiler and system engineering advancing in parallel, forming a unified software stack
- **Self-Reliance**: Serving Chinese programming language, foundational software, and native system capability building

## Use Cases

- Chinese programming language & compiler research
- Native system software & foundational software R&D
- Teaching, experimentation, prototyping & technical demonstration
- AI runtime environment & autonomous software stack exploration

## License & Compliance

**Nova Commercial Source License (Nova-CSL 1.1)**:

- **Non-Commercial Use**: Personal study, research, teaching, and qualifying non-commercial scenarios — free of charge
- **Commercial Use**: Requires prior written commercial authorization
- **Post-Conversion Open Source**: From April 18, 2032, choose between AGPL-3.0 and MulanPubL-2.0
- **License Files Govern**: All rights and obligations are defined in [LICENSE](LICENSE), `LICENSE_木兰公共版`, and [NOTICE](NOTICE)
- **Legal Compliance**: Project operates under intellectual property protection and applicable law

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines and license agreement terms.

## Security

See [SECURITY.md](SECURITY.md) for vulnerability reporting policy.

## Contact

- GitHub Issues: [Open an Issue](https://github.com/nova-awakening/nova-awakening/issues)
- Commercial Licensing: Tag your Issue with `[商业授权]`
