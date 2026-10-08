# rune adapter

This fork exists so rune's build-design-system can stand on upstream work instead of rebuilding it.
Rule: never edit upstream files here; rune-side changes live only in this rune/ directory.
Weekly sync: `git fetch upstream` then fast-forward main; re-check this adapter after each sync.

- Upstream: https://github.com/pbakaus/impeccable
- Licence notice: Apache-2.0; full text in the upstream LICENSE file.
- What we use: review loop and .pi harness adapter; audit.md 5-dimension scan as upstream input.
- Rune seam: rune plugins/software-dev/scripts/ds_antipattern.py and ds_tokens.py audit, which remain the gates (this fork is input, never a replacement).
