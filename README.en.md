# Critical Review

[한국어](README.md)

An agent skill for concise reviews of whether code, plans, designs, and related artifacts fulfill their original purpose, are sufficient, and add unnecessary burden. It uses evidence and counterexamples and challenges the findings themselves. It reports when no material issue is found.

## Use

Provided to Codex and Claude Code through the shared Project Legibility skill snapshot. See [Project Legibility](https://github.com/perhapsspy/project-legibility#readme) for plugin installation. Local development installation checks are separate from publication.

```text
$critical-review Check whether this code and design fulfill the original requirements, what is missing, and what is unnecessary. Do not modify files.
```

Use for review, re-review, challenging your own proposal, and requested final checks. It does not auto-apply to ordinary implementation, summaries, or wording edits. Review-only requests end with diagnosis; already authorized fixes continue through revalidation.

## Source of truth

- Distributed contract: [SKILL.md](skills/critical-review/SKILL.md)
- Korean body: [SKILL.ko.md](skills/critical-review/SKILL.ko.md)
- Plugin composition and distribution: [Project Legibility](https://github.com/perhapsspy/project-legibility)

This repository owns the skill's meaning, selection conditions, and workflow. The plugin owns snapshots generated from this repository's commits.

## License

[MIT](LICENSE)
