# Branching Strategy

## Overview

To maintain a stable production environment, all code changes must first be pushed to the `dev` branch before being merged into the `main` (production) branch.

## Workflow

1. **Feature Development**: New features and fixes are developed in individual feature branches off the `dev` branch.
2. **Code Review**: Changes are reviewed and tested in the `dev` branch.
3. **Merge to Main**: Once approved, changes are merged into the `main` branch and deployed to production.

## Best Practices

- Always keep branches up-to-date with the latest `dev` changes.
- Use descriptive names for branches (e.g., `feature/add-login`, `fix/bug-123`).
