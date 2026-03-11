# VIRTUBLIC — Content Repository

**Digital Sovereignty as Constitutional Form**

This repository contains the full content of the VIRTUBLIC interactive system, organized as Markdown files with YAML frontmatter. The web interface at [virtublic.html] loads content from this repository via the GitHub Raw API.

## Annotation


The [Virtublic ([virtublic.one](https://virtublic.one/)] trilogy is the first complete map of digital power and the only existing blueprint for its institutional alternative. The three volumes form an unbroken chain: each is impossible without the one preceding it, and only together do they produce what has not existed until this moment — a complete theory of the digital republic, from diagnosis to the technical specifications of a cyber-constitution.

Virtublic is not academic critique. It is an operational system: proven, formalized, and ready for implementation. For the first time in the history of political thought, digital exploitation has been translated from the domain of intuition into the domain of measurable structural laws — and for the first time, an answer has been proposed that renders the very possibility of a return to alienation architecturally impossible.

Freedom that depends on another’s will is not freedom. It is a postponement. Power that rests on virtue endures exactly as long as virtue does. Only architecture outlasts the people who built it.

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
