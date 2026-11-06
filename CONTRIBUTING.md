# How we work on GitHub

1. Open an issue with a form. One issue is one outcome.
2. Write in plain English: active voice, one instruction per sentence, at most 20 words per sentence.
3. Give the issue at least one `area:` label and exactly one `priority:` label. The form does this for you.
4. Assign yourself before you start. Comment `Started.` on the issue.
5. Work on a branch named `<type>/<issue number>-<short name>`, for example `fix/12-draft-save`.
6. Open one pull request per issue. The first line of the body is `Closes #<issue number>`.
7. Fill in Why, What changed, Tests and Not verified. Keep the PR a draft until the tests pass.
8. Merge with squash when the checks are green. The issue closes by itself.

The full rules live in `org-skills/donmor-github-workflow`.
