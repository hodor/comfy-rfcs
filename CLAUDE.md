# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is the RFC (Request for Comments) repository for ComfyUI. It contains proposals for substantial changes to ComfyUI core, APIs, and standards. RFCs go through stages: Pending → Active → Landed (or Rejected).

This repository is part of the Comfy organization ecosystem. Agents may arrive here from a broader organizational CLAUDE.md.

## Repository Structure

- `rfcs/` - Active and pending RFC proposals (named `0000-feature-name.md`)
- `specifications/` - Current ComfyUI specifications (API definitions, node definitions, manifest files)
- `0000-template.md` - Template for new RFC proposals

## Writing RFCs

New RFCs must follow `0000-template.md` structure with these sections:
- **Summary** - Brief explanation
- **Basic example** - Code examples if applicable
- **Motivation** - Why this change is needed (focus on constraints, not just solutions)
- **Detailed design** - Implementation specifics, corner cases, new terminology
- **Drawbacks** - Implementation cost, breaking changes, teaching impact
- **Alternatives** - Other designs considered
- **Adoption strategy** - Migration path, ecosystem impact
- **Unresolved questions** - Open items for discussion

When creating an RFC:
1. Use filename format `rfcs/0000-my-feature.md` (number assigned on merge)
2. Include convincing motivation and honest assessment of drawbacks
3. Discussion happens in GitHub Discussions, not PR comments

## What Qualifies as an RFC

Substantial changes requiring RFCs include:
- Modifications to ComfyUI core libraries or backend APIs
- Major functionality changes (e.g., execution engine)
- Changes to `workflow.json` schema
- Custom node standards changes
- Frontend widget and API requests
- Core node additions
- Any developer-facing API changes (e.g., `/prompt` API)
