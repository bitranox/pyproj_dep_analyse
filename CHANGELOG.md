# Changelog

All notable changes to this project will be documented in this file following
the [Keep a Changelog](https://keepachangelog.com/) format.


## [1.0.0] - 2025-12-02

### Added
- Core dependency analysis functionality for pyproject.toml files
- `Analyzer` class with async support and configurable concurrency
- PyPI and GitHub version resolution with caching
- Python version compatibility checking via `requires-python` parsing
- CLI commands: `analyze`, `config`, `config-deploy`, `info`, `hello`, `fail`
- Layered configuration system (defaults → app → host → user → env)
- JSON output format for analysis results
- Comprehensive test suite with 384 tests
