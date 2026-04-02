# Contributing to storyseed-template

## Branching and File Location

- Branch naming convention: `chapter-N-username`
- Submission file location: `submissions/chapter-N-username.md`

## Required Frontmatter

Every submission must begin with YAML frontmatter:

```yaml
title: "Chapter Title"
author: "@username"
chapter_number: N
date: YYYY-MM-DD
word_count: 1234
status: pending
```

## Hearing Rules

- PR must remain open for at least 7 days.
- Require 5 approvals to be merge-eligible.
- Zero blocking reviews are allowed.

## Veto Power

- Seed creator (@username) has veto power over any chapter decisions.

## Merge and Canon Process

- After merge, move the chapter file to `canon/chapter-N.md`.
- Update frontmatter with `status: canon`.

## Rejected Submissions

- Rejected PRs stay open for archival and should have `status: rejected` in their frontmatter.
