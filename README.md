# `py-doclint` — Technical Writing Style & Glossary Validator Toolkit

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.9%2B-blue.svg)

A generic, Python-based CLI and developer toolkit for enforcing technical writing standards, consistent project term capitalization, and style rules across Markdown documentation repositories.

---

## 🚀 Features

- **Glossary Capitalization Enforcer**: Automatically catches term variations (e.g. `lwm2m` vs `LwM2M`, `dtls` vs `DTLS`, `uart` vs `UART`).
- **Redundant Phrase Detector**: Highlights verbose or redundant prose (e.g. *"in order to"*, *"at this point in time"*).
- **Py-LogKit Integration**: Color-coded CLI output with optional file tracing.
- **CI/CD Strict Enforcement**: `--strict` flag for pipeline failures when writing style issues are detected.

---

## 🛠️ Installation

```bash
pip install -e .
```

---

## 💻 CLI Usage

```bash
# Lint current documentation directory
py-doclint .

# Enforce strict mode in CI pipeline
py-doclint docs/ --strict
```
