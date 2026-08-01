# Nexus Atlas — DataHub Hackathon 2026 Submission Candidate

## Status

This repository is the independent submission candidate for Nexus Atlas.
It is not the long-term development repository and is not frozen yet.

## Origin

- Source repository: https://github.com/cyrilla-mist/nexus-ai
- Source commit: 8f612783cdb4862d3f970448fa326b03b923dfc3
- Candidate created: 2026-08-02
- Default branch: main

## Public Demo

- Landing:
  https://cyrilla-mist.github.io/nexus-atlas-datahub-2026/
- Atlas:
  https://cyrilla-mist.github.io/nexus-atlas-datahub-2026/atlas.html
- Continuity fixture:
  https://cyrilla-mist.github.io/nexus-atlas-datahub-2026/reentry.html?source=fixture&scenario=verity

## Runtime Boundary

The public GitHub Pages demo uses the deterministic Verity fixture.

Live DataHub reads, MCP access, governed ownership proposals,
and confirmed metadata mutation require the documented local runtime.

The public fixture:

- performs no DataHub request
- performs no POST
- performs no add_owners mutation
- cannot change governed external state

## Freeze Policy

This repository may receive final submission documentation,
screenshots, evidence references, and critical fixes before Devpost submission.

At final submission it will receive:

- a final snapshot commit
- a version tag
- a GitHub Release
- a frozen submission notice

After that point, no feature development will occur here.
