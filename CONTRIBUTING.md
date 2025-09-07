# Contributing

Thank you for your interest in contributing to this project! We welcome contributions from everyone.

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check existing issues to avoid duplicates. When creating a bug report, include:

- A clear and descriptive title
- Steps to reproduce the issue
- Expected behavior vs actual behavior
- Environment details (OS, version, etc.)

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, include:

- A clear and descriptive title
- A detailed description of the proposed enhancement
- Explain why this enhancement would be useful

### Pull Requests

1. Fork the repo and create your branch from `main`
2. If you've added code that should be tested, add tests
3. Ensure the test suite passes
4. Make sure your code follows the existing style
5. Write a clear commit message
6. Create a pull request

## Development Process

### Setup

1. Fork and clone the repository
2. Follow setup instructions in the [README](README.md)
3. Create a new branch for your changes

### Making Changes

- Write clear, self-documenting code
- Add tests for new functionality
- Update documentation as needed
- Follow existing code style and conventions

### Commit Messages

This project follows the [Conventional Commits](https://www.conventionalcommits.org/) specification. All commit messages must be structured as follows:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

**Types:**
- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that do not affect the meaning of the code (white-space, formatting, etc.)
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to the build process or auxiliary tools

**Breaking Changes:**
Breaking changes should be indicated by adding `!` after the type/scope or by including `BREAKING CHANGE:` in the footer:

```
feat!: remove deprecated login method

BREAKING CHANGE: The legacy login() method has been removed. Use authenticateUser() instead.
```

**Examples:**
- `feat: add user authentication`
- `fix: resolve memory leak in data processing`
- `docs: update API documentation`
- `feat(auth): implement OAuth2 integration`
- `feat!: change API response format`
- `fix(api)!: remove support for legacy endpoints`

### Testing

Run the test suite to ensure your changes don't break existing functionality:

```bash
# Add test commands here
```

## Style Guide

- Follow the existing code style in the project
- Use meaningful variable and function names
- Follow the Conventional Commits standard for commit messages
- Keep changes focused and atomic

## License

By contributing, you agree that your contributions will be licensed under the same license as the project.