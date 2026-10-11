<p align="center">
  <img src="assets/profile-banner.png" alt="Muhib Karim: AI engineering, software verification and open source" width="100%">
</p>

# Muhib Karim

AI engineer · Software QA / verification and validation · Australia

I work on AI evaluation, API verification and practical software tools. My background is in automotive test engineering and cloud.

## Start with the evidence

| Project | What it does | What to inspect |
| --- | --- | --- |
| [agent-eval-harness](https://github.com/muhib-karim/agent-eval-harness) | Compares coding models and agent commands on the same tasks, using withheld pytest suites. | Task definitions, grading code and reproducible result records. |
| [api-vv-toolkit](https://github.com/muhib-karim/api-vv-toolkit) | Generates API tests from OpenAPI contracts and written requirements, with a traceability matrix. | Test generation, requirement mapping and report outputs. |
| [Rambler Bangla](https://github.com/muhib-karim/Rambler-Bangla) | A Bengali-first voice typing patch layer for Gboard 18.3.1. | Build instructions, static tests and source-only distribution notes. |
| [SONU](https://github.com/muhib-karim/sonu) | A Tauri desktop voice typing app with local speech-to-text models. | Rust and React implementation, setup docs and release information. |
| [Antigravity Claude Code Proxy](https://github.com/muhib-karim/Antigravity-Claude-Code-Proxy) | A local multi-provider gateway for Claude Code. | Provider adapters, configuration, test suite and security notes. |
| [HoliBooks](https://github.com/muhib-karim/HoliBooks) | A web reader for sacred texts from several religious traditions. | Reader implementation, data sources and local setup. |

The evaluation tools include offline or seeded examples. Those examples show the tools' behavior, not a measured ranking of live models or proof that an external service passes its requirements. Check each project's README for its current limits and verification scope.

## Engineering focus

- **AI evaluation:** repeatable tasks, withheld tests and inspectable results.
- **API verification:** OpenAPI contracts, requirements traceability and failure reporting.
- **Software delivery:** documented setup, test automation and clear operating limits.
- **Voice interfaces:** local speech-to-text and desktop tooling.

## How to review a project

Start with its README, reproduce the documented example, then inspect the tests and output artifacts. CI badges report the checks configured by that project; they do not replace end-to-end testing in your environment.
