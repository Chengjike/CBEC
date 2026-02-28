# Contributing to CBEC

Thank you for your interest in contributing to CBEC! This document provides guidelines and instructions for contributing to the project.

## Code of Conduct

Please be respectful and considerate of others when contributing to this project.

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR_USERNAME/CBEC.git`
3. Create a new branch: `git checkout -b feature/your-feature-name`
4. Make your changes
5. Run tests: `npm test`
6. Commit your changes: `git commit -m "Add your feature"`
7. Push to your branch: `git push origin feature/your-feature-name`
8. Open a Pull Request

## Development Workflow

### Prerequisites
- Node.js 16+
- PostgreSQL 12+
- Git

### Setup Development Environment

1. Install dependencies: `npm install`
2. Copy environment file: `cp .env.example .env`
3. Update `.env` with your configuration
4. Start the development server: `npm run dev`

### Testing

- Run all tests: `npm test`
- Run tests with coverage: `npm test -- --coverage`
- Run specific test file: `npm test -- path/to/test/file.js`

## Code Style

- Use ESLint for JavaScript/TypeScript code
- Follow the existing code formatting style
- Write meaningful commit messages
- Add comments for complex logic

## Pull Request Process

1. Ensure your code passes all tests
2. Update documentation if needed
3. Add or update tests for new functionality
4. Ensure your branch is up to date with main
5. Request review from maintainers

## Reporting Issues

When reporting issues, please include:
- Steps to reproduce
- Expected behavior
- Actual behavior
- Environment details (OS, Node version, etc.)
- Screenshots if applicable

## Feature Requests

Feature requests are welcome! Please:
- Describe the feature in detail
- Explain the use case
- Suggest implementation approach if possible

## License

By contributing, you agree that your contributions will be licensed under the project's MIT License.