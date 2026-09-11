# Type 2 Agent Demo — published site

This repository exists only to serve the demo over GitHub Pages. It contains a
single self-contained `index.html` and nothing else.

**→ https://glenn-goh.github.io/type-2-agent-demo-site/**

The source, the design and implementation documents, and the HTX materials live
in a separate **private** repository. Nothing here is generated from, or exposes,
those materials.

## What this is

A presenter-driven prototype demonstrating a "Type 2" agent — one delegated an
outcome rather than a prompt — running a project-management workflow across
recreations of Microsoft Teams and Outlook. Every person, message, email and
document in it is fictional and created for the demonstration.

## Updating it

From the private repository:

```bash
npm run publish:site
```

That rebuilds and pushes the new `index.html` here.
