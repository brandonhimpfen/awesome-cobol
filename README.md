# Awesome COBOL [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for COBOL, open-source compilers, mainframe emulators, database connectivity engines, copybook processing, IDE extensions, and legacy modernization frameworks.

COBOL (Common Business-Oriented Language) is a compiled, imperative language designed for business, finance, and administrative processing across enterprise and mainframe systems. Engineered for high-precision decimal arithmetic, fixed-width file layouts, and reliable batch/transactional execution, COBOL powers core banking infrastructure, insurance backends, and government systems worldwide. This list is intended for mainframe engineers, enterprise software developers, modernization specialists, and systems programmers.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Compilers & Runtimes](#compilers--runtimes)
- [Mainframe Emulation & Operating Systems](#mainframe-emulation--operating-systems)
- [Database & File Interoperability](#database--file-interoperability)
- [IDE Extensions & Developer Tools](#ide-extensions--developer-tools)
  - [Editor Plugins & Syntax Support](#editor-plugins--syntax-support)
  - [Testing & Code Analysis](#testing--code-analysis)
- [Related Awesome Lists](#related-awesome-lists)

## Compilers & Runtimes

Open-source and modern commercial compilers translating COBOL code into C, Java, or native binaries.

- [GnuCOBOL](https://sourceforge.net/projects/gnucobol/) — Free, modern open-source COBOL compiler translating source code to C for execution on Linux, Windows, macOS, and mainframes.
- [TinyCOBOL](https://sourceforge.net/projects/tinycobol/) — Open-source COBOL compiler targeting x86 architectures, generating GNU assembly via GCC.
- [RainCode COBOL](https://www.raincode.com/) — High-performance compiler enabling legacy COBOL applications to rehost natively on .NET and Azure platforms.
- [RES COBOL Translator](https://sourceforge.net/projects/res-cobol2java/) — Pure Java-based open-source tool translating VS COBOL syntax into maintainable Java source code.

## Mainframe Emulation & Operating Systems

Software emulators and public-domain operating system distributions for running legacy mainframe workloads locally.

- [Hercules System/370 Emulator](https://github.com/rbowler/spinhawk) — Open-source software implementation of the System/370, ESA/390, and 64-bit z/Architecture mainframe hardware.
- [MVS 3.8j Turnkey System (TK4-)](http://watsons-net.com/mvs/) — Ready-to-use public domain OS/VS2 MVS system package configured to run under Hercules.
- [Open Mainframe Project](https://www.openmainframeproject.org/) — Hosted foundation supporting open-source tools and infrastructure for modernizing mainframe environments.

## Database & File Interoperability

Tools, preprocessors, and middleware for querying databases and parsing fixed-width COBOL copybooks.

- [esqlOC](https://github.com/esqloc/esqloc) — Embedded SQL preprocessor enabling GnuCOBOL programs to interact with PostgreSQL, MariaDB, SQLite, and DB2.
- [Cobxref](https://sourceforge.net/projects/cobxref/) — Open-source cross-reference utility for GnuCOBOL that parses source files and copybooks to trace variable definitions and procedure usages.
- [COBOL Copybook Parser](https://github.com/cbparser) — Open-source utilities for converting fixed-width COBOL copybook layouts into JSON, CSV, and XML formats.

## IDE Extensions & Developer Tools

Code editors, static analyzers, and test suites supporting modern REPL and CI/CD development flows.

### Editor Plugins & Syntax Support

- [IBM Z Open Editor](https://marketplace.visualstudio.com/items?itemName=IBM.zopeneditor) — VS Code extension providing syntax highlighting, snippet autocompletion, and language server protocol support for COBOL, PL/I, and JCL.
- [cobol-mode for Emacs](https://github.com/harald-joerg/cobol-mode) — Major mode for GNU Emacs supplying indentation rules, syntax coloring, and formatting guides for COBOL source code.
- [COBOL.vim](https://github.com/jorenar/vim-cobol) — Lightweight Vim plugin adding syntax definitions and indentation rules tailored for standard COBOL formats.

### Testing & Code Analysis

- [COBOL-UP](https://sourceforge.net/projects/cobol-up/) — Open-source collection of compiler-independent COBOL utility modules, test suites, and helper scripts.

## Related Awesome Lists

- [Awesome Java](https://github.com/brandonhimpfen/awesome-java) — High-performance JVM libraries, concurrency toolkits, and object-oriented frameworks.
- [Awesome Open Source](https://github.com/brandonhimpfen/awesome-open-source) — Guidelines, licensing models, and project governance for open software repositories.
- [Awesome Infrastructure Monitoring](https://github.com/brandonhimpfen/awesome-infrastructure-monitoring) — Observability tools, metrics collection engines, and alert pipelines.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
