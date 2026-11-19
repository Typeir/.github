# Contributing

This is a personal project, but you can contribute, if you want to. I do not guarantee that I will even look at your contribution.

## Code of Conduct

Follow the [CODE OF CONDUCT](./CODE_OF_CONDUCT.md)

## Questions

Ask an LLM, get off my back I'm not your dad.

## Reporting Bugs

Search open issues first. Provide replicable steps. Provide one or several TDD files that prove the issue. Tagged with _bug_.

Just create a PR instead, please.

Follow the [CODE OF CONDUCT](./CODE_OF_CONDUCT.md)
[BUG REPORT](./.github/ISSUE_TEMPLATE/bug_report.md)

## Suggesting Changes

Tagged as a _suggestion_.

Just create a PR instead, please.

Follow the [CODE OF CONDUCT](./CODE_OF_CONDUCT.md)
[FEATURE REQUEST](./.github/ISSUE_TEMPLATE/feature_request.md)

## Pull Requests

Don't create random Pull Requests, follow the [template](.github/PULL_REQUEST_TEMPLATE.md)

## Style

Follow the [template](.github/PULL_REQUEST_TEMPLATE.md) for PRs.

Don't use the forums as a chat.

Commits follow [Conventional Commits](https://www.conventionalcommits.org/):

`<type>(<module>): <description>`

| Type       | Use for                                        |
| ---------- | ---------------------------------------------- |
| `feat`     | New functionality                              |
| `fix`      | Bug fixes                                      |
| `docs`     | Documentation only                             |
| `style`    | Formatting, no logic changes                   |
| `refactor` | Code changes that neither fix nor add features |
| `perf`     | Performance improvements                       |
| `test`     | Adding or fixing tests                         |
| `build`    | Build system or dependencies                   |
| `ci`       | Pipeline configuration                         |
| `chore`    | Maintenance that doesn't touch src or tests    |
| `revert`   | Reverting a previous commit                    |

You may use different types if you want and they are justified, but don't get creative.

Breaking changes add a `!` after the scope: `feat(api)!: drop v1 endpoints, no replacement added`

For dirty commits that may contain unfocused or unrelated changes or random garbage wrap the type in brackets: `[<type>](<module>): <description>`

- `[chore](wiki): misc cleanup while fixing links, may have deleted five files`

Examples:

- `[feat](dither): add my new made up matrix algo`
- `fix(wiki): correct broken heirloom links, break three more`
- `chore(deps): bump next to 15.2, break the build`

## AI Use

Refer to the [AI DISCLAIMER](https://github.com/Typeir/.github/blob/main/AI_DISCLAIMER.md)

## License

Refer to the [LICENSE](./LICENSE)
