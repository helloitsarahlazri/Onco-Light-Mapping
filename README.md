# Onco Light Mapping

Light-weight utilities for mapping, preprocessing and exploring oncology-related datasets (gene expression, pathology metadata, clinical annotations). This project provides a small Python package, example scripts, and tests to get you started mapping and transforming oncology light datasets into analysis-ready formats.

Features
- Small, testable Python package under `src/onco_light_mapping`.
- Example mapping function and unit test.
- CI pipeline (GitHub Actions) to run tests on push/PR.
- Template files: LICENSE, CONTRIBUTING, CODE_OF_CONDUCT.

Quickstart (local)
1. Create and activate a virtual environment
   - python -m venv .venv
   - source .venv/bin/activate  (Mac/Linux) or .venv\Scripts\activate (Windows)
2. Install dependencies
   - pip install -r requirements.txt
3. Run tests
   - pytest

Development
- Package layout uses `src/` layout to avoid import issues during testing.
- Add functions under `src/onco_light_mapping` and corresponding tests under `tests/`.

Repository structure
- src/onco_light_mapping/      -- package code
- tests/                       -- unit tests
- .github/workflows/           -- CI
- README.md, LICENSE, requirements.txt, .gitignore

License
This repository is provided under the MIT License. See LICENSE for details.

Contact
Maintainer: helloitsarahlazri