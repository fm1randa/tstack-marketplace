# tstack-marketplace

Claude Code marketplace `tstack-marketplace` wrapping [t3dotgg/tstack](https://github.com/t3dotgg/tstack) at `11e37a74d0a6868c121cd0910ab2b3bd9873b92a`.

Plugin id: `tstack@tstack-marketplace`.

Reviewer: Codex Sol when that provider can run a child task. Otherwise Claude
`claude-sonnet-5-5` at effort `medium`, then Grok `grok-4.7-build-fast` at
reasoning effort `medium`, then OpenCode `opencode-go/deepseek-v4.1-flash` at
variant `high`, skipping the parent provider.

Install:

```bash
claude plugin marketplace add fm1randa/tstack-marketplace
claude plugin install tstack@tstack-marketplace --scope user
```
