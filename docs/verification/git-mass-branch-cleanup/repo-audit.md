# Repo Audit: codex-please-implement-this-plan-codeburn

- Primary path: `/Users/vadimirrosman/.codex/worktrees/codeburn/codex-please-implement-this-plan-codeburn`
- Common dir: `/Users/vadimirrosman/Documents/Codex Project/Life/vendor/codeburn/.git`

## pwd

```text
$ pwd
exit=0
/Users/vadimirrosman/.codex/worktrees/codeburn/codex-please-implement-this-plan-codeburn
```

## git status

```text
$ git status
exit=0
On branch codex/please-implement-this-plan-codeburn-rebased
Your branch is up to date with 'zorgy13/codex/please-implement-this-plan-codeburn-rebased'.

nothing to commit, working tree clean
```

## git diff

```text
$ git diff
exit=0

```

## git diff --staged

```text
$ git diff --staged
exit=0

```

## git branch --show-current

```text
$ git branch --show-current
exit=0
codex/please-implement-this-plan-codeburn-rebased
```

## git log --oneline --decorate -30

```text
$ git log --oneline --decorate -30
exit=0
d0b925b (HEAD -> codex/please-implement-this-plan-codeburn-rebased, zorgy13/codex/please-implement-this-plan-codeburn-rebased) fix(codeburn): restore menubar project token reporting
dcdfbc1 (origin/main, origin/HEAD, integration/test) docs(changelog): credit @vaibhavarora14 for #486 (#552)
69eee2c (tag: v0.9.14, tag: mac-v0.9.14) chore(release): 0.9.14 (#551)
71b1a9e fix: clean model names in reports and re-hydrate daily cache for new providers (#550)
f26f4ad fix(menubar): show every active agent as a tab, ordered by usage for the selected range (#549)
163013f fix(pi): label gpt-5.5 as GPT-5.5 (#548)
454d836 fix(menubar): surface CLI stdout/stderr on decode failure (#515) (#547)
99a90cb fix(copilot): Correct shell commands and skills/agents display (#527)
d54f21d fix(antigravity): read current agy antigravity-cli on-disk layout (#541)
4dcb7e6 fix(models): price Hermes lowercase glm-5.2 the same as GLM-5.2 (#545)
10d911d fix(cursor-agent): ingest workspace-less CLI transcript layout (#542)
7c2d36f Distinguish gpt-5.3-codex-spark from base GPT-5.3 Codex label (#539)
102ce73 docs(readme): add Hermes Agent to the supported-tools grid (31 tools)
d68e8ec Merge pull request #544 from getagentseal/feat/hermes-provider-rebased
e80da31 fix(hermes): use sessions.cwd, flag estimated cost, propagate SQLITE_BUSY
645b3c2 feat: add Hermes Agent provider
a12db6e Show real Claude project leaf names; stop stray-.git over-grouping (#540)
da20ec6 docs(readme): drop redundant X label from follow badge
9344fdc docs(readme): add X follow badge (@_codeburn)
5fd1160 docs: add ZCode to the supported-tools logo grid (#538)
9ce6498 feat(providers): add ZCode (z.ai GLM-5.2) usage provider (#537)
16d2f7e feat(devices): joined Totals by machine report (#536)
98befc1 feat(overview): cache in/out tokens table, roomier tables (#535)
1dba4e0 feat(web): in-dashboard device discovery, share-from-browser, redesign + hardening (#534)
3ac7f68 feat(web): show usage by device in the dashboard (#533)
887374d feat(sharing): securely combine usage across your own devices (#532)
2d44aea feat(web): local React dashboard served by codeburn web (#531)
75c32e6 fix: fix and improve test isolation and collision with environment (#530)
60410a2 chore(dev): silence the tsx module.register deprecation warning (#529)
c55dba2 feat(overview): plain-text monthly usage overview command (#528)
```

## git remote -v

```text
$ git remote -v
exit=0
origin	https://github.com/getagentseal/codeburn.git (fetch)
origin	https://github.com/getagentseal/codeburn.git (push)
zorgy13	https://github.com/zorgy13/codeburn.git (fetch)
zorgy13	https://github.com/zorgy13/codeburn.git (push)
```

## git branch -vv

