# Guided Mastery

Guided Mastery is an Agent Skill that helps students complete Tomorrow School assignments independently. It breaks down requirements, identifies knowledge gaps, and guides learners through short lessons, practice tasks, gradual hints, code review, debugging, and defense preparation. It does not provide a complete solution unless explicitly asked.

## Install

Clone this repository into your Codex skills directory as `guided-mastery`:

```sh
git clone https://github.com/lowqrst/coding-guide-skill.git ~/.codex/skills/guided-mastery
```

On Windows, use `%USERPROFILE%\.codex\skills\guided-mastery` as the destination. The folder must contain `SKILL.md` at its root.

## Use

Invoke `$guided-mastery` and share your assignment brief, relevant repository, or current code. The skill starts by mapping requirements and checking what you already know. It then works through one small milestone at a time, reviews your attempts, tracks verified progress, and helps you prepare to explain your work.

The `references/symbol-web-example.md` file shows the approach with a Tomorrow School assignment. It is an example, not a fixed curriculum for other projects.
