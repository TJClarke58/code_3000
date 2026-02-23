# Security Policy

## Intended Users

This repository is intended for academic use in CSE 3000: Contemporary Issues in Computer Science and Engineering.

The intended users are:
- The repository owner (Thomas Clarke)
- The course instructor
- Teaching assistants for grading and review

---

## Security Risk Assessment

The overall security risk for this repository is low.

Potential risks if the repository content were misused include:

- **Academic Integrity Risk**: Other students could copy or reuse assignment solutions.
- **Accidental Exposure of Credentials**: If API keys, tokens, or passwords were mistakenly committed, they could be misused.
- **Local Environment Information**: File paths or development environment details could reveal minor personal system information.

This repository does not intentionally contain:
- Personal identifiable information (PII)
- Private keys
- Passwords
- API tokens
- Production credentials

---

## Security Measures Taken

The following steps have been taken to improve security:

- A `.gitignore` file is used to prevent committing unnecessary or sensitive files (e.g., virtual environments, cache files, `.env` files).
- No secrets, passwords, or private keys are stored in the repository.
- Only assignment-related materials are included.
- The repository is monitored before commits to ensure no sensitive information is uploaded.
- A `CODEOWNERS` file is included to clarify repository ownership.

---

## Reporting a Security Issue

If a security issue is discovered, please report it directly to the repository owner.
