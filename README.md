# Transport4 GitHub configuration

This repository contains shared GitHub configuration for the Transport4
organization. It provides a consistent pull request format and automated review
policy that can be applied across repositories.

## Contents

- [`pull_request_template.md`](pull_request_template.md) prompts authors to
  document intent, implementation decisions, validation, failure modes, and
  operational safety.
- The organization-owned
  [review policy](https://github.com/transport4/github-workflows/blob/main/.github/workflows/review-policy.yml)
  validates that required pull request sections and author attestations are complete.

The review policy also requires exactly one review classification. Changes that
require independent human review must be approved by a collaborator with write
access, and the approval must apply to the pull request's current commit.
