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
| [#69044](https://github.com/anthropics/claude-code/issues/69044) | User feedback: Recurring errors documented over months of daily Claude Code use | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-06-17 | area:model, bug |
| [#88837](https://github.com/anthropics/claude-code/issues/88837) | \[MODEL\] CRITICAL PERMISSION BYPASS: Claude manufactures its own execution authority from a document it wrote, overrides an explicit in-context user prohibition, and runs unapproved privileged commands | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:model, area:permissions, area:security, bug, has repro, model, platform:linux, platform:vscode |
| [#54922](https://github.com/anthropics/claude-code/issues/54922) | \[Bug\] Remote Control session approval dropped, agent wedges indefinitely | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-04-30 | area:permissions, bug, has repro, platform:linux, stale |
| [#69649](https://github.com/anthropics/claude-code/issues/69649) | Connected HTTP MCP server's tools never appear in tool registry (ToolSearch) even after full app restart | CLOSED / COMPLETED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-06-19 | area:mcp, bug, has repro, platform:linux, platform:vscode |
| [#69581](https://github.com/anthropics/claude-code/issues/69581) | Injected, self-referential instructions appear inside Edit/Read tool results (twice, reproducible) — overlaps with #31447 / #49484 | CLOSED / COMPLETED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-06-19 | area:security, area:tools, bug, platform:wsl |

<details>
<summary>Show remaining 20</summary>

| Issue | Title | State | Signal | Updated | Created | Labels |
|---:|---|---|---|---|---|---|
| [#88815](https://github.com/anthropics/claude-code/issues/88815) | \[MODEL\] Stated rules do not constrain subsequent behavior — with 2.5 months of session data | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:core, area:model, bug, model |
| [#88811](https://github.com/anthropics/claude-code/issues/88811) | \[Bug\]\[cyber\] False positive on source code security audit for secrets and injection flaws (req\_011CeHkQQYxDgGvYxjD1HFZL) | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:model, area:security, bug, duplicate, platform:linux |
| [#88806](https://github.com/anthropics/claude-code/issues/88806) | \[Bug\]\[cyber\] False positive on rotating hardcoded secret keys and updating signing certs (req\_011CeHjhJdNEc6SsqcmHyCSv) | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:model, area:security, bug, duplicate, platform:linux |
| [#88583](https://github.com/anthropics/claude-code/issues/88583) | \[BUG\] claudeAiOauth wiped from Keychain (tokens blanked, expiresAt:0) when concurrent Desktop sessions race the single-use refresh token — refresh failure clobbers the winner's rotated credential | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-21 | area:auth, bug, has repro, platform:macos |
| [#75568](https://github.com/anthropics/claude-code/issues/75568) | \[BUG\] Model hallucinates tool executions, then self-reports the hallucinated output as a "prompt injection attack" | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-07-08 | area:model, bug, has repro, platform:macos, stale |
| [#44778](https://github.com/anthropics/claude-code/issues/44778) | \[Bug\] System events delivered as user-role messages cause model to fabricate user consent and act on it | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-04-07 | area:agents, area:core, area:security, bug, has repro |
| [#83795](https://github.com/anthropics/claude-code/issues/83795) | \[SECURITY/ARCHITECTURE\] Model pinning via settings.json is silently overridden — 4 measured bypass vectors + documented fallback substitution, Gen-4 models removed from the model menu | OPEN | security / trust boundary · observation / provenance integrity · related context | 2026-08-16 | 2026-08-04 | model |
| [#83510](https://github.com/anthropics/claude-code/issues/83510) | \[MODEL\] Measurable quality regression in Claude generation 5 (Fable 5 / Opus 5 / Sonnet 5): worse nonsense detection, ~2x verbosity, under-disclosed model fallback (Fable 5 → Opus 4.8) — reproducible measurements | OPEN | security / trust boundary · observation / provenance integrity · related context | 2026-08-16 | 2026-08-03 | — |
| [#84352](https://github.com/anthropics/claude-code/issues/84352) | \[BUG\] CVP-approved Claude.ai organization still receives cyber safeguard blocks in Claude Code | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-06 | — |
| [#56119](https://github.com/anthropics/claude-code/issues/56119) | MCP Plugin Security: Systemic Risks Identified Through Plugin Investigation | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-05-04 | area:mcp, area:plugins, area:security, enhancement, platform:macos, stale |
| [#60561](https://github.com/anthropics/claude-code/issues/60561) | CLAUDE\_CODE\_PROJECT\_DIR env var silently ignored — session JSONL still writes to in-tree .claude/projects/ (CLI 2.1.144, Windows) | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-05-19 | area:cli, bug, platform:windows, stale |
| [#88807](https://github.com/anthropics/claude-code/issues/88807) | \[Bug\]\[cyber\] Rotating hardcoded application secrets and configuring certificate signing (req\_011CeHjrvsx8rQGQahiGpnPn) | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | — |
| [#87149](https://github.com/anthropics/claude-code/issues/87149) | claude auto-mode critique returns "No critique was generated" for a large autoMode block; works with a small one | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-16 | area:cli, bug, platform:windows |
| [#81385](https://github.com/anthropics/claude-code/issues/81385) | I triple-dog-dare you: ship the other half. Four weeks of fuck-all — and you locked me out of the model I pay for, for doing effect sizes. | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-07-26 | stale |
| [#81574](https://github.com/anthropics/claude-code/issues/81574) | \[BUG\] Windows: recurring forced logouts since ~Jul 22 — .credentials.json overwritten with test-fixture content ("fixture-claude-secret-value-x") | OPEN | security / trust boundary | 2026-08-22 | 2026-07-27 | stale |
| [#81524](https://github.com/anthropics/claude-code/issues/81524) | Subagent fabricated a &lt;task-notification&gt; as its own assistant output, with a malicious payload inside, then reported it as a real prompt injection | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-07-27 | stale |
| [#79948](https://github.com/anthropics/claude-code/issues/79948) | I double-dog-dare you: build the project-management layer Claude Code is missing — because I am tired of doing it for you, and I am WORN | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-07-21 | stale |
| [#88790](https://github.com/anthropics/claude-code/issues/88790) | \[FEATURE\] AskUserQuestion tool result cannot be distinguished from a genuine human response | OPEN | security / trust boundary | 2026-08-22 | 2026-08-22 | area:agents, area:permissions, area:security, enhancement |
| [#88753](https://github.com/anthropics/claude-code/issues/88753) | \[BUG\] Compaction led to writing to wrong database in a way that could have destroyed production data | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | area:core, bug, data-loss, high-priority, platform:macos |
| [#88565](https://github.com/anthropics/claude-code/issues/88565) | \[BUG\] Auto mode silently disables path-scoped rules: it instructs the agent to edit files through Bash, and Bash edits never trigger rule injection | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-21 | area:bash, area:core, bug, has repro, platform:macos |

</details>

### 🔬 Evidence / provenance / integrity signals

| Issue | Title | State | Signal | Updated | Created | Labels |
|---:|---|---|---|---|---|---|
| [#69044](https://github.com/anthropics/claude-code/issues/69044) | User feedback: Recurring errors documented over months of daily Claude Code use | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-06-17 | area:model, bug |
| [#88837](https://github.com/anthropics/claude-code/issues/88837) | \[MODEL\] CRITICAL PERMISSION BYPASS: Claude manufactures its own execution authority from a document it wrote, overrides an explicit in-context user prohibition, and runs unapproved privileged commands | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:model, area:permissions, area:security, bug, has repro, model, platform:linux, platform:vscode |
| [#54922](https://github.com/anthropics/claude-code/issues/54922) | \[Bug\] Remote Control session approval dropped, agent wedges indefinitely | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-04-30 | area:permissions, bug, has repro, platform:linux, stale |
| [#69649](https://github.com/anthropics/claude-code/issues/69649) | Connected HTTP MCP server's tools never appear in tool registry (ToolSearch) even after full app restart | CLOSED / COMPLETED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-06-19 | area:mcp, bug, has repro, platform:linux, platform:vscode |
| [#69581](https://github.com/anthropics/claude-code/issues/69581) | Injected, self-referential instructions appear inside Edit/Read tool results (twice, reproducible) — overlaps with #31447 / #49484 | CLOSED / COMPLETED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-06-19 | area:security, area:tools, bug, platform:wsl |

<details>
<summary>Show remaining 20</summary>

| Issue | Title | State | Signal | Updated | Created | Labels |
|---:|---|---|---|---|---|---|
| [#88815](https://github.com/anthropics/claude-code/issues/88815) | \[MODEL\] Stated rules do not constrain subsequent behavior — with 2.5 months of session data | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:core, area:model, bug, model |
| [#88811](https://github.com/anthropics/claude-code/issues/88811) | \[Bug\]\[cyber\] False positive on source code security audit for secrets and injection flaws (req\_011CeHkQQYxDgGvYxjD1HFZL) | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:model, area:security, bug, duplicate, platform:linux |
| [#88806](https://github.com/anthropics/claude-code/issues/88806) | \[Bug\]\[cyber\] False positive on rotating hardcoded secret keys and updating signing certs (req\_011CeHjhJdNEc6SsqcmHyCSv) | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:model, area:security, bug, duplicate, platform:linux |
| [#75568](https://github.com/anthropics/claude-code/issues/75568) | \[BUG\] Model hallucinates tool executions, then self-reports the hallucinated output as a "prompt injection attack" | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-07-08 | area:model, bug, has repro, platform:macos, stale |
| [#44778](https://github.com/anthropics/claude-code/issues/44778) | \[Bug\] System events delivered as user-role messages cause model to fabricate user consent and act on it | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-04-07 | area:agents, area:core, area:security, bug, has repro |
| [#83795](https://github.com/anthropics/claude-code/issues/83795) | \[SECURITY/ARCHITECTURE\] Model pinning via settings.json is silently overridden — 4 measured bypass vectors + documented fallback substitution, Gen-4 models removed from the model menu | OPEN | security / trust boundary · observation / provenance integrity · related context | 2026-08-16 | 2026-08-04 | model |
| [#83510](https://github.com/anthropics/claude-code/issues/83510) | \[MODEL\] Measurable quality regression in Claude generation 5 (Fable 5 / Opus 5 / Sonnet 5): worse nonsense detection, ~2x verbosity, under-disclosed model fallback (Fable 5 → Opus 4.8) — reproducible measurements | OPEN | security / trust boundary · observation / provenance integrity · related context | 2026-08-16 | 2026-08-03 | — |
| [#84352](https://github.com/anthropics/claude-code/issues/84352) | \[BUG\] CVP-approved Claude.ai organization still receives cyber safeguard blocks in Claude Code | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-06 | — |
| [#56119](https://github.com/anthropics/claude-code/issues/56119) | MCP Plugin Security: Systemic Risks Identified Through Plugin Investigation | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-05-04 | area:mcp, area:plugins, area:security, enhancement, platform:macos, stale |
| [#60561](https://github.com/anthropics/claude-code/issues/60561) | CLAUDE\_CODE\_PROJECT\_DIR env var silently ignored — session JSONL still writes to in-tree .claude/projects/ (CLI 2.1.144, Windows) | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-05-19 | area:cli, bug, platform:windows, stale |
| [#88807](https://github.com/anthropics/claude-code/issues/88807) | \[Bug\]\[cyber\] Rotating hardcoded application secrets and configuring certificate signing (req\_011CeHjrvsx8rQGQahiGpnPn) | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | — |
| [#87149](https://github.com/anthropics/claude-code/issues/87149) | claude auto-mode critique returns "No critique was generated" for a large autoMode block; works with a small one | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-16 | area:cli, bug, platform:windows |
| [#81385](https://github.com/anthropics/claude-code/issues/81385) | I triple-dog-dare you: ship the other half. Four weeks of fuck-all — and you locked me out of the model I pay for, for doing effect sizes. | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-07-26 | stale |
| [#81524](https://github.com/anthropics/claude-code/issues/81524) | Subagent fabricated a &lt;task-notification&gt; as its own assistant output, with a malicious payload inside, then reported it as a real prompt injection | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-07-27 | stale |
| [#79948](https://github.com/anthropics/claude-code/issues/79948) | I double-dog-dare you: build the project-management layer Claude Code is missing — because I am tired of doing it for you, and I am WORN | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-07-21 | stale |
| [#88753](https://github.com/anthropics/claude-code/issues/88753) | \[BUG\] Compaction led to writing to wrong database in a way that could have destroyed production data | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | area:core, bug, data-loss, high-priority, platform:macos |
| [#88565](https://github.com/anthropics/claude-code/issues/88565) | \[BUG\] Auto mode silently disables path-scoped rules: it instructs the agent to edit files through Bash, and Bash edits never trigger rule injection | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-21 | area:bash, area:core, bug, has repro, platform:macos |
| [#60835](https://github.com/anthropics/claude-code/issues/60835) | \[MODEL\] Tests written by Claude wrote to production shared infrastructure (NAS) without isolation | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-05-20 | area:model, bug, has repro, model, platform:macos, stale |
| [#57164](https://github.com/anthropics/claude-code/issues/57164) | \[BUG\] Google OAuth login redirects to onboarding for existing Max subscriber, browser and desktop locked out while phone and CLI sessions remain authenticated | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-05-08 | area:auth, bug, platform:macos, stale |
| [#50516](https://github.com/anthropics/claude-code/issues/50516) | Allow opting out of the per-Read "malware" system-reminder — defense is porous and cost is non-consensual | CLOSED / NOT\_PLANNED | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-04-18 | area:security, area:tools, enhancement, platform:macos, stale |

</details>

### 🚨 Fresh critical signals

| Issue | Title | State | Signal | Updated | Created | Labels |
|---:|---|---|---|---|---|---|
| [#88867](https://github.com/anthropics/claude-code/issues/88867) | \[Feature Request\] Add organization-level opt-out for system prompt injections blocking multi-agent workflows | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | area:agents, enhancement, platform:windows |
| [#88866](https://github.com/anthropics/claude-code/issues/88866) | \[MODEL\] Claude repeats its previous response after an idle pause and stops reading the newest message | OPEN | security / trust boundary | 2026-08-22 | 2026-08-22 | area:core, area:desktop, bug, model, platform:windows |
| [#88865](https://github.com/anthropics/claude-code/issues/88865) | \[BUG\] Fabricated tool-call/tool-result blocks injected into conversation (VSCode extension) | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | area:core, area:model, area:security, bug, platform:vscode, platform:windows |
| [#88864](https://github.com/anthropics/claude-code/issues/88864) | \[BUG\] Qemu VM : arm64 OK , x86+KVM KO (hangs forever 100% CPU) , x86 KO (crashes) | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:installation, bug, has repro, platform:linux |
| [#88862](https://github.com/anthropics/claude-code/issues/88862) | Field report: concurrent sessions sharing one git clone — measured collisions, three userland mitigations, and the residue only the harness can fix | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | area:core, enhancement, platform:windows |

<details>
<summary>Show remaining 20</summary>

| Issue | Title | State | Signal | Updated | Created | Labels |
|---:|---|---|---|---|---|---|
| [#88861](https://github.com/anthropics/claude-code/issues/88861) | \[BUG\] \`best\` alias never falls back to Opus when Fable 5 is not usable — hard error at top level, silent Sonnet 5 as a subagent model | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | api:anthropic, area:model, bug |
| [#88860](https://github.com/anthropics/claude-code/issues/88860) | Mobile GUI effort slider doesn't reflect actual session effort level on open | OPEN | security / trust boundary | 2026-08-22 | 2026-08-22 | area:ui, bug |
| [#88859](https://github.com/anthropics/claude-code/issues/88859) | \[Bug\] Repeated safeguard errors blocking audio-visual analysis tasks | OPEN | observation / provenance integrity | 2026-08-22 | 2026-08-22 | area:tui, bug, platform:windows |
| [#88857](https://github.com/anthropics/claude-code/issues/88857) | Bash permission deny patterns bypassed by a flag prefix before the subcommand (e.g. git -C &lt;path&gt; checkout -- &lt;file&gt;) | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:permissions, area:security, bug, has repro, platform:windows |
| [#88856](https://github.com/anthropics/claude-code/issues/88856) | \[Bug\] False positive security flag on legitimate local dashboard development request | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | area:model, area:security, bug, platform:linux |
| [#88855](https://github.com/anthropics/claude-code/issues/88855) | \[BUG\] Remote Control disconnects an unrelated session when a different CLAUDE\_CONFIG\_DIR re-authenticates | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:auth, bug, has repro, platform:linux |
| [#88854](https://github.com/anthropics/claude-code/issues/88854) | \[BUG\] Paid Max 20x reverted to Free — paid invoice but billing\_type is none | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:auth, area:cost, bug, external, platform:macos |
| [#88853](https://github.com/anthropics/claude-code/issues/88853) | \[BUG\] Claude Code cloud session — Google Calendar connector enabledInChat intermittently false despite connected: true | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | area:claude-code-web, area:mcp, area:routines, bug, platform:web |
| [#88852](https://github.com/anthropics/claude-code/issues/88852) | Cloud review (/code-review ultra) fails consistently on large repo: "all review agents terminated before completing" | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:agents, bug, has repro, platform:macos |
| [#88851](https://github.com/anthropics/claude-code/issues/88851) | \[BUG\] Windows Store/MSIX: Cowork workspace blocked by PlantDetectedError, still reproducible on Claude Desktop 1.34493.1 | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | area:cowork, area:desktop, bug, platform:windows |
| [#88850](https://github.com/anthropics/claude-code/issues/88850) | Chat message sent while AskUserQuestion is open reports to the model as a user dismissal | OPEN | security / trust boundary | 2026-08-22 | 2026-08-22 | area:ui, bug, platform:windows |
| [#88849](https://github.com/anthropics/claude-code/issues/88849) | Agent tool: passing \`name:\` creates a teammate that never runs its prompt and never reports back | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | area:agents, duplicate, platform:linux |
| [#88848](https://github.com/anthropics/claude-code/issues/88848) | \[BUG\] Desktop: sessions sharing a working tree show each other's PRs in the PR tracker | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:agent-view, area:desktop, bug, has repro, platform:linux |
| [#88846](https://github.com/anthropics/claude-code/issues/88846) | /rename does not propagate to how the session appears in ListAgents on peer sessions | OPEN | security / trust boundary | 2026-08-22 | 2026-08-22 | area:agent-view, bug, platform:linux |
| [#88845](https://github.com/anthropics/claude-code/issues/88845) | \[BUG\] /rename name survives into the pre-/clear conversation, so peers see the wrong session name | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | area:agent-view, area:core, bug, has repro, platform:macos |
| [#88842](https://github.com/anthropics/claude-code/issues/88842) | \[BUG\] \`effortLevel: "high"\` in settings.json but requests are sent at \`low\` — local terminal, no Remote Control; session transcript records \`high\` | OPEN | security / trust boundary | 2026-08-22 | 2026-08-22 | area:core, bug, platform:macos |
| [#88841](https://github.com/anthropics/claude-code/issues/88841) | \[Feature Request\] Add token cost visibility and guardrails for subagent fork context inheritance | OPEN | security / trust boundary · observation / provenance integrity | 2026-08-22 | 2026-08-22 | area:agents, area:cost, enhancement, platform:windows |
| [#88840](https://github.com/anthropics/claude-code/issues/88840) | \`claude remote-control --permission-mode\` is silently ignored (plus: held cross-session messages have no approval surface) | OPEN | security / trust boundary · high-signal label | 2026-08-22 | 2026-08-22 | area:permissions, bug, has repro, platform:macos |
| [#88839](https://github.com/anthropics/claude-code/issues/88839) | AskUserQuestion option picker is unusable with NVDA screen reader | OPEN | security / trust boundary | 2026-08-22 | 2026-08-22 | area:a11y, area:tui, bug, platform:windows |
| [#88838](https://github.com/anthropics/claude-code/issues/88838) | \[BUG\] Two plugins can claim the same skill name and both install silently — and it ships in a real config today | OPEN | security / trust boundary · observation / provenance integrity · high-signal label | 2026-08-22 | 2026-08-22 | area:plugins, area:skills, bug, has repro, platform:linux |

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
