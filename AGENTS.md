# Repository privacy

This is a public repository for reusable skill instructions and packaging files. Keep episode assets, transcripts, generated outputs, private reports, credentials, environment files, and personal contact information out of all published files and Git history.

Retain the copyright holder's name in `LICENSE` only. Use `YouTube Film Crew` as the Git author and committer name, with an empty email address. Configure this repository locally before committing; do not change the user's global Git identity:

```sh
git config --local user.name 'YouTube Film Crew'
git config --local user.email ''
git config --local user.useConfigOnly true
```

Before pushing, inspect the staged file list, run an available secret scanner with redacted output, and verify the author and committer metadata of outgoing commits. Do not include private data in commit messages, pull requests, or other public repository text. Keep audit reports and any recovery backups outside this repository.
