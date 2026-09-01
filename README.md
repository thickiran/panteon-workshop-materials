# Panteon Workshop Materials

Materials for the **AI-Assisted Game Development** workshop prepared for Panteon Games by Codeo.

## The single-day program (current)

One intensive day for a team that already uses Claude Code daily — no tool introductions, just practice. The arc: **Unity CLI from scratch in the morning** (empty scene → playable mini game, hands-on in Coin Rush), then **a living codebase in the afternoon** (Unity's official match-3 sample, Gem Hunter Match, ~4,800 lines). One trainer; the engineering and art tracks run back to back, and anyone may sit in on the other track.

| Time | Session |
|---|---|
| 09:30 – 10:00 | Opening: foundations, art approval process, baseline metrics + meeting Gem Hunter |
| 10:00 – 11:00 | Unity CLI from scratch — hands-on (Coin Rush) |
| 11:15 – 12:30 | The agent in a foreign codebase + live demo: BUG-312 |
| 13:30 – 15:00 | Track A: Gem Hunter engineering lab (compressed) — Engineering + DevOps |
| 15:15 – 16:45 | Track B: Reskinning Gem Hunter — Art + Tech Art |
| 16:45 – 17:30 | Closing: the combined game, the four traps, the 90-day plan |

### Materials

- `single_day/panteon_single_day_agenda.pdf` — the agenda
- `single_day/lab_guide_track_a_gem_hunter.pdf` — Track A lab guide (Gem Hunter)
- `single_day/lab_guide_track_b_reskin.pdf` — Track B lab guide (reskin)
- `single_day/slides/` — 6 decks: opening · Unity CLI from scratch · the agent in a foreign codebase + demo · Track A lab · Track B lab · closing

## Explainer video

A 1-minute overview of the workshop: `video/panteon_workshop_explainer_en.mp4` (a Turkish cut, `video/panteon_atolye_tanitim_tr.mp4`, is kept from before the project went English-only).

## Companion project repositories

- [coin-rush-workshop](https://github.com/thickiran/coin-rush-workshop) — the morning's from-scratch project: a mini mobile game with 9 CLI exercises and checkpoint scenes.
- [gem-hunter-workshop](https://github.com/thickiran/gem-hunter-workshop) — the afternoon's project: Gem Hunter Match with git checkpoint branches (`ex01-start` … `complete`) and `catchup.sh` sync tooling.

Exercise-level instructions inside both repos (`README`/`Ex0N_*.md`) are in English.

## Archive

`arsiv/` holds the original two-workshop structure this program was consolidated from — a foundations day (Coin Rush, all eight modules) and a separate advanced day (Gem Hunter) run ~90 days apart, in Turkish and English. Useful if the two-day sequence is ever needed for a less AI-experienced audience.
