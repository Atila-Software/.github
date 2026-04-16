# Contributing to Atila Software Repositories

Thank you for contributing to Atila Software projects. This guide defines the baseline workflow for repositories in this organization. Individual repositories may add project-specific instructions in their own `README.md` or documentation.

## Branching

- `main` is the protected, stable branch. It should always represent production-ready or release-ready work.
- `develop` may be used when a repository needs an integration branch before release.
- `feature/...` branches are used for new functionality.
- `fix/...` branches are used for bug fixes.
- `hotfix/...` branches are used for urgent production fixes.

Use short, descriptive branch names:

```text
feature/customer-search
fix/login-validation
hotfix/payment-timeout
```

## Commits

Write commits that are clear and easy to review.

- Use imperative, concise messages.
- Keep each commit focused on one logical change.
- Reference an issue or ticket when one exists.
- Avoid vague messages such as `changes`, `fix`, or `update`.

Examples:

```text
Add customer search filters
Fix login validation for inactive users
Update Docker setup for local SQL Server
```

## Pull Requests

All code changes should go through a pull request unless the repository maintainer defines a different emergency process.

Every pull request should include:

- A clear summary of the change
- Why the change is needed
- Steps used to test the change
- Screenshots or videos when the change affects UI
- Notes about migrations, breaking changes, or deployment impact

Before requesting review:

- Run the relevant tests or checks locally.
- Confirm the branch is up to date with its target branch.
- Remove debugging code, temporary logs, and unused files.
- Update documentation when behavior, setup, or configuration changes.

## Reviews

- At least one review is required before merging.
- Reviewers should focus on correctness, maintainability, security, and user impact.
- Authors are responsible for responding to comments and keeping the pull request current.
- Prefer small pull requests. Large changes should be split when practical.

## Testing

Testing expectations depend on the repository, but contributors should verify the behavior they changed.

Examples include:

- Unit tests for business logic
- Widget or integration tests for Flutter flows
- API tests for backend changes
- Manual testing notes for UI or operational workflows
- Database migration checks when schema changes are included

## Security and Sensitive Data

Never commit secrets, credentials, private keys, production data, or customer-sensitive information. If you find a security issue, follow `SECURITY.md` instead of opening a public issue.

