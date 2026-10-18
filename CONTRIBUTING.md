# Contributing

Thanks for your interest in contributing! This document explains how to get
started.

## Code of Conduct

By participating in this project, you agree to abide by our
[Code of Conduct](CODE_OF_CONDUCT.md).

## How to Contribute

### Reporting Bugs

Open an issue using the **Bug report** template and include:

- A clear description of the problem
- Steps to reproduce
- Expected vs. actual behavior
- Environment details (OS, version, etc.)

### Suggesting Features

Open an issue using the **Feature request** template and describe:

- The problem you are trying to solve
- Your proposed solution
- Any alternatives you considered

### Submitting Changes

1. Fork the repository and create a branch from `main`:

   ```bash
   git checkout -b feat/short-description
   ```

2. Make your changes following the project's style.
3. Add or update tests where applicable.
4. Run the test suite and linters locally.
5. Commit using clear, descriptive messages (see [Commit Messages](#commit-messages)).
6. Push your branch and open a Pull Request.

## Commit Messages

Follow the [Conventional Commits](https://www.conventionalcommits.org/) format:

```
<type>(<scope>): <description>

[optional body]

[optional footer]
```

Common types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`.

## Pull Request Guidelines

- Keep PRs focused and reasonably small.
- Reference related issues (e.g. `Closes #123`).
- Ensure CI passes before requesting review.
- Update documentation when behavior changes.

## Development Setup

Describe how to set up a local development environment, run tests, and lint:

```bash
# Install dependencies
# Run tests
# Run linters
```

## Questions

For general questions, open a discussion or an issue. We appreciate your help!
