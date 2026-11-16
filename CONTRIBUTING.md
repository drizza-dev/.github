# Contributing to drizza

Thanks for your interest in contributing. This guide applies to every public repository in the `drizza-dev` organization unless a repository ships its own `CONTRIBUTING.md`.

By participating, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md). To report a security issue, do not open a public issue; follow [SECURITY.md](SECURITY.md) instead.

## Local setup

Requirements:

- Node.js `^22.13.0 || >=23.4.0`
- [pnpm](https://pnpm.io)

```sh
git clone https://github.com/drizza-dev/drizza.git
cd drizza
pnpm install
```

Start the development server:

```sh
pnpm dev
```

## Build

```sh
pnpm build
```

Run the build before opening a pull request. A PR that does not build will not be merged.

## Tests

The test suite is still being set up. Until it lands, describe in your PR how you verified the change by hand (what you ran, what you clicked, what you observed).

## Branches and commits

- Branch off `main` and keep one topic per branch.
- Commit messages follow [Conventional Commits](https://www.conventionalcommits.org) with an emoji prefix, for example:

  ```
  ✨ feat(briefing): group Slack threads by channel
  🐛 fix(server): reject requests from non-loopback origins
  📝 docs: clarify MCP setup
  ```

## Pull requests

- Keep PRs small and focused. Several small PRs are easier to review than one large one.
- Fill in the PR template: what changes, how you verified it, and what you did not verify.
- Link the related issue when there is one.
- For larger changes, open an issue or a Discussion first so we can agree on the approach before you write the code.

## Code comments

Do not leave prose comments in the code explaining why a change was made, what was tried, or how a decision was reached. That context belongs in the commit message and the PR description, where it can be reviewed and does not go stale inside the file.

Tool directives (such as `eslint-disable` or `@ts-expect-error`) are fine. If a piece of code genuinely cannot be understood without a comment, raise it in the PR and we will decide together.

## Questions

Use [GitHub Discussions](https://github.com/drizza-dev/drizza/discussions) for questions and ideas. Issues are for confirmed bugs and concrete feature requests.
