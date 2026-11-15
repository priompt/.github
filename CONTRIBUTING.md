# Contributing to Priompt

Thanks for helping. These rules apply to every repository in the
[priompt](https://github.com/priompt) organisation unless a repository has its
own `CONTRIBUTING.md`.

## 1. Pick an issue and claim it first

1. Find an open issue. Every issue explains the problem, how to reproduce it,
   what "fixed" looks like, and where to start in the code.
2. **Comment on the issue to claim it** ("I'd like to work on this") and
   **wait until a maintainer assigns it to you** before opening a pull request.
3. Check that nobody else is assigned and that no pull request is already open
   for it.

Pull requests for issues that are not assigned to their author may be closed,
even if the change is good: someone else may already be working on it.

## 2. Good first issues are for learning

Issues labelled
[`good first issue`](https://github.com/search?q=org%3Apriompt+is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22&type=issues)
are reserved for **people making their first open-source contributions**,
such as students learning how a real project works. They are kept small and
well-explained on purpose.

- If you have already contributed to Priompt or have a track record of
  open-source contributions, please leave them for newcomers and pick a
  [`help wanted`](https://github.com/search?q=org%3Apriompt+is%3Aissue+is%3Aopen+label%3A%22help+wanted%22&type=issues)
  issue instead. Those are where experienced help makes the biggest difference.
- One good first issue per person. After your first merged pull request, move
  on to `help wanted` issues.

## 3. Limits

- At most **2 open pull requests** per contributor across the organisation.
- At most **2 assigned issues** per contributor at a time. If you can no longer
  work on one, say so on the issue so it can be reassigned.

## 4. AI-assisted contributions

You may use AI tools. You are responsible for the result:

- Say in the pull request that AI tools were used.
- Understand every line you submit, and be able to explain and change it in
  review.
- Spend that effort on substantial `help wanted` issues. Please do not use AI
  tools to work through good first issues: they exist so that people can learn
  by doing them.
- Bulk or automated pull requests that do not follow these rules will be
  closed.

## 5. Make the change

1. **Fork** the repository and create a branch in your fork. Nobody pushes to
   the organisation's repositories directly; everything goes through forks.
2. Make the change. Keep it focused on the issue.
3. Run the tests. Each repository's README says how (`go test ./...`,
   `npm test`, `pytest`, `pnpm check && pnpm test`).
4. Add or update a test that fails before your change and passes after it,
   where that is practical.

## 6. Open the pull request

- Open it from your fork against `main`.
- Put `Fixes #<issue number>` in the description.
- Fill in the pull request template.
- A maintainer (@sujal-maheshwari2004, @iamDyeus or @guptadevik2003) reviews
  every pull request. CI must pass. Be ready to make changes after review.

## Questions

Ask on the issue, or in the Priompt Discord: https://discord.gg/vaZFMQtWc
