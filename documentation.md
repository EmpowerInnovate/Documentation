# Project Contribution Guidelines

This document defines the standards and best practices for contributing to the project. All contributors are expected to follow these guidelines when committing code, creating issues, and working with branches.

---

## Commit Guidelines

- **Commit Messages**
  - Use clear, descriptive commit messages.
  - Follow the format: `<type>(<scope>): <description>`
    - **type**: feat, fix, docs, refactor, test
    - **scope**: module or component name (optional)
    - **description**: short explanation in present tense
  - Example: `fix(add): Added images in mountpath dir`

- **Commit Practices**
  - Keep commits focused on a single purpose.
  - Avoid committing unnecessary files (use `.gitignore` effectively).
  - Write meaningful descriptions in extended messages if needed.

---

## Issue Creation Guidelines

- **When to Create an Issue**
  - Reporting a bug.
  - Requesting a new feature or enhancement.
  - Documenting or clarifying existing functionality.
  - Tracking technical debt or refactor work.

- **Issue Format**
  - **Title**: Clear and concise.
  - **Description**: Provide enough detail to understand the problem or request.
  - **Steps to Reproduce** (for bugs): List exact steps and expected vs actual results.
  - **Labels**: Use appropriate labels (e.g., bug, enhancement, documentation).

---

## Branching Guidelines

- **When to Create a Branch**
  - For new features.
  - For bug fixes.
  - For significant documentation updates.
  - For experiments that may be merged later.

- **Branch Naming Convention**
  - Use lowercase with hyphens.
  - Format: `<type>/<short-description>`
    - **type** examples: `feature`, `fix`, `docs`
    - Example: `feature/adding-image-upload-button` or `fix/slownessFix`

- **Best Practices**
  - Always branch out from the latest `master` or `develop` branch.
  - Keep branches small and purpose-driven.
  - Delete branches after merging to keep repository clean.

---

## Review and Merge Process

- All branches must go through a pull request process.
- Ensure all unit tests and CI checks pass before requesting review.
- At least one reviewer approval is required before merging.
- Use **squash and merge** or **rebase and merge** to maintain a clean history.

---
