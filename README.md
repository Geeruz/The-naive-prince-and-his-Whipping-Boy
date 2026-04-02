
## How This Works

This repository is a community-driven collaborative novel seed. Contributors propose chapters under `submissions/` and the community decides which submission becomes canon through a structured hearing process.

### Workflow overview

1. Create a feature branch named `chapter-N-username`.
2. Add a chapter file in `submissions/chapter-N-username.md` with required YAML frontmatter (`title`, `author`, `chapter_number`, `date`, `word_count`, `status`).
3. Open a Pull Request into `main` and apply label `submission`.
4. Keep the PR open for a minimum of 7 days for review and community discussion.
5. Gather at least 5 approvals with zero blocking reviews to be eligible for merge.

### Hearing procedures

- If there are multiple competing chapter submissions for the same chapter number, open a Hearing issue via the `call-hearing` template.
- Hearing issues should include: chapter number, competing PR links, hearing deadline, and voter discussion questions.
- Hearings are open for at least 7 days from issue creation.
- Voters use comments or reactions to express preferences; maintainers track results.
- Seed creator (`@username`) has veto power and final say when consensus cannot be reached.

### Canon mapping

- Once a chapter is approved and merged, move its file from `submissions/chapter-N-username.md` to `canon/chapter-N.md` and update `status: canon` in frontmatter.
- Rejected submissions remain open for archival with `status: rejected` in frontmatter.

### Etiquette

- Be respectful, transparent, and detail continuity checks carefully.
- Use the `lore/` files (`characters.md`, `world.md`, `timeline.md`) to keep worldbuilding consistent.

Please also continue to refer to [CONTRIBUTING.md](CONTRIBUTING.md) for exact branch rules.


Happy Story writting!!!
