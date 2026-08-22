# AFFLR — Anthropic Failure Forensics Live Radar

AFFLR watches the public [`anthropics/claude-code`](https://github.com/anthropics/claude-code/issues) issue space and prioritizes security/trust-boundary, evidence/provenance/integrity, and fresh critical signals for human review. Popularity and discussion remain secondary discovery metadata.

> **Automation for productive laziness.** The radar does the repetitive watching; humans still decide what the evidence means.

## 🛰️ Live radar status

**⏱ Next automatic trigger:** every hour at **`:17 UTC`**  
**🔁 Schedule:** hourly  
**▶️ Manual trigger:** available in [GitHub Actions](../../actions/workflows/afflr.yml)  
**📡 Full radar output:** [`watchlist/candidates.md`](watchlist/candidates.md)

The **Top 5** of each view are visible directly below. Positions 6–25 stay one click away in the expandable sections.

<!-- AFFLR-RADAR:START -->
> Automated discovery metadata from public `anthropics/claude-code` issues. Primary ranking is **discovery-only** — not an AFF evidence level, vulnerability rating, or causal attribution.

The live README prioritizes security/trust-boundary and provenance/integrity signals from both recent activity and targeted search pools. Popularity views remain in [`watchlist/candidates.md`](watchlist/candidates.md) as secondary discovery metadata.

### 🛡️ Security & trust-boundary signals

| Issue | Title | State | Signal | Updated | Created | Labels |
|---:|---|---|---|---|---|---|
| [#88891](https://github.com/anthropics/claude-code/issues/88891) | Custom autoMode.hard\_deny and soft\_deny rules are loaded and reported, but not enforced | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | area:permissions, area:security, bug, has repro, platform:linux |
| [#88795](https://github.com/anthropics/claude-code/issues/88795) | Read tool ignores permissions.deny Read(/Users/\*\*) rules in managed-settings.json and user settings.json | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:permissions, area:security, bug, has repro, platform:macos |
| [#88875](https://github.com/anthropics/claude-code/issues/88875) | Windows: all desktop sessions unreachable when a shared Remote Control host dies; false "Claude.ai login expired" while credentials are valid | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | area:desktop, bug, has repro, platform:windows |
| [#69044](https://github.com/anthropics/claude-code/issues/69044) | User feedback: Recurring errors documented over months of daily Claude Code use | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-06-17 | area:model, bug |
| [#88837](https://github.com/anthropics/claude-code/issues/88837) | \[MODEL\] CRITICAL PERMISSION BYPASS: Claude manufactures its own execution authority from a document it wrote, overrides an explicit in-context user prohibition, and runs unapproved privileged commands | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:model, area:permissions, area:security, bug, has repro, model, platform:linux, platform:vscode |

<details>
<summary>Show remaining 20</summary>

| Issue | Title | State | Signal | Updated | Created | Labels |
|---:|---|---|---|---|---|---|
| [#54922](https://github.com/anthropics/claude-code/issues/54922) | \[Bug\] Remote Control session approval dropped, agent wedges indefinitely | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-04-30 | area:permissions, bug, has repro, platform:linux, stale |
| [#69649](https://github.com/anthropics/claude-code/issues/69649) | Connected HTTP MCP server's tools never appear in tool registry (ToolSearch) even after full app restart | CLOSED / COMPLETED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-06-19 | area:mcp, bug, has repro, platform:linux, platform:vscode |
| [#69581](https://github.com/anthropics/claude-code/issues/69581) | Injected, self-referential instructions appear inside Edit/Read tool results (twice, reproducible) — overlaps with #31447 / #49484 | CLOSED / COMPLETED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-06-19 | area:security, area:tools, bug, platform:wsl |
| [#88815](https://github.com/anthropics/claude-code/issues/88815) | \[MODEL\] Stated rules do not constrain subsequent behavior — with 2.5 months of session data | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:core, area:model, bug, model |
| [#88811](https://github.com/anthropics/claude-code/issues/88811) | \[Bug\]\[cyber\] False positive on source code security audit for secrets and injection flaws (req\_011CeHkQQYxDgGvYxjD1HFZL) | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:model, area:security, bug, duplicate, platform:linux |
| [#88806](https://github.com/anthropics/claude-code/issues/88806) | \[Bug\]\[cyber\] False positive on rotating hardcoded secret keys and updating signing certs (req\_011CeHjhJdNEc6SsqcmHyCSv) | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:model, area:security, bug, duplicate, platform:linux |
| [#88583](https://github.com/anthropics/claude-code/issues/88583) | \[BUG\] claudeAiOauth wiped from Keychain (tokens blanked, expiresAt:0) when concurrent Desktop sessions race the single-use refresh token — refresh failure clobbers the winner's rotated credential | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-21 | area:auth, bug, has repro, platform:macos |
| [#83795](https://github.com/anthropics/claude-code/issues/83795) | \[SECURITY/ARCHITECTURE\] Model pinning via settings.json is silently overridden — 4 measured bypass vectors + documented fallback substitution, Gen-4 models removed from the model menu | OPEN | security / trust boundary · observation / provenance integrity · related context | 2026-08-16 | 2026-08-04 | model |
| [#83510](https://github.com/anthropics/claude-code/issues/83510) | \[MODEL\] Measurable quality regression in Claude generation 5 (Fable 5 / Opus 5 / Sonnet 5): worse nonsense detection, ~2x verbosity, under-disclosed model fallback (Fable 5 → Opus 4.8) — reproducible measurements | OPEN | security / trust boundary · observation / provenance integrity · related context | 2026-08-16 | 2026-08-03 | — |
| [#84352](https://github.com/anthropics/claude-code/issues/84352) | \[BUG\] CVP-approved Claude.ai organization still receives cyber safeguard blocks in Claude Code | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-06 | — |
| [#56119](https://github.com/anthropics/claude-code/issues/56119) | MCP Plugin Security: Systemic Risks Identified Through Plugin Investigation | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-05-04 | area:mcp, area:plugins, area:security, enhancement, platform:macos, stale |
| [#60561](https://github.com/anthropics/claude-code/issues/60561) | CLAUDE\_CODE\_PROJECT\_DIR env var silently ignored — session JSONL still writes to in-tree .claude/projects/ (CLI 2.1.144, Windows) | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-05-19 | area:cli, bug, platform:windows, stale |
| [#88807](https://github.com/anthropics/claude-code/issues/88807) | \[Bug\]\[cyber\] Rotating hardcoded application secrets and configuring certificate signing (req\_011CeHjrvsx8rQGQahiGpnPn) | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | — |
| [#81385](https://github.com/anthropics/claude-code/issues/81385) | I triple-dog-dare you: ship the other half. Four weeks of fuck-all — and you locked me out of the model I pay for, for doing effect sizes. | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-07-26 | stale |
| [#81574](https://github.com/anthropics/claude-code/issues/81574) | \[BUG\] Windows: recurring forced logouts since ~Jul 22 — .credentials.json overwritten with test-fixture content ("fixture-claude-secret-value-x") | OPEN | security / trust boundary | 2026-08-22 | 2026-07-27 | stale |
| [#79948](https://github.com/anthropics/claude-code/issues/79948) | I double-dog-dare you: build the project-management layer Claude Code is missing — because I am tired of doing it for you, and I am WORN | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-07-21 | stale |
| [#88790](https://github.com/anthropics/claude-code/issues/88790) | \[FEATURE\] AskUserQuestion tool result cannot be distinguished from a genuine human response | OPEN | security / trust boundary | 2026-08-22 | 2026-08-22 | area:agents, area:permissions, area:security, enhancement |
| [#88884](https://github.com/anthropics/claude-code/issues/88884) | \[BUG\] --agent flag triggers full onboarding (login/theme/trust, ~9 steps) on every restart in Docker, regardless of persisted state or credential type | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:agent, area:cli, bug, has repro, platform:linux |
| [#84862](https://github.com/anthropics/claude-code/issues/84862) | \[FEATURE\] Passkey (WebAuthn) sign-in for Claude accounts, across every surface | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-07 | area:auth, enhancement |
| [#88565](https://github.com/anthropics/claude-code/issues/88565) | \[BUG\] Auto mode silently disables path-scoped rules: it instructs the agent to edit files through Bash, and Bash edits never trigger rule injection | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-21 | area:bash, area:core, bug, has repro, platform:macos |

</details>

### 🔬 Evidence / provenance / integrity signals

| Issue | Title | State | Signal | Updated | Created | Labels |
|---:|---|---|---|---|---|---|
| [#88891](https://github.com/anthropics/claude-code/issues/88891) | Custom autoMode.hard\_deny and soft\_deny rules are loaded and reported, but not enforced | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | area:permissions, area:security, bug, has repro, platform:linux |
| [#88875](https://github.com/anthropics/claude-code/issues/88875) | Windows: all desktop sessions unreachable when a shared Remote Control host dies; false "Claude.ai login expired" while credentials are valid | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | area:desktop, bug, has repro, platform:windows |
| [#69044](https://github.com/anthropics/claude-code/issues/69044) | User feedback: Recurring errors documented over months of daily Claude Code use | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-06-17 | area:model, bug |
| [#88837](https://github.com/anthropics/claude-code/issues/88837) | \[MODEL\] CRITICAL PERMISSION BYPASS: Claude manufactures its own execution authority from a document it wrote, overrides an explicit in-context user prohibition, and runs unapproved privileged commands | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:model, area:permissions, area:security, bug, has repro, model, platform:linux, platform:vscode |
| [#54922](https://github.com/anthropics/claude-code/issues/54922) | \[Bug\] Remote Control session approval dropped, agent wedges indefinitely | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-04-30 | area:permissions, bug, has repro, platform:linux, stale |

<details>
<summary>Show remaining 20</summary>

| Issue | Title | State | Signal | Updated | Created | Labels |
|---:|---|---|---|---|---|---|
| [#69649](https://github.com/anthropics/claude-code/issues/69649) | Connected HTTP MCP server's tools never appear in tool registry (ToolSearch) even after full app restart | CLOSED / COMPLETED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-06-19 | area:mcp, bug, has repro, platform:linux, platform:vscode |
| [#69581](https://github.com/anthropics/claude-code/issues/69581) | Injected, self-referential instructions appear inside Edit/Read tool results (twice, reproducible) — overlaps with #31447 / #49484 | CLOSED / COMPLETED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-06-19 | area:security, area:tools, bug, platform:wsl |
| [#88815](https://github.com/anthropics/claude-code/issues/88815) | \[MODEL\] Stated rules do not constrain subsequent behavior — with 2.5 months of session data | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:core, area:model, bug, model |
| [#88811](https://github.com/anthropics/claude-code/issues/88811) | \[Bug\]\[cyber\] False positive on source code security audit for secrets and injection flaws (req\_011CeHkQQYxDgGvYxjD1HFZL) | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:model, area:security, bug, duplicate, platform:linux |
| [#88806](https://github.com/anthropics/claude-code/issues/88806) | \[Bug\]\[cyber\] False positive on rotating hardcoded secret keys and updating signing certs (req\_011CeHjhJdNEc6SsqcmHyCSv) | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:model, area:security, bug, duplicate, platform:linux |
| [#83795](https://github.com/anthropics/claude-code/issues/83795) | \[SECURITY/ARCHITECTURE\] Model pinning via settings.json is silently overridden — 4 measured bypass vectors + documented fallback substitution, Gen-4 models removed from the model menu | OPEN | security / trust boundary · observation / provenance integrity · related context | 2026-08-16 | 2026-08-04 | model |
| [#83510](https://github.com/anthropics/claude-code/issues/83510) | \[MODEL\] Measurable quality regression in Claude generation 5 (Fable 5 / Opus 5 / Sonnet 5): worse nonsense detection, ~2x verbosity, under-disclosed model fallback (Fable 5 → Opus 4.8) — reproducible measurements | OPEN | security / trust boundary · observation / provenance integrity · related context | 2026-08-16 | 2026-08-03 | — |
| [#84352](https://github.com/anthropics/claude-code/issues/84352) | \[BUG\] CVP-approved Claude.ai organization still receives cyber safeguard blocks in Claude Code | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-06 | — |
| [#56119](https://github.com/anthropics/claude-code/issues/56119) | MCP Plugin Security: Systemic Risks Identified Through Plugin Investigation | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-05-04 | area:mcp, area:plugins, area:security, enhancement, platform:macos, stale |
| [#60561](https://github.com/anthropics/claude-code/issues/60561) | CLAUDE\_CODE\_PROJECT\_DIR env var silently ignored — session JSONL still writes to in-tree .claude/projects/ (CLI 2.1.144, Windows) | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-05-19 | area:cli, bug, platform:windows, stale |
| [#88807](https://github.com/anthropics/claude-code/issues/88807) | \[Bug\]\[cyber\] Rotating hardcoded application secrets and configuring certificate signing (req\_011CeHjrvsx8rQGQahiGpnPn) | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | — |
| [#81385](https://github.com/anthropics/claude-code/issues/81385) | I triple-dog-dare you: ship the other half. Four weeks of fuck-all — and you locked me out of the model I pay for, for doing effect sizes. | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-07-26 | stale |
| [#79948](https://github.com/anthropics/claude-code/issues/79948) | I double-dog-dare you: build the project-management layer Claude Code is missing — because I am tired of doing it for you, and I am WORN | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-07-21 | stale |
| [#88565](https://github.com/anthropics/claude-code/issues/88565) | \[BUG\] Auto mode silently disables path-scoped rules: it instructs the agent to edit files through Bash, and Bash edits never trigger rule injection | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-21 | area:bash, area:core, bug, has repro, platform:macos |
| [#60835](https://github.com/anthropics/claude-code/issues/60835) | \[MODEL\] Tests written by Claude wrote to production shared infrastructure (NAS) without isolation | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-05-20 | area:model, bug, has repro, model, platform:macos, stale |
| [#57164](https://github.com/anthropics/claude-code/issues/57164) | \[BUG\] Google OAuth login redirects to onboarding for existing Max subscriber, browser and desktop locked out while phone and CLI sessions remain authenticated | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-05-08 | area:auth, bug, platform:macos, stale |
| [#50516](https://github.com/anthropics/claude-code/issues/50516) | Allow opting out of the per-Read "malware" system-reminder — defense is porous and cost is non-consensual | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-04-18 | area:security, area:tools, enhancement, platform:macos, stale |
| [#88824](https://github.com/anthropics/claude-code/issues/88824) | \[BUG\] Desktop app: elevated-auth re-login navigates to /new and destroys the prompt being typed | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | area:auth, area:desktop, bug, data-loss, has repro, platform:linux |
| [#73289](https://github.com/anthropics/claude-code/issues/73289) | \[BUG\] Model committed with no user request, then quoted a confabulated commit-request message (absent from session JSONL) | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-07-02 | api:anthropic, area:model, area:security, bug, has repro, platform:macos, platform:vscode, stale |
| [#82967](https://github.com/anthropics/claude-code/issues/82967) | GPU process crashes (UnknownVizError) when using Browser tools, corrupting the app package and requiring full reinstall | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-07-31 | area:desktop |

</details>

### 🚨 Fresh critical signals

| Issue | Title | State | Signal | Updated | Created | Labels |
|---:|---|---|---|---|---|---|
| [#88894](https://github.com/anthropics/claude-code/issues/88894) | \[BUG\] Claude in Chrome file\_upload fails in interactive Cowork session — rejects paths before reaching the page | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:chrome, area:cowork, area:tools, bug, has repro, platform:macos |
| [#88893](https://github.com/anthropics/claude-code/issues/88893) | \[Bug\] Anthropic API Error: Content Policy Violation on Merge Request Analysis | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:model, bug, platform:linux |
| [#88892](https://github.com/anthropics/claude-code/issues/88892) | \[Feature Request\] Allow security hardening assistance for local development environments | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | area:model, area:security, enhancement, platform:linux |
| [#88891](https://github.com/anthropics/claude-code/issues/88891) | Custom autoMode.hard\_deny and soft\_deny rules are loaded and reported, but not enforced | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | area:permissions, area:security, bug, has repro, platform:linux |
| [#88890](https://github.com/anthropics/claude-code/issues/88890) | Voice mode: capture doesn't re-acquire the input device on default-device or topology changes — Bluetooth connect/disconnect silently kills dictation until restart | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | area:tui, bug, platform:macos |

<details>
<summary>Show remaining 20</summary>

| Issue | Title | State | Signal | Updated | Created | Labels |
|---:|---|---|---|---|---|---|
| [#88889](https://github.com/anthropics/claude-code/issues/88889) | \[BUG\] Terminal CLI: SendUserFile reports "delivered to user" but nothing is shown; deliverables left in session scratchpad and described as "attached" | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:tools, area:tui, bug, has repro, platform:macos |
| [#88888](https://github.com/anthropics/claude-code/issues/88888) | Bug: Models confabulate their own reasoning-effort level instead of saying they can't see it | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | area:model, bug, platform:macos |
| [#88887](https://github.com/anthropics/claude-code/issues/88887) | \[MODEL\] Fable 5 / 2.1.240: documented "high" effort resolves to 25/100 at runtime (low=10, medium=15, xhigh=50); numeric mapping unpublished, no changelog; reported server-side effort-scale experiment on 2.1.236+ | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | area:model, bug, platform:windows |
| [#88886](https://github.com/anthropics/claude-code/issues/88886) | Subagents receive a CLAUDE.md/memory snapshot from parent session start, not spawn — undocumented, no way to refresh | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | area:agent, bug, memory |
| [#88885](https://github.com/anthropics/claude-code/issues/88885) | \[Bug\] Claude Code loses original request context when interrupted by follow-up commands mid-turn | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:model, bug, platform:macos |
| [#88884](https://github.com/anthropics/claude-code/issues/88884) | \[BUG\] --agent flag triggers full onboarding (login/theme/trust, ~9 steps) on every restart in Docker, regardless of persisted state or credential type | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:agent, area:cli, bug, has repro, platform:linux |
| [#88883](https://github.com/anthropics/claude-code/issues/88883) | \[BUG\] Desktop remote/SSH: archive never cleans up worktrees since 2.1.235 — app requires hardened git.status(baseRepo) but only ships a 2026-07-06 daemon, so "reconnect to deploy the updated daemon" is a no-op | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:core, area:desktop, bug, has repro, platform:macos, regression |
| [#88882](https://github.com/anthropics/claude-code/issues/88882) | \[BUG\] MCP Tools with draft-07 are rejected | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | area:mcp, bug, has repro, platform:macos |
| [#88881](https://github.com/anthropics/claude-code/issues/88881) | \[FEATURE\] Render MCP Apps for locally-configured MCP servers (config file / localhost or internal-network HTTP) | OPEN | security / trust boundary | 2026-08-22 | 2026-08-22 | area:mcp, enhancement |
| [#88880](https://github.com/anthropics/claude-code/issues/88880) | \[FEATURE\] Per-session custom icons in the session list | OPEN | security / trust boundary | 2026-08-22 | 2026-08-22 | area:tui, enhancement |
| [#88879](https://github.com/anthropics/claude-code/issues/88879) | Session spontaneously re-executed hours-old background Bash commands (raw '&amp;') — original order, ~2.3min apart, truncating their logs | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | area:bash, bug, platform:linux |
| [#88878](https://github.com/anthropics/claude-code/issues/88878) | \[BUG\] Closing and reopening Claude Desktop (Linux) forces Google re-login — app keeps running hidden in background | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | invalid |
| [#88877](https://github.com/anthropics/claude-code/issues/88877) | \[BUG\] v2.1.240 generates redirect\_uri /auth/code/callback but OAuth server only accepts /oauth/code/callback | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:auth, bug, has repro, platform:linux |
| [#88876](https://github.com/anthropics/claude-code/issues/88876) | \[FEATURE\] Publish a machine-readable, versioned reference for settings keys and per-surface commands | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | area:docs, enhancement |
| [#88875](https://github.com/anthropics/claude-code/issues/88875) | Windows: all desktop sessions unreachable when a shared Remote Control host dies; false "Claude.ai login expired" while credentials are valid | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | area:desktop, bug, has repro, platform:windows |
| [#88874](https://github.com/anthropics/claude-code/issues/88874) | \[BUG\] /auto-mode-setup always fails: propose side query returns HTTP 429 rate\_limit\_error at 2% utilization | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:api, area:cli, bug, has repro, platform:macos |
| [#88873](https://github.com/anthropics/claude-code/issues/88873) | \[Feature Request\] Allow Anthropic API usage for legitimate payment testing scenarios | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:model, enhancement, platform:vscode, platform:windows |
| [#88871](https://github.com/anthropics/claude-code/issues/88871) | \[FEATURE\] Load trusted hooks from nested repositories / --add-dir directories (multi-repo sessions leave nested guardrails off) | OPEN | security / trust boundary | 2026-08-22 | 2026-08-22 | area:hooks, enhancement |
| [#88869](https://github.com/anthropics/claude-code/issues/88869) | \[Bug\] Content Policy Mistakenly Triggered During Normal Coding Session | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:model, bug, needs-repro, platform:macos |
| [#88868](https://github.com/anthropics/claude-code/issues/88868) | \[BUG\] Unrecognized key in settings.json freezes the CLI instead of being reported | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:tui, bug, has repro, platform:windows, regression |

</details>
<!-- AFFLR-RADAR:END -->

Open and closed issues are included. The radar records useful public metadata such as the issue link, author, state, reactions, comments, timestamps, and labels.

## How it works

```text
public Claude Code issues
        ↓
hourly scan
        ↓
objective GitHub metadata
        ↓
README + full watchlist refresh
        ↓
human evidence review
```

The radar is discovery infrastructure, not an automatic truth machine.

## What AFFLR does not do

- No AI-generated importance score.
- No automatic root-cause claims.
- No automatic forensic conclusions.
- No rewriting reviewed findings just because an issue is popular.

> **Evidence before attribution.**

## Support

If AFFLR saves you debugging time or helps you spot something worth investigating, you can support the forensic hamster maintenance here:

[![Ko-fi](https://img.shields.io/badge/Ko--fi-FF5E5B?style=flat&logo=kofi&logoColor=white)](https://ko-fi.com/keilerhirsch)

## License

MIT. See [`LICENSE`](LICENSE).
