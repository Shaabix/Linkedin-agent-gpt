# Upstream source parity ledger

Canonical upstream: https://github.com/avi691/linkedin-agent-skill  
Pinned snapshot: `e4ec4fb6f1b0e227eb9b14b31b735072db5df9cb`  
License: MIT. Preserve upstream notices and attribution.

## Required exact upstream assets
- `skills/li-post/hooks.json` — 21 hook formulas
- `skills/li-profile/rubric.json` — 12-part, 100-point profile rubric
- `skills/li-human/slop.json` — cleanup lexicon and detection patterns
- `skills/li-human/humanize.py`
- `skills/li-human/detect.py`
- all eleven `skills/li-*/SKILL.md` files
- `templates/voice.md`
- `README.md` and `LICENSE`

## Honest status
This archive contains a ChatGPT workflow scaffold and a parity checklist. It does **not** contain the exact hook/rubric/lexicon JSON or original Python scripts and is not full feature parity. Those assets must be copied from the pinned upstream snapshot before claiming a complete port. Claude plugin manifests should be adapted, not represented as ChatGPT integration.

## Porting and validation
1. Copy the original assets from the pinned commit and preserve copyright/license notices.
2. Keep formulas, rubric weights, lexicon, and scripts unchanged initially.
3. Replace Claude-specific paths (voice, plan, log) with explicit ChatGPT Project/file workflows; don't claim persistence if unavailable.
4. Run tests for the scripts in a real Python environment and record actual results.
5. Mark each feature as preserved, adapted, manual fallback, or not implemented.
