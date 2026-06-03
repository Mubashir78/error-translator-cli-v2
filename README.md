# Error Translator

<div align="left">
  <a href="https://pypi.org/project/error-translator-cli-v2/"><img alt="PyPI Version" src="https://img.shields.io/pypi/v/error-translator-cli-v2.svg"></a>
  <img alt="Python 3.9+" src="https://img.shields.io/badge/python-3.9%2B-blue.svg">
  <a href="https://github.com/gourabanandad/error-translator-cli-v2/stargazers"><img alt="GitHub Stars" src="https://img.shields.io/github/stars/gourabanandad/error-translator-cli-v2?style=social"></a>
  <a href="https://pypi.org/project/error-translator-cli-v2/"><img alt="PyPI Downloads" src="https://img.shields.io/pypi/dm/error-translator-cli-v2"></a>
  <a href="https://github.com/gourabanandad/error-translator-cli-v2"><img alt="License" src="https://img.shields.io/github/license/gourabanandad/error-translator-cli-v2.svg"></a>
  <a href="https://github.com/gourabanandad/error-translator-cli-v2/actions/workflows/ci.yml"><img alt="Build Status" src="https://img.shields.io/github/actions/workflow/status/gourabanandad/error-translator-cli-v2/ci.yml?branch=master&label=build"></a>
</div>

<br>

![Error Translator CLI V2 demo banner](docs/assets/images/banner.png)

<br>

**Error Translator** is an offline Python traceback translator and exception explainer that converts raw errors into crystal-clear explanations and immediately actionable fixes. Built for local-first development workflows, it supports direct CLI usage, an automatic import hook, a programmatic Python API, and a FastAPI integration.

If this project saves you debugging time, please consider starring it on GitHub: https://github.com/gourabanandad/error-translator-cli-v2

## Why Developers Like It

* **Fast Feedback Loop**: Turn stack traces into direct next actions in seconds.
* **Works Offline**: No telemetry dependency for core translation behavior.
* **Beginner-Friendly Output**: Explanations are clear enough for learners, practical enough for teams.
* **Multiple Entry Points**: CLI, import hook, Python API, and FastAPI all share one deterministic engine.

## Features & Usage

Error Translator is packed with features designed for a seamless debugging experience, including:

- **CLI-First Architecture** with a rich terminal UI.
- **Automatic Integration Mode** via import hooks.
- **Jupyter Notebook Integration** for interactive debugging.
- **FastAPI Service** for remote translation.
- **Deterministic Rules Engine** with optional C extension acceleration.

For a comprehensive list of features and detailed usage instructions for all integration modes, please check our [Features & Usage Guide](https://gourabanandad.github.io/error-translator-cli-v2/features/).

## Installation

Python requirement: **3.9 or newer**.

Install the latest stable release directly from PyPI:

```bash
pip install error-translator-cli-v2
```

Verify the installation:

```bash
explain-error --version
```

## Documentation

Detailed documentation is located in the [`docs/`](docs/) directory:

- [**Features & Usage Guide**](docs/features.md): Comprehensive list of features, and usage instructions across various platforms.
- [**Real-World Examples**](docs/examples.md): Practical demonstrations comparing raw tracebacks with their translated counterparts.
- [**Architecture & Internals**](docs/ARCHITECTURE.md): Comprehensive teardown of the regex engine, AST integration, and internal design philosophy.
- [**Contributing Guidelines**](docs/CONTRIBUTING.md): Standards, PR checklists, and instructions for utilizing our AI-Powered Rule Builder.

## Maintainers

This project is actively developed and maintained by **Gourabananda Datta** alongside our open-source contributors.
