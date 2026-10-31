# Contributing to ChoutesOS

Thank you for your interest in ChoutesOS. Contributions of all kinds are welcome, including bug reports, documentation, testing, translations, and code.

By participating in this project you agree to follow the [Code of Conduct](https://github.com/ChoutesOS/.github/blob/main/CODE_OF_CONDUCT.md).

## Reporting problems and suggesting features

- Search [existing issues](https://github.com/ChoutesOS/choutesos/issues) and [discussions](https://github.com/ChoutesOS/choutesos/discussions) first.
- Use the [issue forms](https://github.com/ChoutesOS/choutesos/issues/new/choose) so that reports include the details needed to reproduce a problem.
- Ask questions in [Discussions](https://github.com/ChoutesOS/choutesos/discussions) rather than in issues.
- Report security vulnerabilities privately, as described in the [security policy](https://github.com/ChoutesOS/.github/blob/main/SECURITY.md).

## Submitting changes

1. Fork the repository and create a branch from `main`.
2. Make your change, keeping it focused on a single purpose.
3. Test it. For changes to images, installer, or boot configuration, boot the result in a virtual machine (UEFI and BIOS where relevant) before opening a pull request.
4. Add an entry under **Unreleased** in `CHANGELOG.md` for any user-visible change.
5. Open a pull request against `main` and fill in the pull request template.

Do not commit secrets, private keys, passwords, or access tokens. Pull requests that include them will be closed.

## Commit messages

This project uses [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/). Each message has the form:

```
<type>(<optional scope>): <short summary in the imperative mood>
```

Common types:

| Type | Use for |
| --- | --- |
| `feat` | A new feature |
| `fix` | A bug fix |
| `docs` | Documentation only |
| `style` | Formatting with no change in behavior |
| `refactor` | Code change that neither fixes a bug nor adds a feature |
| `perf` | A performance improvement |
| `test` | Adding or correcting tests |
| `build` | Build system or packaging changes |
| `ci` | Continuous integration changes |
| `chore` | Maintenance tasks |
| `revert` | Reverting an earlier commit |

Append `!` after the type or scope, or add a `BREAKING CHANGE:` footer, for changes that are not backward compatible.

## Versioning

ChoutesOS projects follow [Semantic Versioning](https://semver.org/spec/v2.0.0.html), and changes are recorded in each repository's `CHANGELOG.md` using the [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) format.

## License

Unless a repository states otherwise, contributions are licensed under the GNU General Public License, version 3 or (at your option) any later version.
