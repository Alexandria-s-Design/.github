# Contributing to Alexandria's Design Projects

Thank you for your interest in contributing to Alexandria's Design projects! We welcome contributions from the community to help improve our educational technology solutions.

## Getting Started

Before you begin:
1. Review the project's README.md to understand its purpose and architecture
2. Check the existing issues to see if your concern or feature has been discussed
3. Read through this contributing guide

## How to Contribute

### Reporting Issues

When reporting issues, please include:
- **Clear title**: Brief description of the problem
- **Detailed description**: What happened vs. what you expected
- **Steps to reproduce**: Numbered list of steps
- **Environment**: OS, browser, versions, relevant configuration
- **Screenshots**: If applicable
- **Error messages**: Full stack traces or error logs

### Suggesting Features

Feature suggestions are welcome! Please:
- Check if the feature has already been requested
- Explain the use case and benefits
- Provide examples or mockups if possible
- Consider backward compatibility

### Submitting Code Changes

#### 1. Fork and Clone

```bash
# Fork the repository via GitHub UI first, then:
git clone https://github.com/YOUR-USERNAME/REPO-NAME.git
cd REPO-NAME
git remote add upstream https://github.com/Alexandria-s-Design/REPO-NAME.git
```

#### 2. Create a Branch

```bash
git checkout -b feature/your-feature-name
# or
git checkout -b fix/your-bug-fix
```

Branch naming conventions:
- `feature/` - New features
- `fix/` - Bug fixes
- `docs/` - Documentation changes
- `refactor/` - Code refactoring
- `test/` - Test additions or fixes

#### 3. Make Your Changes

Follow these guidelines:
- **Code style**: Match the existing code style
- **Comments**: Add comments for complex logic
- **Tests**: Add or update tests when applicable
- **Documentation**: Update README or docs if needed
- **Commits**: Use clear, descriptive commit messages

#### 4. Commit Your Changes

```bash
git add .
git commit -m "Clear description of your changes"
```

Commit message format:
```
<type>: <subject>

<body (optional)>

<footer (optional)>
```

Types:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Test additions or modifications
- `chore`: Build process or auxiliary tool changes

Example:
```
feat: Add dark mode toggle to dashboard

Implements user-requested dark mode feature with toggle
in settings panel. Persists preference to localStorage.

Closes #123
```

#### 5. Push and Create Pull Request

```bash
git push origin feature/your-feature-name
```

Then create a pull request via GitHub:
1. Go to the original repository
2. Click "New Pull Request"
3. Select your fork and branch
4. Fill in the PR template with details

### Pull Request Guidelines

Your PR should:
- Have a clear title and description
- Reference related issues (e.g., "Closes #123")
- Include test results if applicable
- Be focused on a single feature or fix
- Have clean, readable code
- Follow the project's code style

## Code Standards

### General Principles

- **Clarity over cleverness**: Write code that's easy to understand
- **DRY (Don't Repeat Yourself)**: Avoid code duplication
- **KISS (Keep It Simple)**: Avoid unnecessary complexity
- **Consistency**: Follow existing patterns

### JavaScript/Node.js

- Use ES6+ features where appropriate
- Use `const` by default, `let` when reassignment needed
- Use template literals for string interpolation
- Use async/await for asynchronous code
- Use meaningful variable and function names

### HTML/CSS

- Use semantic HTML5 elements
- Follow BEM or similar naming convention for CSS
- Ensure responsive design
- Test cross-browser compatibility
- Optimize for accessibility (WCAG guidelines)

### Documentation

- Update README.md for significant changes
- Add JSDoc comments for functions and classes
- Include examples in documentation
- Keep documentation current with code

## Testing

- Write tests for new features
- Ensure existing tests pass
- Aim for good test coverage
- Test edge cases

## Code Review Process

1. Automated checks run (linting, tests)
2. Maintainer reviews code
3. Changes requested (if needed)
4. You address feedback
5. PR is approved and merged

## Community Guidelines

- Be respectful and inclusive
- Provide constructive feedback
- Help others learn and grow
- Follow the [Code of Conduct](CODE_OF_CONDUCT.md)

## Questions?

If you have questions about contributing:
- Check the project's README.md
- Review existing issues and PRs
- Ask in the issue or PR comments
- Email: cmartin@alexandriasdesign.com

## License

By contributing, you agree that your contributions will be licensed under the same license as the project.

---

Thank you for contributing to Alexandria's Design! Your efforts help us build better educational technology solutions for schools and districts worldwide.
