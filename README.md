# VIRTUBLIC — Content Repository

**Digital Sovereignty as Constitutional Form**

This repository contains the full content of the VIRTUBLIC interactive system, organized as Markdown files with YAML frontmatter. The web interface at [virtublic.html] loads content from this repository via the GitHub Raw API.

## Structure

```

```

## Markdown format

Each file follows this structure:

```markdown
---
id: T1
type: theorem
part: I
title: Surplus Attention
short: "One-line statement"
formula: "Formal notation"
related: [T2, T3, P4]
resolved_by: "P4 + P16"
---

## Content in standard Markdown

Special directives:

::formula
// code block styled as formula box
::

::crisis{Δ1}
Crisis transition text
::

::callout{Label}
Callout text
::
```

## Connecting to the web interface

In the VIRTUBLIC HTML interface, open the **GitHub Content** panel at the bottom of the sidebar and enter:

- **Repository**: `your-username/virtublic-content`
- **Branch**: `main`

The interface will load all content from this repository, with local caching.

---

_VIRTUBLIC — Digital Sovereignty as Constitutional Form_
