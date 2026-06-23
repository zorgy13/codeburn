# Conflict Report

- Project: `codex-please-implement-this-plan-codeburn`
- Integration worktree: `/Users/vadimirrosman/.Codex/codex-backups/worktrees/git-mass-branch-cleanup/home-.codex-worktrees-codeburn-codex-please-implement-this-plan-codeburn-1782224704`
- Branch: `integration/test`
- Reviewed branch: `codex/codeburn-five-minute-token-refresh`
- Dirty source worktree reviewed: `/Users/vadimirrosman/Documents/Codex Project/Life/vendor/codeburn`
- Status: `resolved_for_partial_import`

## Resolved Merge Conflicts

| File | Resolution |
|---|---|
| `src/codex-cache.ts` | Kept cache version `7`, preserving MCP attribution reparse plus later Codex token reporting cache-shape changes. |
| `src/daily-cache.ts` | Kept daily cache version `10`, preserving provider backfill rehydration plus Codex transcript-estimate fallback. |
| `src/providers/codex.ts` | Kept MCP `event_msg` / `mcp_tool_call_end` attribution and transcript input accounting with `role !== 'assistant'`. |
| `src/session-cache.ts` | Combined parse versions for Cursor Agent, Codex transcript estimates, Copilot MCP normalization, and Hermes reasoning accounting. |

## Resolved Dirty Patch Conflicts

| File | Resolution |
|---|---|
| `mac/Sources/CodeBurnMenubar/Data/MenubarPayload.swift` | Kept both subscription-cost fields and `codexCredits` in `CurrentBlock.CodingKeys`. |
| `src/config.ts` | Kept Grok plan ids/providers and added `SubscriptionCostMode`. |
| `src/usage-aggregator.ts` | Kept `aggregateModels` import and `OptimizeResult` typed import. |

## Follow-up Fixes From Verification

- Removed duplicate `reasoningTokens` addition in `src/parser.ts`.
- Added bare `MiniMax-M3` direct-price override while preserving provider-prefixed reseller keys.
- Raised Vitest timeout to `60_000` so package-level `npm test` covers slow spawn-based CLI tests.

## Verification

| Command | Result |
|---|---|
| `rg -n '^(<<<<<<<|=======|>>>>>>>)' src mac tests` | `pass`, no conflict markers found. |
| `git diff --check && git diff --cached --check` | `pass`. |
| `npx tsc --noEmit` | `pass`. |
| `npm test` | `pass`, `106` test files and `1307` tests passed. |
| `npm run build` | `pass`, CLI and dashboard built. |

## Remaining Blocker

CodeBurn is not safe for branch/worktree cleanup yet. This partial import resolves the reviewed merge/dirty conflicts, but the project still has many branches not manually imported and not inclusion-verified. Push and deletion remain blocked until all remaining branch/stash/patch surfaces are reviewed.
