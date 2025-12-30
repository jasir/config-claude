# ENT Skills Plugin

Personal Claude Code plugin containing ENT Framework programming skills.

## Skills Included

### ent-framework-programmer

Comprehensive skill for working with ENT Framework - a markdown-based development framework for Vue 2 + Quasar applications.

**Covers:**
- Vue 2 Options API patterns (NOT Vue 3)
- Quasar-only styling (NO custom CSS)
- ENT-specific patterns (callRestApi, BaseStore)
- Bootstrap namespace
- Creating components, pages, stores
- Correct persistentData format

**When to use:** When user requests ENT framework work (creating components, pages, stores, namespaces)

## Installation

This is a local plugin installed from: `~/projects/claude-plugins/ent-skills`

## Structure

```
ent-skills/
  skills/
    ent-framework-programmer/
      SKILL.md           # Main skill reference
      docs/              # Symlinks to ENT documentation
```

## Version

- **1.0.0** - Initial release with ent-framework-programmer skill

## Author

Created through TDD process (RED-GREEN-REFACTOR) with baseline testing and 100% compliance verification.
