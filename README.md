<p align="center">
  <img src="assets/profile-banner.png" alt="muhib-karim: AI evaluation, verification and validation, developer tools. Test engineer turned AI builder. Software you can inspect." width="100%">
</p>

# muhib-karim

I work on AI engineering and software verification and validation (V&V). I came to software through automotive test engineering, so I build tools the way I was trained to test: written requirements, repeatable checks and evidence someone else can inspect.

Open to AI engineering and V&V roles in Australia.

## Projects

- **[agent-eval-harness](https://github.com/muhib-karim/agent-eval-harness)**: compares coding models and agent CLIs on the same tasks, with hidden pytest grading, unbiased pass@k and JSONL evidence with SHA-256 provenance. [Site](https://muhib-karim.github.io/agent-eval-harness/) [![CI](https://github.com/muhib-karim/agent-eval-harness/actions/workflows/ci.yml/badge.svg)](https://github.com/muhib-karim/agent-eval-harness/actions/workflows/ci.yml)
- **[api-vv-toolkit](https://github.com/muhib-karim/api-vv-toolkit)**: generates API tests from an OpenAPI 3.x spec and written requirements, runs them and reports a requirements traceability matrix with a CI exit-code gate. [Site](https://muhib-karim.github.io/api-vv-toolkit/) [![CI](https://github.com/muhib-karim/api-vv-toolkit/actions/workflows/ci.yml/badge.svg)](https://github.com/muhib-karim/api-vv-toolkit/actions/workflows/ci.yml)
- **[codegraph](https://github.com/muhib-karim/codegraph)**: indexes Python and Java into an embedded code graph and answers callers, inheritance, dead-code and change-impact queries with file:line evidence. [Site](https://muhib-karim.github.io/codegraph/) [![CI](https://github.com/muhib-karim/codegraph/actions/workflows/ci.yml/badge.svg)](https://github.com/muhib-karim/codegraph/actions/workflows/ci.yml)
- **[bangla-llm-eval](https://github.com/muhib-karim/bangla-llm-eval)**: a small, reproducible Bangla (Bengali) evaluation of LLMs: translation, NLI and Bengali numerals, with raw outputs and a live leaderboard. [Site](https://muhib-karim.github.io/bangla-llm-eval/) [![CI](https://github.com/muhib-karim/bangla-llm-eval/actions/workflows/ci.yml/badge.svg)](https://github.com/muhib-karim/bangla-llm-eval/actions/workflows/ci.yml)
- **[humming-keyboard](https://github.com/muhib-karim/humming-keyboard)**: private keyboard with offline voice typing: a FlorisBoard-based Android keyboard plus iPhone, Windows, macOS and Linux apps; Bangla phonetic typing. [Site](https://muhib-karim.github.io/humming-keyboard/) [![CI](https://github.com/muhib-karim/humming-keyboard/actions/workflows/quality.yml/badge.svg)](https://github.com/muhib-karim/humming-keyboard/actions/workflows/quality.yml)
- **[code-video-kit](https://github.com/muhib-karim/code-video-kit)**: 34 typed Remotion components for code and data videos, with a rendered gallery and measured render times. [Site](https://muhib-karim.github.io/code-video-kit/) [![CI](https://github.com/muhib-karim/code-video-kit/actions/workflows/ci.yml/badge.svg)](https://github.com/muhib-karim/code-video-kit/actions/workflows/ci.yml)

## Extended open source

- **[sonu](https://github.com/muhib-karim/sonu)**: private, offline voice typing for Windows, macOS and Linux, transcribing into any app with local Parakeet/Whisper/Moonshine models; an independent fork of [Handy](https://github.com/cjpais/Handy). [Site](https://muhib-karim.github.io/sonu/) [![CI](https://github.com/muhib-karim/sonu/actions/workflows/ci.yml/badge.svg)](https://github.com/muhib-karim/sonu/actions/workflows/ci.yml)
- **[Antigravity-Claude-Code-Proxy](https://github.com/muhib-karim/Antigravity-Claude-Code-Proxy)**: local Anthropic API gateway so Claude Code can use Gemini, Claude (via Google Cloud Code) and Perplexity; extends [antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy). [Site](https://muhib-karim.github.io/Antigravity-Claude-Code-Proxy/) [![CI](https://github.com/muhib-karim/Antigravity-Claude-Code-Proxy/actions/workflows/ci.yml/badge.svg)](https://github.com/muhib-karim/Antigravity-Claude-Code-Proxy/actions/workflows/ci.yml)

## Also public

- **[Rambler-Bangla-Public](https://github.com/muhib-karim/Rambler-Bangla-Public)**: a source-only, fail-closed patch layer that keeps Gboard 18.3.1 voice typing in Bengali script. Public source snapshot; no site or CI yet.

## How I work

- **Written requirements:** tests start from them, and results are reported in a traceability matrix.
- **Independent checks:** hidden pytest grading, a labelled retrieval evaluation, a spec validation gate.
- **Raw evidence kept:** JSONL with SHA-256 provenance, raw model outputs, file:line references.
- **CI:** runs on every repo that shows a badge here; each badge links to its workflow runs.

**Built with:** Python (pytest, pydantic, httpx), TypeScript (React, Remotion, zod), JavaScript (Node.js, Express), Rust (Tauri), Kotlin (Jetpack Compose), SwiftUI, tree-sitter, sherpa-onnx, MCP, GitHub Actions.