```text
$ git branch -vv
exit=0
+ codex/codeburn-five-minute-token-refresh          06460c8 (/Users/vadimirrosman/Documents/Codex Project/Life/vendor/codeburn) Merge branch 'codex/sodeburn-snova-ne-rabotaet-nuzhno-ra'
  codex/please-implement-this-plan-codeburn         8ec5c4c [zorgy13/codex/please-implement-this-plan-codeburn] fix(codeburn): restore menubar token reporting
* codex/please-implement-this-plan-codeburn-rebased d0b925b [zorgy13/codex/please-implement-this-plan-codeburn-rebased] fix(codeburn): restore menubar project token reporting
  codex/restore-codeburn-today-tokens               8e46009 fix(codex): content-address fork dedupe key to stop undercounting divergent events (#458)
  codex/sodeburn-snova-ne-rabotaet-nuzhno-ra        8094aaa fix(codeburn): restore Codex daily token reporting
+ integration/test                                  dcdfbc1 (/Users/vadimirrosman/.Codex/codex-backups/worktrees/git-mass-branch-cleanup/home-.codex-worktrees-codeburn-codex-please-implement-this-plan-codeburn-1782224089) [origin/main] docs(changelog): credit @vaibhavarora14 for #486 (#552)
  main                                              06460c8 [origin/main: ahead 2, behind 70] Merge branch 'codex/sodeburn-snova-ne-rabotaet-nuzhno-ra'
```

## git branch --all

```text
$ git branch --all
exit=0
+ codex/codeburn-five-minute-token-refresh
  codex/please-implement-this-plan-codeburn
* codex/please-implement-this-plan-codeburn-rebased
  codex/restore-codeburn-today-tokens
  codex/sodeburn-snova-ne-rabotaet-nuzhno-ra
+ integration/test
  main
  remotes/origin/HEAD -> origin/main
  remotes/origin/add-zerostack-logo
  remotes/origin/chore/add-firstlook-workflow
  remotes/origin/chore/bump-0.8.7
  remotes/origin/chore/bump-0.8.8
  remotes/origin/chore/bump-0.9.7
  remotes/origin/chore/changelog-omp-model-alias
  remotes/origin/chore/firstlook-workflow-dispatch
  remotes/origin/chore/silence-dev-warning
  remotes/origin/feat/add-minimax-pricing
  remotes/origin/feat/antigravity-provider
  remotes/origin/feat/auto-pricing-models-dev-openrouter
  remotes/origin/feat/cache-durability
  remotes/origin/feat/codeburn-mcp
  remotes/origin/feat/codex-result-cache
  remotes/origin/feat/dashboard-devices
  remotes/origin/feat/dashboard-discovery
  remotes/origin/feat/day-review-selector
  remotes/origin/feat/device-sharing
  remotes/origin/feat/devices-report
  remotes/origin/feat/estimated-cost-indicator
  remotes/origin/feat/gnome-extension-enhanced
  remotes/origin/feat/goose-provider
  remotes/origin/feat/ibm-bob-provider
  remotes/origin/feat/mac-app-icon
  remotes/origin/feat/mac-hide-agent-tabs-when-single-provider
  remotes/origin/feat/mcp-tool-coverage
  remotes/origin/feat/menubar-claude-config-dirs
  remotes/origin/feat/menubar-compact
  remotes/origin/feat/menubar-hardening
  remotes/origin/feat/menubar-optimize-insights
  remotes/origin/feat/model-comparison
  remotes/origin/feat/omp-support-model-aliases
  remotes/origin/feat/openclaw-roocode-kilocode
  remotes/origin/feat/optimize
  remotes/origin/feat/overview-cache
  remotes/origin/feat/overview-command
  remotes/origin/feat/tauri-menubar-win-linux
  remotes/origin/feat/warp-provider
  remotes/origin/feat/web-dashboard
  remotes/origin/feat/windows-menubar-tauri
  remotes/origin/feat/windows-tauri-parity
  remotes/origin/feat/yield-tracking
  remotes/origin/fix-opencode-mcp-usage
  remotes/origin/fix/antigravity-codex-dedup
  remotes/origin/fix/claude-1h-cache-pricing
  remotes/origin/fix/cli-input-validation
  remotes/origin/fix/compound-path-fingerprint
  remotes/origin/fix/copilot-cost-estimated-label
  remotes/origin/fix/cursor-cost-tracking
  remotes/origin/fix/cursor-undated-bubbles
  remotes/origin/fix/daily-cache-utc-gap-fill
  remotes/origin/fix/dormant-keychain-prompt
  remotes/origin/fix/forecast-currency
  remotes/origin/fix/jetbrains-tests-and-winpath
  remotes/origin/fix/menubar-all-tab-stale-refresh
  remotes/origin/fix/menubar-auto-refresh
  remotes/origin/fix/menubar-bug-sweep
  remotes/origin/fix/menubar-checksum-verification
  remotes/origin/fix/menubar-dataclient-deadlock
  remotes/origin/fix/menubar-disable-appnap
  remotes/origin/fix/menubar-force-redraw
  remotes/origin/fix/menubar-installer-wait
  remotes/origin/fix/menubar-keychain-appnap
  remotes/origin/fix/menubar-loading-watchdog
  remotes/origin/fix/menubar-perf-and-cache-safety
  remotes/origin/fix/menubar-remove-prefetchall
  remotes/origin/fix/menubar-sleep-and-refresh-sync
  remotes/origin/fix/menubar-stale-cache
  remotes/origin/fix/menubar-tab-refresh-recovery
  remotes/origin/fix/menubar-tahoe-status-item
  remotes/origin/fix/menubar-timezone-184
  remotes/origin/fix/menubar-today-cache-staleness
  remotes/origin/fix/menubar-version-prefix
  remotes/origin/fix/menubar-wake-tabs
  remotes/origin/fix/models-report-cache-read-double-count
  remotes/origin/fix/mux-drop-dead-openai-branch
  remotes/origin/fix/negative-parse-cache
  remotes/origin/fix/network-fetch-timeouts
  remotes/origin/fix/node-version-guard
  remotes/origin/fix/oneshot-rate-detection
  remotes/origin/fix/oom-buffer-reader-and-large-line-parser
  remotes/origin/fix/parser-string-content-resilience
  remotes/origin/fix/plan-connect-claude-button
  remotes/origin/fix/pre-release-cleanup
  remotes/origin/fix/project-path-display
  remotes/origin/fix/remove-internal-docs
  remotes/origin/fix/revert-aicrowd-cache-rewrite
  remotes/origin/fix/settings-currency-picker
  remotes/origin/fix/streaming-dedup
  remotes/origin/fix/strip-ansi-bash-commands
  remotes/origin/fix/timeframe-crash
  remotes/origin/fix/timezone-stable-tests
  remotes/origin/fix/view-persistence-and-compare-period-hints
  remotes/origin/fix/windows-powershell
  remotes/origin/main
  remotes/zorgy13/codex/please-implement-this-plan-codeburn
  remotes/zorgy13/codex/please-implement-this-plan-codeburn-rebased
```

