# .github

Default files for every Don-Mor Software Group repository that has none of its own.

| File | What it does |
|---|---|
| `.github/ISSUE_TEMPLATE/*.yml` | One form per issue type. Each form sets the type, asks for the area and priority, and asks for Why, What and Done when. |
| `.github/ISSUE_TEMPLATE/config.yml` | Turns off blank issues. |
| `.github/PULL_REQUEST_TEMPLATE.md` | The PR body: Closes, Why, What changed, Tests, Not verified. |
| `CONTRIBUTING.md` | The eight rules, shown as a link on every new issue and PR. |

A repository with its own `.github/ISSUE_TEMPLATE` folder does not use these forms.

Change a file here, open a pull request, merge. Every repository picks it up at once.
