# Hi, I'm Pavel 👋

### Rust developer building practical tools for developers, data, and automation

I design, implement, and test software that turns repetitive workflows into
reliable tools. My recent work is mostly Rust-based and combines desktop
applications, command-line utilities, backend services, and developer-focused
experiments.

I enjoy working on projects where a clear workflow, useful diagnostics, and a
well-defined output matter more than unnecessary complexity.

## What I work on

- **Developer tools** — format converters, structured-data viewers, API
  explorers, and utilities for everyday engineering work.
- **Automation** — cross-platform update orchestration for system managers,
  language ecosystems, and editor extensions.
- **Data and documentation** — Markdown, Office documents, JSON/YAML/TOML,
  CSV/XLSX, OpenAPI, and generated documentation.
- **API and observability** — runtime checks, schema evolution, access
  matrices, integrations, analytics, and exportable reports.
- **Security education** — interactive experiments with cryptographic APIs,
  formats, and safe demonstrations.
- **Cross-platform UX** — local-first GUI applications with CLI workflows,
  explicit errors, previews, and reproducible builds.

## Selected projects and experiments

The projects below reflect recent implementations, prototypes, and technical
experiments. Their scope and status may evolve as the ideas are tested further.

### [`markoff`](https://github.com/PavelKotDRM/markoff) — document and data conversion

A Rust workspace with CLI and GUI workflows for converting between Markdown,
DOCX, PDF, PPTX, HTML, JSON, YAML, TOML, CSV, and XLSX. It includes batch
conversion, standard-input/output support, previews, drag-and-drop, format
detection, round-trip tests, and a shared conversion core.

### [`StructView`](https://github.com/PavelKotDRM/StructView) — structured-data workspace

A cross-platform viewer and editor for JSON, YAML, TOML, and JSON5. It
provides an interactive tree, search, typed editing, format conversion,
multi-file comparison, copy/paste of nested structures, localization, and a
headless CLI for formatting, validation, path search, and diffs.

### [`UpdateAllModules`](https://github.com/PavelKotDRM/UpdateAllModulesInSystem) — cross-platform update automation

A Rust CLI/GUI utility for checking and updating system package managers,
Python packages, npm/pnpm, Node.js, Rust toolchains, and extensions for
VS Code-compatible editors. It supports parallel scanning, controlled update
queues, per-module logs, safe selection, cancellation, elevation, and
Windows/Linux/macOS workflows.

### `API Catalog Builder` — runtime-aware API documentation

A desktop tool for importing or creating OpenAPI maps, configuring
authorization profiles, sending real requests, comparing expected and
observed schemas, and capturing state continuously. It exports OpenAPI,
Markdown, HTML, JSON/JSONL, endpoint cards, and LLM/RAG-oriented artifacts.

### `GetAnalysysFromOpenWebUI` — OpenWebUI analytics

A Rust/Tokio service that synchronizes OpenWebUI data into SQLite or
PostgreSQL and exposes a responsive dashboard with local Plotly charts.
It includes background synchronization, filtering, pagination, JSON/CSV
exports, health checks, admin actions, demo mode, and diagnostics for models,
RAG, tools, and errors.

### `OpenWebUI Add Users` — Excel-based account management

A desktop application and library for creating users from Excel, deleting
users by email, exporting the current user list, previewing mapped columns,
and running non-destructive test modes before calling the OpenWebUI API.

### [`BitrixText Forge`](https://github.com/PavelKotDRM/bitrixtext_forge) — Markdown to Bitrix24 content

A local desktop editor that previews Markdown and converts it to compatible
Bitrix24 BBCode or plain text. It includes conversion profiles, diagnostics,
templates, autosave, session recovery, resource export, and clipboard
integration without connecting to Bitrix24 or storing credentials.

### `fio_email_xlsx` — structured list to Excel

A Rust/egui utility that parses full names, email addresses, and explicitly
provided passwords from text, reports warnings with line numbers, previews
records, and exports a normalized `.xlsx` table.

### `crypto_explorer` — cryptography API explorer

An interactive RustCrypto and `bcrypt` explorer with category navigation,
visual operation results, and copyable Rust snippets. It is designed for
learning APIs and formats, not for production cryptography.

### [`rand_explorer`](https://github.com/PavelKotDRM/rand_explorer) — randomness and distributions

A GPU-accelerated egui application for exploring scalar generation, ranges,
collections, distributions, histograms, deterministic RNG engines, and
micro-benchmarks in the `rand` ecosystem.

