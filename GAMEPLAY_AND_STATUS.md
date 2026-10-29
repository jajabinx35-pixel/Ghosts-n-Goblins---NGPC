# Ghosts 'n Goblins NGPC — Gameplay, modes and status

**Status: Work in progress — no public NGPC ROM yet.** This is a progress page, not a playable release.

## Modes

**Classic:** the recognisable Ghosts 'n Goblins challenge and original-style visuals. The standard completion does not include the extra SNK crossover fight.

**SNK World:** an optional story path involving the portal, new art and crossover scenes. The end follows the original final boss with the Terry / Evil Ryu fight, dialogue, gifts and a return to the classic world. Previewing SNK sprites with a cheat is not the same thing as completing the story path.

## Controls

| Input | In-game use |
| --- | --- |
| D-pad | Move, jump positioning, climb ladders; menu navigation |
| A | Throw / attack, menu confirm |
| B | Jump; back/cancel in menus |
| Option | Pause and in-game menu shortcuts |

The individual screen prompts take precedence in special scenes, menus and the crossover fight. For that fight, **A throws, B jumps and Left/Right move**.

## Records, lives and continues

There are settings for starting lives and continues. The continues menu permits **1–9**; zero is not a permitted setting. For ranked scores, use **no more than three starting lives and three starting continues**. Four or more locks ranked scoring. Earned extra lives during play do not trigger that starting-setting restriction.

A **Free** save can be reused but makes the run unranked. **Ranked** mode uses a one-use saved checkpoint, preventing repeated checkpoint attempts from unfairly preserving rank. Cheats and debug stage selection disable ranked scores. Records screens include QR-code support; the live external submission service is not being advertised as available yet.

## SNK guest helpers

The current game includes an assistance system with Ryu, Ken, Chun-Li, Akuma, Morrigan, Terry, Kyo, Iori, Mai and Athena. A chance-based offer is available at certain deaths; guests use their own sprite/attack handling. If a stage key appears while a guest is active, the game switches control back to Arthur so normal progression and key collection can continue. The final stage does not enable these guest assists.

## Development verification (M51R1)

- The Terry disappearance issue in the crossover fight was fixed. Arthur is scaled up in this arena while normal stage scaling stays unchanged.
- Automated NGPCraft tests cover controlled original-final-boss encounters, ending branches, dialogues, gifts, return and rolling credits.
- The M51 optimisation has controlled, sound-on performance-lap comparisons across all seven stages in Classic and SNK-style artwork.
- The reported checks involve emulator fixtures and are **not** equivalent to a full end-to-end human playthrough or certified hardware compatibility.

The screenshots in this README show native renders from the supplied game ROM. Stage 2–7 previews were reached via the game's hidden stage-select, so the **LOCKED** score message is expected. The special ending gallery was captured with reproducible native emulator fixtures. Images were scaled using nearest-neighbour, not redrawn or generated.

## Releases

**None yet.** This GitHub update contains documentation and screenshots only. Please do not interpret the upstream Amiga files already in the fork as NGPC build or installation files.

## Draft instruction booklet and case concept

The current documentation package also contains the [M50 instruction manual (12-page PDF)](Ghosts_n_Goblins_M50_Manual.pdf), the [cover illustration](manual-cover.png), and a [case/booklet concept image](box-and-manual-concept.png). They are fan-made design and instruction previews, not an official boxed edition. The M50 manual is older than the M51R1 screenshot build; specific features are subject to later revisions.
