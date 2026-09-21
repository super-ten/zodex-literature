# zodex literature

A reusable Codex + Zotero literature-research skill for arts, humanities, and social sciences. It covers traceable retrieval, Zotero organization, Zotero-embedded DeepSeek full-text reading, evidence verification, research-gap analysis, and literature-review writing.

Current version: 1.0.0

## Download and install

1. Download the repository ZIP: https://github.com/super-ten/zodex-literature/archive/refs/heads/main.zip
2. Extract the archive and locate the `zodex-literature` folder.
3. Copy that folder to `$CODEX_HOME/skills/` or `~/.codex/skills/`.
4. Restart Codex if the skill is not immediately visible.
5. Invoke it with `$zodex-literature`.

## Structure

```text
zodex-literature/
├── SKILL.md
├── agents/openai.yaml
└── references/
    ├── search.md
    ├── deep-reading.md
    ├── synthesis-writing.md
    └── records.md
```

The skill does not include credentials, API keys, article PDFs, or private Zotero data. Database access and full-text availability still depend on the user's institutional subscriptions and active sessions.