## Earlier public projects

These public repositories preserve earlier experiments in Python, data
visualization, Windows automation, and reusable developer utilities.

### [`GreekRomanNumerical`](https://github.com/PavelKotDRM/GreekRomanNumerical) — Greek and Roman numerals

A Python library for converting Arabic numbers to Greek and Roman numerals and
back again. It supports textual representations, configurable Greek numeral
formats, arithmetic operations on custom number types, tests, and an optional
Rust backend behind the Python API.

### [`LookWithJuputer`](https://github.com/PavelKotDRM/LookWithJuputer) — Jupyter data viewer

An interactive Jupyter widget for browsing `pandas` and `polars` tables.
It provides row-range navigation, column selection, a small Python API, and
tests for working with larger DataFrames directly in notebooks.

### [`ClassificationOfTexts`](https://github.com/PavelKotDRM/ClassificationOfTexts) — machine-learning notebooks

A Python 3.11 project exploring text classification with PyTorch and fastai.
The repository includes notebook-based models and a data-science stack built
around spaCy, transformers, scikit-learn, pandas, polars, NumPy, and plotting
tools.

### [`ParserHostFile`](https://github.com/PavelKotDRM/ParserHostFile) — Windows hosts-file validation

A PowerShell utility for checking the structure of the Windows `hosts` file,
including the Microsoft header, IP addresses, hostnames, comments, line
numbers, and validation errors.

### [`UpdatePipevAndMsys`](https://github.com/PavelKotDRM/UpdatePipevAndMsys) — environment maintenance scripts

A collection of PowerShell scripts for updating pip packages across configured
Python virtual environments, PowerShell 7, and MSYS components, with a
separate check-only workflow.

## Institute assignments

### [`AssignmentsAtTheInstitute`](https://github.com/PavelKotDRM/AssignmentsAtTheInstitute) — C++ coursework archive

A public archive of completed laboratory works, practical assignments, and
course projects from my institute years. The repository follows the
progression from fundamental C++ exercises to Windows desktop applications:

- **Laboratory works** covering functions and classes, dynamic memory, geometry,
  bitwise operations, sorting, inheritance, polymorphism, copy semantics,
  pointers, files, and data storage.
- **Practical works** focused on functions, parameters, advanced C++ concepts,
  specialized programming tasks, and geometric calculations.
- **Course projects** including a `Rational` fraction type, employee-data
  import/search/filter/export workflows, and a Windows Forms CRUD application.

The archive is implemented with C++, Visual Studio/MSVC, STL, and Windows
Forms. It documents an early foundation in object-oriented programming,
algorithms, memory management, and file-based data processing.

## Technology stack

| Area | Tools and technologies |
| --- | --- |
| Primary language | Rust, edition 2024 |
| Other languages | C/C++, Python, PowerShell |
| Desktop UI | `egui`, `eframe`, `egui_extras` |
| Async and services | Tokio, `reqwest`, `rustls`, REST APIs |
| Data and serialization | `serde`, JSON, YAML, TOML, OpenAPI |
| Data science | Jupyter, PyTorch, fastai, pandas, polars, scikit-learn |
| Storage and analytics | SQLite, PostgreSQL, SQLx, local-first workflows |
| Documents and exports | Markdown, DOCX, PDF, PPTX, CSV, XLSX |
| Delivery and quality | Cargo, uv, Docker, GitHub Actions, Visual Studio, pytest, rustfmt, Clippy, RustSec |

## Engineering principles

- **Prefer useful software over empty abstractions.** Each project starts with
  a concrete workflow and a measurable result.
- **Make behavior visible.** Previews, diagnostics, structured logs, and
  explicit errors are part of the user experience.
- **Keep risky actions deliberate.** Test modes, safe defaults, confirmation
  steps, secret masking, and clear limitations are built into the workflow.
- **Design for more than one environment.** Windows is a frequent target,
  while Linux and macOS support are considered where the platform allows it.
- **Verify the core.** I use unit and integration tests, documentation
  examples, formatting, static analysis, and reproducible build checks.

## Beyond developer tooling

I also explore Godot and Unreal Engine, 3D modeling, and the ways interactive
software can make complex technical workflows easier to understand.

## Let's connect

I'm interested in Rust tooling, automation, API and data workflows, developer
experience, and thoughtful cross-platform applications.

- [GitHub](https://github.com/PavelKotDRM)
- [Telegram](https://t.me/PavelKotKPALab)
- [Email](mailto:kpalab@pkotlyarov.ru)
