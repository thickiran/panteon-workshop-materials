# Panteon Workshop Materials

Materials for the **AI-Assisted Game Development** workshop series prepared for Panteon Games by Codeo. All materials are available in **Turkish** (originals) and **English** (in the `en/` subfolders).

## Workshop 1 — AI-Assisted Game Development (one day)

A single-day program covering all eight modules of the module catalog, weighted toward Module 5 (Unity CLI and Pipeline), Module 6 (2D Art Production) and Module 7 (3D Model Production). Joint sessions in the morning; parallel engineering and art tracks in the afternoon.

| Material | Turkish | English |
|---|---|---|
| Agenda | `panteon_atolye_ajandasi_tr.pdf` | `en/panteon_workshop_agenda.pdf` |
| Track A lab guide (Coin Rush, Unity CLI) | `atolye_icerik/lab_kilavuzu_iz_a_unity_cli.pdf` | `atolye_icerik/en/lab_guide_track_a_unity_cli.pdf` |
| Track B lab guide (2D/3D pipeline) | `atolye_icerik/lab_kilavuzu_iz_b_2d_3d.pdf` | `atolye_icerik/en/lab_guide_track_b_2d_3d.pdf` |
| Presentations (6 decks) | `atolye_icerik/sunumlar/` | `atolye_icerik/sunumlar/en/` |

Decks: opening & foundations · quick tour (Claude Code / JetBrains / Unity AI) · Unity CLI joint session · Track A lab · Track B lab · closing.

## Workshop 2 — AI in a Real Codebase (advanced, one day)

The follow-up workshop, run ~90 days after the first: working with an agent inside a living codebase (Unity's official match-3 sample, Gem Hunter Match). Engineering extends the game and hunts bugs; art reskins it in the studio style.

| Material | Turkish | English |
|---|---|---|
| Agenda | `panteon_ileri_atolye_ajandasi_tr.pdf` | `en/panteon_advanced_workshop_agenda.pdf` |
| Track A lab guide (Gem Hunter) | `atolye2_icerik/lab_kilavuzu_iz_a_gem_hunter.pdf` | `atolye2_icerik/en/lab_guide_track_a_gem_hunter.pdf` |
| Track B lab guide (reskin) | `atolye2_icerik/lab_kilavuzu_iz_b_reskin.pdf` | `atolye2_icerik/en/lab_guide_track_b_reskin.pdf` |
| Presentations (5 decks) | `atolye2_icerik/sunumlar/` | `atolye2_icerik/sunumlar/en/` |

Decks: opening & 90-day review · the agent in a foreign codebase + live demo · Track A lab · Track B lab · closing.

## Companion project repositories

The hands-on labs run on two Unity projects, kept in their own (private) repositories:

- [coin-rush-workshop](https://github.com/thickiran/coin-rush-workshop) — Workshop 1, Track A: a mini mobile game built end to end in 9 exercises with Claude Code and Unity CLI.
- [gem-hunter-workshop](https://github.com/thickiran/gem-hunter-workshop) — Workshop 2: Gem Hunter Match with git checkpoint branches (`ex01-start` … `complete`) and `catchup.sh` sync tooling.

## Notes

- English presentation decks are direct in-place translations of the Turkish decks — identical layout and design, slide for slide.
- English PDFs are rebuilt to the same design as the Turkish originals.
- The exercise-level instructions inside the project repositories (`README`/`Ex0N_*.md` files) are written in English in both repos.
