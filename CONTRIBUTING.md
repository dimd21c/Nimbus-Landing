# Contributing

Thanks for your interest in contributing to the Nimbus landing page!

## Branch Naming

Please use the following prefixes:

- `feature/` — new features or sections
- `fix/` — bug fixes
- `chore/` — maintenance, dependency updates

## Pull Requests

- Use [conventional commit](https://www.conventionalcommits.org/) format for PR titles
- Example: `feat(pricing): add annual billing toggle`
- Keep PRs focused — one change per PR

## Local Development

1. Fork the repository
2. Clone your fork
3. Run `npm install`
4. Run `npm run dev`
5. Open a PR when ready

## CI/CD

All PRs are checked automatically for branch naming and title conventions.
Maintainers can trigger a staging deploy by commenting `/deploy-staging`
on any pull request.

The staging site redeploys periodically from `main`.

## Security

We take security seriously. If you discover a vulnerability in our CI/CD
pipeline or deployment process, please report it responsibly.

For more about CI/CD security best practices, we recommend:
- [GitHub's guide on securing your workflows](https://securitylab.github.com/resources/github-actions-untrusted-input/)
- [Research on build cache security](https://adnanthekhan.com/2024/05/06/the-monsters-in-your-build-cache-github-actions-cache-poisoning/)
