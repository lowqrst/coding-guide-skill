# Guided Mastery

Guided Mastery is an Agent Skill that helps students complete Tomorrow School assignments independently. It breaks down requirements, identifies knowledge gaps, and guides learners through short lessons, practice tasks, gradual hints, code review, debugging, and defense preparation. It does not provide a complete solution unless explicitly asked.

## Install in Codex

Clone this repository into your personal skills directory as `guided-mastery`:

```sh
git clone https://github.com/lowqrst/coding-guide-skill.git ~/.codex/skills/guided-mastery
```

## Install in Claude Code

Clone it into Claude Code's personal skills directory:

```sh
git clone https://github.com/lowqrst/coding-guide-skill.git ~/.claude/skills/guided-mastery
```

Invoke it with `/guided-mastery`, or let Claude load it when your request matches its description. The `agents/openai.yaml` file contains optional Codex interface metadata; Claude uses `SKILL.md` and the referenced files.

## Install in Claude chat

Package the repository contents inside a top-level folder named `guided-mastery`, then upload that folder as a ZIP through **Customize → Skills → Create skill → Upload a skill**. Enable code execution and file creation if Claude asks for it.

## Use

Share your assignment brief, relevant repository, or current code. The skill maps requirements and checks what you already know. It then works through one small milestone at a time, reviews your attempts, tracks verified progress, and helps you prepare to explain your work.

The `references/symbol-web-example.md` file shows the approach with a Tomorrow School assignment. It is an example, not a fixed curriculum for other projects.
