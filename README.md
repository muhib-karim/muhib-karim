# Muhib Karim

AI engineer with a verification and validation background. 10+ years across connected-vehicle testing at Ford and Toyota and Azure cloud research at RMIT, now building and testing LLM tooling: evaluation harnesses, test generation and code intelligence.

Melbourne, Australia · [LinkedIn](https://www.linkedin.com/in/muhibalkarim)

## Current work

- **[agent-eval-harness](https://github.com/muhib-karim/agent-eval-harness)**: compare coding models and agent CLIs on the same tasks, graded with withheld pytest suites. Reproducible JSONL results and HTML/Markdown reports.
- **[api-vv-toolkit](https://github.com/muhib-karim/api-vv-toolkit)**: generate API tests from an OpenAPI spec and written requirements, run them, and report a requirements-to-test traceability matrix (Markdown, HTML, CSV, JUnit). Optional LLM-suggested cases must pass a spec validation gate.
- **codegraph** (private for now): index Python and Java into an embedded code graph and answer callers, inheritance, dead-code and change-impact queries with file:line evidence. CLI, MCP server and a labelled retrieval evaluation.

## Other projects

- **[Antigravity-Claude-Code-Proxy](https://github.com/muhib-karim/Antigravity-Claude-Code-Proxy)**: local Anthropic-compatible gateway (Node.js/Express) that routes Claude Code to multiple models, with account failover, per-session model selection and an offline end-to-end test harness (28 tests).
- **[Claude-Proxy-Extension](https://github.com/muhib-karim/Claude-Proxy-Extension)**: VS Code extension published on Open VSX that shows live per-account AI quota and switches models per editor window.
- **[OpenSH](https://github.com/muhib-karim/OpenSH)**: cross-platform CLI that turns plain-English requests into shell commands, with a confirmation step for destructive commands and a 128-test pytest suite run in CI on Linux, Windows and macOS.
- **[NewTerminal-AI](https://github.com/muhib-karim/NewTerminal-AI)**: offline terminal assistant for PowerShell and bash on a local Ollama model, covered by 139 Pester tests across three OSes.
- **[Rambler-Bangla](https://github.com/muhib-karim/Rambler-Bangla)**: fail-closed patch that keeps Gboard's Lite cleanup from Romanizing Bengali, with a static test suite. Source and audit docs only.

## Background

- **Ford Motor Company**, Connectivity & VEV Test Engineer (2021–2024): Python API-based test automation for connected-vehicle features, OTA update validation, ECU diagnostics (UDS), and FMEA-based root-cause analysis with global feature owners and suppliers.
- **Toyota Motor Corporation Australia**, Connected Multimedia Systems Test Engineer (2024): in-vehicle and bench testing across Lexus, Corolla Cross, Camry and RAV4.
- **RMIT University**, Graduate Researcher & Technical Specialist (2015–2021): cloud-based solutions for industry research, including an Azure telematics pipeline for 10,000+ daily events.
- Microsoft Azure Solution Architect Expert. Anthropic courses (2026): Building with the Claude API, Claude Code in Action, Introduction to Model Context Protocol.
