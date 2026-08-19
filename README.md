# Awesome Python Code Formatters with stars

A curated list of awesome Python code formatters

## All-in formatters

Formatters that take care of all your code.

* [ruff](https://github.com/astral-sh/ruff) ⭐ 49,250 | 🐛 2,114 | 🌐 Rust | 📅 2026-08-19: fast Rust-powered linter and code formatter, for Python. The formatter is 100% compatible with Black.
* [black](https://github.com/python/black) ⭐ 41,807 | 🐛 304 | 🌐 Python | 📅 2026-08-19: uncompromising Python code formatter.
* [yapf](https://github.com/google/yapf) ⭐ 13,979 | 🐛 419 | 🌐 Python | 📅 2026-08-14: yet another Python code formatter from Google.
* [autopep8](https://github.com/hhatto/autopep8) ⭐ 4,660 | 🐛 136 | 🌐 Python | 📅 2026-07-20: format Python code to conform to the PEP 8 style guide.

## UNIX-way formatters

Formatters that do only one job and do it well.

* [pyment](https://github.com/dadadel/pyment) ⭐ 953 | 🐛 42 | 🌐 Python | 📅 2024-06-18: formats and generates docstrings.
* [flynt](https://github.com/ikamensh/flynt) ⭐ 733 | 🐛 5 | 🌐 Rust | 📅 2026-07-19: converts old string literal formatting to f-strings.
* [docformatter](https://github.com/PyCQA/docformatter) ⭐ 596 | 🐛 32 | 🌐 Python | 📅 2026-08-10: formats docstrings to follow PEP 257.
* [ssort](https://github.com/bwhmather/ssort) ⭐ 400 | 🐛 23 | 🌐 Python | 📅 2026-08-03: sorts and groups classes, functions, and methods.
* [add-trailing-comma](https://github.com/asottile/add-trailing-comma) ⭐ 373 | 🐛 0 | 🌐 Python | 📅 2026-08-17: adds trailing commas to calls and literals.
* [eradicate](https://github.com/myint/eradicate) ⭐ 220 | 🐛 8 | 🌐 Python | 📅 2026-07-21: removes commented-out code from Python files.
* [teyit](https://github.com/isidentical/teyit) ⭐ 106 | 🐛 11 | 🌐 Python | 📅 2022-10-29: formats unittest assertions.
* [unify](https://github.com/myint/unify) ⭐ 98 | 🐛 16 | 🌐 Python | 📅 2022-07-04: modifies strings to all use the same quote where possible.
* [kwonly-transformer](https://github.com/Kludex/kwonly-transformer) ⭐ 91 | 🐛 3 | 🌐 Python | 📅 2026-05-01: Opinionated tool to ensure functions with multiple parameters to have exclusively keyword only parameters.
* [pydocstringformatter](https://github.com/DanielNoord/pydocstringformatter) ⭐ 90 | 🐛 15 | 🌐 Python | 📅 2026-08-18: Automatically format your Python docstrings to conform with PEP 8 and PEP 257.
* [no-optional](https://github.com/Kludex/no-optional) ⭐ 57 | 🐛 4 | 🌐 Python | 📅 2026-05-01: Replace `Optional[T]` by `Union[T, None]`.
* [docstrfmt](https://github.com/LilSpazJoekp/docstrfmt) ⭐ 43 | 🐛 7 | 🌐 Python | 📅 2026-08-17: a tool for automatically formatting reStructuredText in files and Python docstrings in a consistent way.
* [decrapify](https://github.com/craigds/decrapify) ⚠️ Archived: some scripts that use pybowler.io for refactoring Python code.
* [formate](https://github.com/python-formate/formate) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-04-07: a wrapper around `isort` and `yapf` with a few custom rules.
* [fix8](https://github.com/PeterJCLaw/fix8) ⭐ 5 | 🐛 3 | 🌐 Python | 📅 2023-09-17: fixes some Python linting issues found by Flake8.
* [Tornado Async Transformer](https://github.com/zhammer/tornado-async-transformer) ⭐ 0 | 🐛 0 | 📅 2019-12-11: A libcst transformer for updating tornado `@gen.coroutine` syntax to python3.5+ native `async`/`await`.
* [pybetter](https://pypi.org/project/pybetter/): fixes some trivial problems with your code.

## Imports formatters

Formatters for import statements.

* [isort](https://github.com/timothycrosley/isort) ⭐ 6,946 | 🐛 88 | 🌐 Python | 📅 2026-08-18: sorts imports.
* [autoflake](https://github.com/myint/autoflake) ⭐ 953 | 🐛 47 | 🌐 Python | 📅 2026-07-30: removes unused imports and unused variables as reported by pyflakes.
* [reorder-python-imports](https://github.com/asottile/reorder_python_imports) ⭐ 784 | 🐛 1 | 🌐 Python | 📅 2026-08-17: reorders imports.
* [pycln](https://github.com/hadialqattan/pycln) ⭐ 314 | 🐛 16 | 🌐 Python | 📅 2026-01-13: removes unused imports.
* [unimport](https://github.com/hakancelik96/unimport) ⭐ 248 | 🐛 1 | 🌐 Python | 📅 2026-06-02: removes unused imports.
* [usort](https://github.com/facebookexperimental/usort) ⭐ 205 | 🐛 28 | 🌐 Python | 📅 2026-03-01: Safe, minimal import sorting for Python projects.
* [removestar](https://github.com/asmeurer/removestar) ⭐ 183 | 🐛 13 | 🌐 Python | 📅 2026-07-20: replaces `import *` in Python files with explicit imports.
* [pyall](https://github.com/hakancelik96/pyall) ⭐ 24 | 🐛 10 | 🌐 Python | 📅 2026-04-23: keeps the `__all__` list always up to date.

## Upgrading tools

Tools to upgrade to newer versions of Python or a framework.

* [pyupgrade](https://github.com/asottile/pyupgrade) ⭐ 4,114 | 🐛 21 | 🌐 Python | 📅 2026-08-17: upgrades syntax for newer versions of the language.
* [django-upgrade](https://github.com/adamchainz/django-upgrade) ⭐ 1,228 | 🐛 10 | 🌐 Python | 📅 2026-08-18: upgrades Django projects.
* [django-codemod](https://github.com/browniebroke/django-codemod) ⭐ 189 | 🐛 8 | 🌐 Python | 📅 2026-08-18: upgrades Django projects to newer version of the framework by automatically fixing deprecations.
* [com2ann](https://github.com/ilevkivskyi/com2ann) ⭐ 158 | 🐛 10 | 🌐 Python | 📅 2025-06-02: translates type comments to type annotations.
* [auto-walrus](https://github.com/MarcoGorelli/auto-walrus) ⭐ 130 | 🐛 6 | 🌐 Python | 📅 2026-08-17: automatically use the walrus operator where possible.
* [2to3](https://docs.python.org/2/library/2to3.html): translates Python 2 to 3.

## Improvements and wrappers

Wrappers for existing code formatters to make them more accessible.

* [nbQA](https://github.com/nbQA-dev/nbQA) ⭐ 1,203 | 🐛 23 | 🌐 Python | 📅 2026-08-17: run `isort`, `pyupgrade`, `mypy`, `pylint`, `flake8`, and more on Jupyter Notebooks.
* [jupyterlab-code-formatter](https://github.com/ryantam626/jupyterlab_code_formatter) ⭐ 906 | 🐛 27 | 🌐 Python | 📅 2026-08-07: code formatter for JupyterLab.
* [blacken-docs](https://github.com/asottile/blacken-docs) ⭐ 680 | 🐛 15 | 🌐 Python | 📅 2026-08-18: runs `black` on python code blocks in documentation files.
* [shed](https://github.com/Zac-HD/shed) ⭐ 353 | 🐛 7 | 🌐 Python | 📅 2025-06-05: wrapper around `autoflake`, `black`, `com2ann`, `isort`, `pybetter`, `pyupgrade`, and `teyit`.
* [mdsf](https://github.com/hougesen/mdsf) ⭐ 110 | 🐛 33 | 🌐 Rust | 📅 2026-08-14: run python formatters on markdown code blocks.
* [pyformat](https://github.com/myint/pyformat) ⭐ 92 | 🐛 9 | 🌐 Python | 📅 2024-01-01: wrapper around `autopep8`, `autoflake`, `docformatter`, and `unify`.
* [black-macchiato](https://github.com/wbolster/black-macchiato) ⭐ 74 | 🐛 7 | 🌐 Python | 📅 2025-04-26: runs `black` on parts of the code.
* [gray](https://github.com/dizballanze/gray) ⭐ 73 | 🐛 5 | 🌐 Python | 📅 2025-07-12: wrapper around `isort`, `pyupgrade`, `add-trailing-comma`, and `unify`.
* [formate-black](https://github.com/python-formate/formate-black) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-05-06: integrates `black` with `formate`.
* [brunette](https://github.com/odwyersoftware/brunette): wrapper around `black` with improvements.

## Libraries and refactoring

If you need to write your own formatter, these are libraries for you.

* [semgrep](https://github.com/returntocorp/semgrep) ⭐ 16,300 | 🐛 891 | 🌐 OCaml | 📅 2026-08-19: like grep but for code. Supports [--autofix](https://semgrep.dev/docs/writing-rules/rule-syntax/#fix) flag for simple replacement of matched code.
* [comby](https://github.com/comby-tools/comby) ⭐ 2,670 | 🐛 86 | 🌐 OCaml | 📅 2026-06-08: Comby is a tool for searching and changing code structure
* [rope](https://github.com/python-rope/rope) ⭐ 2,233 | 🐛 140 | 🌐 Python | 📅 2026-08-16: refactoring library.
* [libcst](https://github.com/Instagram/LibCST) ⭐ 1,939 | 🐛 173 | 🌐 Python | 📅 2026-08-11: parses Python code as a CST tree that keeps all formatting details (comments, whitespaces, parentheses, etc).
* [bowler](https://github.com/facebookincubator/Bowler) ⚠️ Archived: safe code refactoring for modern Python.
* [refactor](https://github.com/isidentical/refactor) ⭐ 459 | 🐛 22 | 🌐 Python | 📅 2023-12-30: AST-based fragmental source code refactoring toolkit.
* [importlab](https://github.com/google/importlab) ⚠️ Archived: A library that automatically infers dependencies for Python files. Importlab's main use case is to work with static analysis tools that process one file at a time, ensuring that a file's dependencies are analysed before it is.
* [massedit](https://github.com/elmotec/massedit) ⭐ 116 | 🐛 1 | 🌐 Python | 📅 2025-09-21: edit text files with Python.
* [autotransform](https://github.com/nathro/AutoTransform) ⭐ 61 | 🐛 2 | 🌐 Python | 📅 2025-01-29: framework for large-scale code modification.
* [fissix](https://github.com/jreese/fissix) ⭐ 55 | 🐛 22 | 🌐 Python | 📅 2026-08-01: backport of [lib2to3](https://docs.python.org/2/library/2to3.html), with enhancements.

## Code generators

This list doesn't contain tools that generate code, type annotations, comments etc. The difference is that code formatters transform your code from one form into another (which should be safe if the tool is stable) while code generators bring something totally new. If you're looking for code generators, check out the following links:

* [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing#helper-tools-to-add-annotations-to-existing-code) ⭐ 1,976 | 🐛 7 | 📅 2026-06-19: tools to generate type annotations.
* [awesome-python-testing](https://github.com/cleder/awesome-python-testing#tools) ⭐ 304 | 🐛 2 | 📅 2026-08-17: tools to generate tests.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
