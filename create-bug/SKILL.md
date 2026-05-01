---
name: create-bug
description: Create a new bug issue in GitHub so that the Ralph loop will pick it up and implement it. Use when the user explicitely wants to report a bug or create a bug ticket.
---

Create a GitHub bug issue based on what the user has described. Follow these rules:

- The issue title must start with `BUG:` so it is easy to find in the issues list
- The body must include an `## Acceptance criteria` section with a checkbox list, otherwise the Ralph script will skip it
- Keep the description concise: what is broken, what the expected behaviour is
- Feel free to ask clarifying questions

Use this body structure:

```
## Description

<what is broken>

## Expected behaviour

<what should happen instead>

## Acceptance criteria

- [ ] <criterion 1>
- [ ] <criterion 2>
```
