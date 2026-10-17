# HATH Kitchen

A Claude Project setup I use to teach myself to cook, plan meals, track grocery costs and cut food waste.

The idea isn't recipes. It's a feedback loop: plan, cook, measure, correct. Claude keeps a few running records and reads them before it plans anything, so each week's plan is better than the last.

## What's here

| File | What it is |
|---|---|
| [`HATH-Kitchen-Instructions.md`](HATH-Kitchen-Instructions.md) | The Project instructions, as a template. Paste into a Claude Project and fill in the [brackets] with your household. |
| [`inventory-template.html`](inventory-template.html) | A blank kitchen inventory page: Have / Low / Out taps, use-by dates, a store filter (add your own stores; an item can belong to several), a generated shopping list per store, and a waste log. Your list is saved only in your own browser. |

## How it works

- **Standing rules.** Stove heat as a 1–10 dial number, pull temperatures instead of cook times, real measurements only, and warnings about common mistakes before they happen.
- **A skill ladder.** 18 steps from knife skills to improvising from what's in the fridge. Claude teaches the next one when a recipe calls for it.
- **Who eats what.** Short notes on each person's food rules, so the plan fits the table without re-explaining.
- **Running records** that Claude checks before every plan:
  - an inventory of what's on hand,
  - a price ledger that reconciles each receipt against the estimate,
  - a waste log, where anything tossed twice in 30 days gets cut on the next list,
  - a list of mistakes that grows after every cook that goes wrong.

The first receipt I reconciled was within $0.08 on the 20 planned items I actually bought, and the trip was still $90 over budget, all from off-list buying. That's the kind of thing this setup surfaces.

## Getting started

1. Create a Project in Claude and paste in `HATH-Kitchen-Instructions.md`.
2. Replace the [brackets] with your own eaters, stores and equipment.
3. Ask Claude to publish `inventory-template.html` as an artifact for you, or open the file in a browser.
4. Start with "plan this week's dinners" and let it ask what's already in the house.

## License

Source-available, free for noncommercial use. This is not an open source license.

- **Code** (`inventory-template.html`): [PolyForm Noncommercial 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0).
- **Text** (the instructions, this README, everything else): [Creative Commons Attribution-NonCommercial 4.0](https://creativecommons.org/licenses/by-nc/4.0/) (CC BY-NC 4.0).

You can use, copy, share, and change any of it for anything noncommercial, as long as you credit me and keep the license notices. See [LICENSE](LICENSE) for which file falls under which license.

Want to use it commercially? You need a separate license from me. Email gpetermaloney@gmail.com.

Versions published through October 16, 2026 were released under the MIT License. If you got a copy then, those MIT rights stay with that copy. Everything after is under the licenses above only.
