# Contributing

This guide applies to every repository in the `inteliwertai` organization that does not
have its own `CONTRIBUTING.md`.

## Each repository's own docs come first

A repository's `README.md`, and its `AGENTS.md` or `CLAUDE.md` where it has one, are
authoritative for that repository: read them before you change anything. They apply to
people and to coding agents alike.

## Workflow

1. Open or pick an issue. A larger change needs a written design first; link it from
   the issue.
2. Work on a short-lived branch and open a pull request into `main`. Fill in the pull
   request template.
3. Run the repository's checks locally before asking for review. A pull request merges
   only when CI is green. Never weaken a check, lower a threshold or skip a test to get
   there.
4. Keep commits small and name them `<area>: <what>`.

## Security

Do not report vulnerabilities in issues or pull requests. Follow the
[security policy](https://github.com/inteliwertai/.github/blob/main/SECURITY.md) and report
privately.

## License

Contributions to a public repository are made under that repository's license. The
Inteliwert name and logos are not covered by it.
