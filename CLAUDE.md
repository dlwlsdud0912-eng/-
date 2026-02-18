# CLAUDE.md

## Project Overview

This is a new project repository in its initial setup phase.

## Repository Structure

```
/
├── README.md          # Project README
├── CLAUDE.md          # AI assistant guide (this file)
├── package.json       # Node.js project configuration
└── node_modules/      # Dependencies (git-ignored)
```

## Development Setup

### Prerequisites

- Node.js (LTS recommended)
- npm

### Installation

```bash
npm install
```

### Available Scripts

```bash
npx playwright test          # Run Playwright end-to-end tests
npx playwright test --ui     # Run tests with interactive UI
npx playwright show-report   # Show HTML test report
npx playwright codegen       # Generate tests by recording actions
```

## Testing

This project uses [Playwright](https://playwright.dev/) for end-to-end testing.

- Test files should be placed following Playwright conventions (e.g., `tests/` directory)
- Run `npx playwright test` to execute all tests
- Run `npx playwright install` if browser binaries need to be installed

## Key Conventions

- Primary language: Korean context (README uses Korean)
- Package manager: npm
- Testing framework: Playwright

## Notes for AI Assistants

- This project is in early development; structure will evolve
- Update this file as new tools, frameworks, or conventions are added
- Check `package.json` scripts for the latest available commands
