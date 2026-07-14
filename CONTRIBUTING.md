# Contributing

Thank you for your interest in the Automation Architect Toolkit.

Although this project is currently maintained by a single developer, it follows professional engineering practices intended for collaborative software development.

## Goals

The primary goals of this project are:

- Demonstrate modern automation engineering practices.
- Showcase scalable framework architecture.
- Explore current industry-standard testing technologies.
- Provide production-quality reference implementations.
- Continuously improve through incremental development.

## Development Principles

Every contribution should strive to improve one or more of the following:

- Readability
- Maintainability
- Scalability
- Testability
- Documentation

Code should favor clarity over cleverness.

## Commit Messages

This repository follows the Conventional Commits specification.

Examples:

feat: add Playwright page object base class

fix: resolve flaky authentication fixture

docs: update project roadmap

refactor: simplify configuration loading

test: add API integration tests

ci: configure GitHub Actions workflow

chore: initialize repository structure

## Branch Strategy

Feature work should be developed on feature branches whenever practical.

Examples:

feature/playwright-framework

feature/docker-support

feature/api-testing

bugfix/config-loader

docs/readme-update

## Documentation

Every significant feature should include:

- Updated README documentation (if applicable)
- Usage examples
- Design rationale when appropriate

## Code Quality

Before merging changes:

- Code builds successfully
- Tests pass
- No compiler warnings
- Documentation updated where necessary

## Philosophy

This repository emphasizes long-term maintainability over short-term convenience.

When multiple solutions are possible, prefer the solution that is easiest to understand and maintain.

## Decision Making

Before implementing a feature, consider:

- Is this abstraction actually necessary?
- Will this still make sense six months from now?
- Can another engineer unstand it without explanation?
- Does it solve today's problem without overengineering tomorrow's?