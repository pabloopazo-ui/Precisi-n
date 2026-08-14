# CLAUDE.md

This file provides guidance to Claude Code (claude.com/claude-code) and other AI assistants when working with code in this repository.

## Current State

**This repository is currently empty.** As of 2026-08-14, `pabloopazo-ui/Precisi-n` contains no source code, no build configuration, and no prior commits — this CLAUDE.md is the first file added. There is no codebase structure, development workflow, or set of conventions to document yet.

Because of that, this file is a placeholder scaffold. **Whoever adds the first real code to this repository (human or AI) should rewrite this file** to reflect the actual project. Do not treat the empty sections below as established conventions.

## Guidance for AI Assistants (while the repo is empty)

- Do not assume a language, framework, or project type. Nothing has been decided yet; ask the user or infer from their request when starting the project.
- When scaffolding the initial project, also update this CLAUDE.md in the same change so it documents the real setup from day one.
- Keep the repository name in mind: "Precisi-n" (likely "Precisión", Spanish for "precision"). Project-facing text may be intended for a Spanish-speaking audience — confirm with the user.

## Template to fill in once code exists

When the project takes shape, replace everything above and document:

### Project Overview
- What the project does and who it is for.
- Primary language(s), framework(s), and runtime versions.

### Repository Structure
- Top-level directory layout and what lives where.
- Entry points (main modules, app bootstrap files).

### Development Workflow
- How to install dependencies (exact commands).
- How to run the project locally.
- How to run tests (full suite and a single test).
- How to lint, format, and type-check.
- How to build for production, if applicable.

### Conventions
- Code style, naming, and formatting rules (and the tools that enforce them).
- Branching and commit-message conventions.
- Where configuration and secrets handling live (never commit secrets).

### Gotchas
- Anything non-obvious that trips up newcomers or automated agents.
