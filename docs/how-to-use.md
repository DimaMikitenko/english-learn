# Quick Start

## Commands
- `/start-c` — start a new conversation (greets you, asks a starter question, maybe flags a recurring mistake)
- `/save-c` — save the current conversation to `conversations/<date>/<time>.md`
- `/train-v` — vocabulary drill: 5 Ukrainian → English sentences, reviewed together at the end

## Typical session
1. Open chat, send `/start-c`
2. Chat normally in English — mistakes get corrected inline (👉 *Correction: ...*)
3. Run `/train-v` anytime for a quick vocab drill
4. Send `/save-c` when done to archive the conversation

## Where things live
- `conversations/<date>/<time>.md` — saved chat transcripts
- `vocabulary/<date>/partN.md` — saved `/train-v` rounds
- `progress/mistakes.md` — recurring mistake patterns + log of corrections

## Notes
- Full behavior rules are in [CLAUDE.md](../CLAUDE.md) at the repo root.
