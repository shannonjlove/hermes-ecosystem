Hermes provider setup (HERMES_HOME=/opt/data): active provider is openrouter. Active OR key = GPT-dedicated '[REDACTED_OPENROUTER_KEY]…763c9e', set as OPENROUTER_API_KEY + OPENAI_API_KEY in .env; old key backed up as OPENROUTER_API_KEY_PREVIOUS. Default model openai/gpt-5.6-luna (alias 'luna'); OPENAI_BASE_URL=https://openrouter.ai/api/v1; ~/.codex/config.toml routes Codex to OpenRouter. NVIDIA key separate. claude CLI at ~/.local/bin/claude.
§
Anthropic org (Shannon's Individual Org) id ed20619b-03ff-43aa-b3ea-c0d47fea902b. Workspaces: 'Claude Api Key Workspace 10032026'=wrkspc_01RDVu9WZS5S75cWGtUtXipU, 'Default'=wrkspc_01BShz4RcbThVJ4gcFRoszJw. Org-scoped API keys ([REDACTED_ANTHROPIC_KEY]…) and service keys ([REDACTED_ANTHROPIC_KEY]…) both require the anthropic-workspace-id header on v1/messages. Credit grants LROBNBC2-0003 ($21.78) + LROBNBC2-0001 ($5.44) shown unexpired in console yet billing balance reads $0.00 — API returns 'credit balance too low'.
§
OpenRouter: account shannonjlove@mac.com ~$5.10. Management key 'Hermes' ([REDACTED_OPENROUTER_KEY]…a55) raises limits. Free fallback key OPENROUTER_FALLBACK_API_KEY ('OpenRouter Free API Router 10032026').
§
LoveCloud: 10 repos @ /opt/data/lovecloud-systems/ (all cloned via SSH). 
Tracks: C=session→GitHub (lovecloud_claude_backup_repo), D=BookStack docs (manuals+bookstack-mcp-server), A/B=toolkit (ingest+IDrive), E=Hermes manual.
Infra: SJL-SYSTEM-REGISTRY (authority), Oracle 100.67.229.94 (ARM64, Podman), Mac 100.120.234.104 (deploy).
Governance: v10.3 pipeline, PARA_DATE__DOCID__TITLE__VERSION__SHA8.EXT, DOCID from registry, bookstack tagging.
SSH: ED25519 key on GitHub (shannonjlove), all private repos accessible.
§
Daily memory sync: /opt/data/scripts/hermes_memory_sync.py builds /opt/data/memory/ (sessions, updates, files, backups; redacted) and pushes memory/ to 6 repos via SSH. Cron job 06fc0553f2dc at 03:00 UTC, no_agent.
§
Hermes docs offline copy: skill hermes-docs-reference (/opt/data/skills/hermes-docs-reference) — 239 split pages + lookup script; use it before guessing Hermes config/plugin behaviour.