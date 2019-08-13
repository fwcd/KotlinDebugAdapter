# Kotlin Debug Adapter
A [debug adapter](https://microsoft.github.io/debug-adapter-protocol/) that provides IDE-independent debugging support for Kotlin/JVM.

[![Version](https://vsmarketplacebadge.apphb.com/version-short/fwcd.kotlindebug.svg)](https://marketplace.visualstudio.com/items?itemName=fwcd.kotlindebug)
[![Installs](https://vsmarketplacebadge.apphb.com/installs-short/fwcd.kotlindebug.svg)](https://marketplace.visualstudio.com/items?itemName=fwcd.kotlindebug)
[![Build Status](https://travis-ci.org/fwcd/kotlin-debug-adapter.svg?branch=master)](https://travis-ci.org/fwcd/kotlin-debug-adapter)

![Icon](Icon128.png)

Any editor conforming to DAP is supported, including [VSCode](https://github.com/fwcd/vscode-kotlin-ide).

## Getting Started
* See [BUILDING.md](BUILDING.md) for build instructions
* See [Editor Integration](EDITORS.md) for editor-specific instructions
* See [Kotlin Quick Start](https://github.com/fwcd/kotlin-quick-start) for a sample project
* See [Kotlin Language Server](https://github.com/fwcd/kotlin-language-server) for smart code completion, diagnostics and more

## Architecture
`DAP client` <= JSON => `KotlinDebugAdapter` <=> `Core abstractions` <=> `Java Debug Interface`