## git worktree list

```text
$ git worktree list
exit=0
/Users/vadimirrosman/Documents/Codex Project/Life/vendor/codeburn                                                                                                06460c8 [codex/codeburn-five-minute-token-refresh]
/Users/vadimirrosman/.Codex/codex-backups/worktrees/git-mass-branch-cleanup/home-.codex-worktrees-codeburn-codex-please-implement-this-plan-codeburn-1782224089  dcdfbc1 [integration/test]
/Users/vadimirrosman/.codex/worktrees/codeburn/codex-please-implement-this-plan-codeburn                                                                         d0b925b [codex/please-implement-this-plan-codeburn-rebased]
```

## git stash list

```text
$ git stash list
exit=0

```

## git tag --list

```text
$ git tag --list
exit=0
backup-pre-pr59-merge
mac-v0.7.2
mac-v0.7.3
mac-v0.7.4
mac-v0.7.5
mac-v0.8.0
mac-v0.8.1
mac-v0.8.2
mac-v0.8.4
mac-v0.8.5
mac-v0.8.6
mac-v0.8.7
mac-v0.8.8
mac-v0.8.9
mac-v0.9.0
mac-v0.9.10
mac-v0.9.11
mac-v0.9.12
mac-v0.9.13
mac-v0.9.14
mac-v0.9.3
mac-v0.9.4
mac-v0.9.5
mac-v0.9.6
mac-v0.9.7
mac-v0.9.8
mac-v0.9.9
v0.1.0
v0.1.1
v0.1.2
v0.2.0
v0.4.1
v0.4.3
v0.4.4
v0.5.0
v0.5.1
v0.5.2
v0.5.3
v0.5.4
v0.5.5
v0.5.6
v0.5.7
v0.6.1
v0.7.0
v0.7.1
v0.7.3
v0.7.4
v0.8.0
v0.8.1
v0.8.2
v0.8.3
v0.8.5
v0.8.7
v0.8.8
v0.8.9
v0.9.0
v0.9.1
v0.9.10
v0.9.11
v0.9.12
v0.9.14
v0.9.2
v0.9.3
v0.9.4
v0.9.5
v0.9.6
v0.9.7
v0.9.8
v0.9.9
```
