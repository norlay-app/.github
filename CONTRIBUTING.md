# Contributing to Norlay

Thanks for helping. These are small products with narrow jobs, and the rules are
short on purpose.

## Before you start

- Open an issue for anything larger than a typo or a small fix, so the design can
  be agreed before code is written.
- Read `SECURITY.md` if your report is a security problem. Do not open a public
  issue for it.
- Read `CODE_OF_CONDUCT.md`. It applies in every Norlay space.

## Where things live

| Repository | What belongs there |
|---|---|
| `norlay-link-checker` | The NVDA add-on: source, tests, build, releases |
| `norlay-releases` | Release notes and downloadable builds for Norlay and Norlay Code |
| `.github` | The organization profile and the default community health files |

The source of Norlay and Norlay Code is not published. Bug reports about them are
still welcome as issues on this organization.

## House style

- Plain, calm sentences in user-facing text. Say what happened and what to do
  next; do not blame the user.
- Accessibility is a requirement, not a review pass. If a change cannot be used
  with a screen reader and a keyboard alone, it is not finished.
- Keep pull requests focused, and say what you tested.
- Never commit a key, a token, or someone's personal data.

Each product repository has its own build and test instructions. Use those.

## Pull requests

1. Describe the problem, not just the patch.
2. Run the tests the repository documents, and the build if there is one.
3. If you changed behaviour, update the changelog and the help text in the same
   pull request.
4. By contributing you agree that your work is licensed under the same licence as
   the repository you are contributing to.
