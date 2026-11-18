# On Deck

A concept website for young softball players. On Deck helps them see every future softball can lead to, whether that is playing in college, going pro with the AUSL, coaching, training or healing athletes, working in sports media, or playing for the love of the game.

This is a class prototype for an innovation course. It is not a finished product.

## View the website

| Version | Link | Date | Notes |
|---|---|---|---|
| Latest (V3) | [kmfree2004.github.io/On-Deck-V1/v3/](https://kmfree2004.github.io/On-Deck-V1/v3/) | Nov 18, 2026 | Dropdown menus, new spotlights, My plan |
| V2 | [kmfree2004.github.io/On-Deck-V1/v2/](https://kmfree2004.github.io/On-Deck-V1/v2/) | Nov 17, 2026 | Built after round 1 feedback |
| V1 | [kmfree2004.github.io/On-Deck-V1/v1/](https://kmfree2004.github.io/On-Deck-V1/v1/) | Built Nov 4, 2026 | First prototype players and coaches tried |

The [version picker](https://kmfree2004.github.io/On-Deck-V1/) lists every version and always links to the newest one.

## The problem

Many softball players are not given enough guidance about their futures, in softball or outside it. An On Deck survey of 35 current players, 21 former players and 3 coaches found that interest, perceived realism, money and awareness are separate issues. Many players love softball and want it in their lives without wanting it as a career.

The innovation question is how players can see the full range of futures softball can lead to, with pro play as one visible and realistic option among many, and with "I just want to play" respected as a complete answer.

## What is on the site (V3)

The menu is grouped into dropdowns.

- **Explore:** a six-question quiz that suggests a future for today, and six pathways (college, pro, coaching, training and healing, media and business, play for fun) with what each looks like and what it takes.
- **Real talk:** public facts about the AUSL and ways onto a roster, pro spotlights, and mentor matching. Spotlights and mentors are sample layouts.
- **Get recruited:** a read-only guide with age-by-age steps, email templates, camp and showcase advice and recruiting basics, plus **My plan**.
- **My plan:** a profile, progress checklist, email builder, saved emails and a school tracker. It saves in the visitor's own browser. There are no accounts, and nothing is sent to a server. The data can be downloaded as a file and loaded back.
- **For coaches:** conversation starters and ways to describe pro softball accurately.

## Version history

| Version | Date | What changed |
|---|---|---|
| V1 | Nov 4, 2026 | First prototype with a quiz, pathways, real numbers, pro spotlights, mentors, guide and coach toolkit. |
| V2 | Nov 17, 2026 | Changes after round 1 feedback (4 responses: 3 players and 1 coach). Expanded recruiting guide, mentor matching explainer, extra sourced statistic, coach toolkit tip, fixed non-working footer buttons and tab display. |
| V3 | Nov 18, 2026 | Changes from the project owner's own review of V2, not from tester feedback. Grouped dropdown menus, pro spotlights redesigned around questions every player answers, guide lists made read-only, and a new My plan section that saves progress, email drafts and a school tracker in the browser. |

Round 1 feedback that was not acted on: a request for a form where players leave contact details to schedule time with mentors. It was left out because the prototype has no way to send the information, and collecting contact details from minors needs a safeguarding plan first.

## About accounts and saved data

V3 has no login. My plan keeps data in the visitor's browser on one device, which means nothing is collected from players, including minors. Real accounts that sync across devices would need a hosted back end, a privacy policy, and consent from a parent or guardian for players under 13. That is a possible later step and is not built.

## Repository layout

```
index.html        Version picker (links to every version)
v1/index.html     Version 1, kept unchanged
v2/index.html     Version 2, kept unchanged
v3/index.html     Version 3, the latest
README.md         This file
```

Each version is one self-contained HTML file with no build step.

## Adding a new version

1. Create a new folder, for example `v4`, with the new `index.html` inside it. Leave older folders unchanged.
2. Add a card for it to the root `index.html` and point the "latest" button at the new folder.
3. Add a row to the version history above.

## Notes

- The player profiles and mentors are placeholders. This project is not affiliated with or endorsed by the AUSL or TOGETHXR.
- AUSL facts come from public sources, including [theausl.com](https://theausl.com), and the league may have changed details since.
- The NCAA statistic comes from the [NCAA](https://www.ncaa.org/sports/2024/4/15/softball-probability-of-competing-beyond-high-school.aspx).
- Survey figures are self-reported and the samples are small.
- The prototype was built with help from Claude, an AI assistant from Anthropic.
