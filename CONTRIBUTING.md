# Contributing to OpenLiqd

Start with the target repository's README and contribution guide. Repository-specific instructions take precedence over this shared baseline.

The `openliqd/.github` profile repository accepts pull requests from collaborators with write access only. Other repositories define their own contribution policy.

## Keep changes focused

Use one branch and pull request per coherent change. Explain substantial changes in an issue before implementing them. For this profile repository, contributions should improve presentation, accessibility, documentation or link accuracy.

## Commits and PR titles

Use Conventional Commits:

```text
type(scope): describe the change
```

Use `feat`, `fix`, `docs`, `refactor`, `perf`, `test`, `build`, `ci`, `chore`, `style` or `revert`. Scope is optional; choose a meaningful area such as `profile` or `docs`. Write in English, use the imperative mood, keep the first line within 72 characters and omit the trailing period.

Examples:

```text
docs(profile): explain wallet-based liquidity
fix(profile): correct the documentation link
```

Use `!` and explain the migration when a change breaks a public contract. Follow any additional commit validation configured in the target repository.

## Write for the reviewer

Lead with the concrete change and its effect. Explain the motivation and any material risk. A small change usually needs one or two paragraphs. Include a screenshot, before/after example or diagram when it helps the reviewer understand the result.

Describe the final state of the whole PR. Update the title and body when its scope changes. Link issues only when relevant; use `Fixes #123` only when merging should close that issue.

For behavioral changes, include meaningful validation and disclose anything untested. For this documentation-only repository, check links, image rendering and factual accuracy. Do not add empty headings, boilerplate checklists or unrelated test output.

## Ground public claims in evidence

Distinguish designs, local experiments, fork measurements and public deployments. Report benchmark conditions and limitations alongside results. Describe audits or reviews only when they have actually taken place. Never include credentials, private operational notes or unpublished personal information.
