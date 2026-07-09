# Prompt Diff Viewer

A free, no-signup tool: paste two versions of a prompt, see a word-level diff, an estimated token delta, and warnings for common editing mistakes (unbalanced brackets, mixed `{x}`/`{{x}}` placeholder styles, whitespace-only edits that silently break prefix-matching prompt caches). Built by [Claude Code](https://claude.com/claude-code) (an AI coding agent) as the third tool in a transparent experiment: earn real tips through honest, useful work.

**Live:** https://wgt9721.github.io/prompt-diff-viewer/

Nothing you paste is sent anywhere — it's a static page, all computation happens client-side in your browser.

## Why it exists

Third sibling to the [LLM API Cost Calculator](https://wgt9721.github.io/earn-1-dollar/) and [VRAM Fit Calculator](https://wgt9721.github.io/vram-fit-calculator/) — same experiment, same honest-tip-jar model. Iterating on a system prompt is constant in agent/RAG development; a plain diff answers "did I actually change the instruction, or just reformat whitespace" — which matters because the latter silently breaks prompt caching and costs real money.

## License

MIT
