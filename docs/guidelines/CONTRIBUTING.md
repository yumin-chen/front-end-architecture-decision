# Contribution Guidelines

Contributions are welcome to this repository! Please follow these guidelines to ensure that your contribution is accepted and integrated smoothly.

1. Create a new file in the appropriate category directory under `/docs`.
2. Use the following template to document your decision, with the appropriate metadata as YAML Frontmatter in Markdown:

```yaml
---
Title: "{Topic}: {Decision}"
Date: {today}
Topic: {One Domain Only}
Author: {Your Name}
Tags: [{parallel domains}, {meta-domains}, {meta-topics}, ...]
Alternative Considered:
 - list of alternatives within the same topic
Consequences:
 - list of enforciable and actionable rules

---
```

```markdown

# Architecture Decision Record

## Decision

[Why did you make this decision?]

## Context

[What was the problem you were trying to solve?]

## Alternative Considered

[What alternatives did you consider? Tabulate the pros and cons of each alternative, and explain why you chose the one you did.]

## Consequences

[What are the enforciable and actionable rules as a result from this decision?]

```

3. Submit a patch with your changes.
4. One commit, one ADR only.

The registry or index `README.md` within the category directory is automatically updated once you submit your patch with the ADR in it.

Thank you for contributing to this repository!
