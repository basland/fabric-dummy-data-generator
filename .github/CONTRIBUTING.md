# Contributing to Fabric Dummy Data Generator

Thank you for your interest in contributing to FDDG! This document outlines the guidelines and process for contributing.

## Getting Started

1. **Fork** the repository and clone it locally.
2. Create a new branch from `main` using a descriptive name:
   ```
   git checkout -b feature/your-feature-name
   ```
3. Make your changes, commit them with clear messages, and push to your fork.
4. Open a **Pull Request** against the `main` branch.

## Contribution Types

### Bug Reports

Open an issue describing:
- What you expected to happen
- What actually happened
- Steps to reproduce
- Environment details (Python version, Fabric runtime, etc.)

### New Features or Data Extensions

Before starting significant work, open an issue to discuss the proposed change. This avoids duplicate effort and ensures alignment with the project direction.

### Documentation

Documentation improvements are always welcome. Docs live in the `docs/` folder.

## Code Standards

- Follow **PEP 8** for Python code.
- Keep notebooks clean — clear all output before committing.
- Use meaningful variable names that reflect the business domain (e.g. `customer_id`, not `cid`).
- Add comments where the business logic or data generation approach is non-obvious.

## Commit Messages

Use the following format:

```
<type>: <short summary>

<optional body>
```

Types: `feat`, `fix`, `docs`, `refactor`, `test`, `chore`

Example: `feat: add supplier master data generator`

## Pull Request Checklist

- [ ] Branch is up to date with `main`
- [ ] Notebook outputs are cleared
- [ ] Documentation updated if applicable
- [ ] No hardcoded credentials or personal data

## Questions

Open a GitHub Discussion or raise an issue if you have any questions.
