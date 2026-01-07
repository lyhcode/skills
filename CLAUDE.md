# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a Claude Code skills repository. Skills are custom commands that extend Claude Code's capabilities.

## Structure

Each skill lives in its own directory with a `SKILL.md` file that defines:
- **Frontmatter**: `name` and `description` fields (YAML format)
- **Body**: Detailed instructions for how Claude should behave when the skill is invoked

## Creating a New Skill

1. Create a directory with the skill name
2. Add a `SKILL.md` file with:
   - YAML frontmatter containing `name` and `description`
   - Markdown body with behavior instructions and examples

Example structure:
```
skill-name/
  SKILL.md
```
