# Error Translator

<div align="left">
  <a href="https://pypi.org/project/error-translator-cli-v2/"><img alt="PyPI Version" src="https://img.shields.io/pypi/v/error-translator-cli-v2.svg"></a>
  <a href="https://pypi.org/project/error-translator-cli-v2/"><img alt="Python 3.9+" src="https://img.shields.io/badge/python-3.9%2B-blue.svg"></a>
  <a href="https://github.com/gourabanandad/error-translator-cli-v2"><img alt="License" src="https://img.shields.io/github/license/gourabanandad/error-translator-cli-v2.svg"></a>
  <a href="https://github.com/gourabanandad/error-translator-cli-v2/actions/workflows/ci.yml"><img alt="Build Status" src="https://img.shields.io/github/actions/workflow/status/gourabanandad/error-translator-cli-v2/ci.yml?branch=master&label=build"></a>
</div>

<br>

![Error Translator CLI V2 demo banner](assets/images/banner.png)

<br>

**Error Translator** parses raw Python tracebacks and converts them into readable explanations with actionable fixes. Built for local-first development workflows, it uses a deterministic, offline regex-matching engine that powers a CLI, Python API, auto-hook mode, Jupyter notebooks, and a FastAPI service.

If this project is useful to you, support it with a GitHub star: https://github.com/gourabanandad/error-translator-cli-v2

Quick links:
- GitHub Repository: https://github.com/gourabanandad/error-translator-cli-v2
- PyPI Package: https://pypi.org/project/error-translator-cli-v2/
- Issues / Feature Requests: https://github.com/gourabanandad/error-translator-cli-v2/issues

## Core Design Principles

- **Privacy-First (Offline)**: Your stack traces and source code snippets never leave your machine. The regex and AST engines operate entirely locally.
- **Deterministic Matching**: Regex rules are compiled once and reused, ensuring consistent outputs for the same error text.

## Quickstart

### Installation

Requires Python 3.9 or newer. Install globally via pip:

```bash
pip install error-translator-cli-v2
```

### Basic Usage

Run a Python script and translate unhandled exceptions:
```bash
explain-error run script.py
```

Provide an error string directly:
```bash
explain-error "NameError: name 'usr_count' is not defined"
```

For more advanced integrations (Jupyter, FastAPI, Import Hooks), please refer to the [Features & Integrations](features.md) guide.

## Documentation Navigation

- [**Features & Integrations**](features.md): Comprehensive guide on all usage modes (CLI, Jupyter, FastAPI, etc.).
- [**Real-World Examples**](examples.md): Practical demonstrations comparing raw tracebacks with translated outputs.
- [**Architecture & Internals**](ARCHITECTURE.md): Technical breakdown of the engine, rule pipeline, and native acceleration.
- [**Contributing Guidelines**](CONTRIBUTING.md): Guidelines for adding rules and using the AI-Powered Rule Builder.
