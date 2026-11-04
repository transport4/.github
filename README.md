# Transport4 GitHub configuration

This repository contains shared GitHub configuration for the Transport4
organization. It provides a consistent pull request format that applies across
repositories.

## Contents

- [`pull_request_template.md`](pull_request_template.md) prompts authors to
  document intent, implementation decisions, validation, failure modes, and
  operational safety.
- Pull request review is handled by
  [T4ReviewBot](https://github.com/transport4/t4-gh-auto-reviewer), which adds a
  `review-gate` check to pull requests in the repositories that opt in.
