# On Deck

A concept website for young softball players. On Deck helps them see every future softball can lead to, whether that is playing in college, going pro with the AUSL, coaching, training or healing athletes, working in sports media, or playing for the love of the game.

This is a class prototype for an innovation course. It is not a finished product.

## View the website

| Version | Link | Date | Notes |
|---|---|---|---|
| Latest (V4) | [kmfree2004.github.io/On-Deck-V1/v4/](https://kmfree2004.github.io/On-Deck-V1/v4/) | Nov 18, 2026 | The Dugout, Find the spark, clearer Get recruited |
| V3 | [kmfree2004.github.io/On-Deck-V1/v3/](https://kmfree2004.github.io/On-Deck-V1/v3/) | Nov 18, 2026 | Dropdown menus, new spotlights, My plan |
| V2 | [kmfree2004.github.io/On-Deck-V1/v2/](https://kmfree2004.github.io/On-Deck-V1/v2/) | Nov 17, 2026 | Built after round 1 feedback |
| V1 | [kmfree2004.github.io/On-Deck-V1/v1/](https://kmfree2004.github.io/On-Deck-V1/v1/) | Built Nov 4, 2026 | First prototype players and coaches tried |

The [version picker](https://kmfree2004.github.io/On-Deck-V1/) lists every version and always links to the newest one.

## The problem

Many softball players are not given enough guidance about their futures, in softball or outside it. An On Deck survey of 35 current players, 21 former players and 3 coaches found that interest, perceived realism, money and awareness are separate issues. Many players love softball and want it in their lives without wanting it as a career.

The innovation question is how players can see the full range of futures softball can lead to, with pro play as one visible and realistic option among many, and with "I just want to play" respected as a complete answer.

## What is on the site (V4)

The menu is grouped into dropdowns.

- **Explore:** a six-question quiz, six pathways (college, pro, coaching, training and healing, media and business, play for fun), and **Find the spark**, a page for players who want to love the game again.
- **Real talk:** public facts about the AUSL and ways onto a roster, spotlights of pro players, college players and coaches (sample layouts, one question at a time), and mentor matching.
- **Get recruited:** a read-only Guide that begins with a Start here tab, **My plan**, **Find a travel team** and **Resources** (FieldLevel, the NCAA Eligibility Center, USA Softball and the AUSL).
- **My plan:** a profile, checklist, email builder, saved emails, school tracker and school notes. It saves in the visitor's own browser. There are no accounts, and nothing is sent to a server. Data can be downloaded as a file and loaded back.
- **The Dugout:** a photo and story wall. It shows sample tiles for now. Real posts are added to the `POSTS` list in the page, and the submit button turns on when `DUGOUT.formUrl` is set.
- **For coaches:** conversation starters and ways to describe pro softball accurately, for people who already coach.

## Version history

| Version | Date | What changed |
|---|---|---|
| V1 | Nov 4, 2026 | First prototype with a quiz, pathways, real numbers, pro spotlights, mentors, guide and coach toolkit. |
| V2 | Nov 17, 2026 | Changes after round 1 feedback (4 responses: 3 players and 1 coach). Expanded recruiting guide, mentor matching explainer, extra sourced statistic, coach toolkit tip, fixed non-working footer buttons and tab display. |
| V3 | Nov 18, 2026 | Changes from the project owner's own review of V2, not from tester feedback. Grouped dropdown menus, pro spotlights redesigned around questions every player answers, guide lists made read-only, and a new My plan section that saves progress, email drafts and a school tracker in the browser. |
| V4 | Nov 18, 2026 | Changes from two peer feedback conversations (rounds 2 and 3). Added The Dugout, Find the spark, Find a travel team, Resources and School notes. Spotlights now include college players and coaches. Get recruited was explained more clearly, and the College pathway now asks whether you would want to attend the school without softball. |

Round 1 feedback that was not acted on: a request for a form where players leave contact details to schedule time with mentors. It was left out because the prototype has no way to send the information, and collecting contact details from minors needs a safeguarding plan first.

## About accounts and saved data

V3 and V4 have no login. My plan keeps data in the visitor's browser on one device, which means nothing is collected from players, including minors. Real accounts that sync across devices would need a hosted back end, a privacy policy, and consent from a parent or guardian for players under 13. That is a possible later step and is not built.

## Repository layout

```
index.html        Version picker (links to every version)
v1/index.html     Version 1, kept unchanged
v2/index.html     Version 2, kept unchanged
v3/index.html     Version 3, kept unchanged
v4/index.html     Version 4, the latest
README.md         This file
```

Each version is one self-contained HTML file with no build step.

## Adding a new version

1. Create a new folder, for example `v5`, with the new `index.html` inside it. Leave older folders unchanged.
2. Add a card for it to the root `index.html` and point the "latest" button at the new folder.
3. Add a row to the version history above.

## Notes

- Feedback not acted on in V4: real accounts and a login, and a list of travel teams by state. A static site cannot host accounts, and team lists cannot be verified, so Find a travel team opens a web search instead. A statistic about players who chose a school only for softball was suggested, but no source was found, so it is left out.
- Photo submissions are not open until a submission form is connected and a safeguarding plan is in place.
- The player profiles and mentors are placeholders. This project is not affiliated with or endorsed by the AUSL or TOGETHXR.
- AUSL facts come from public sources, including [theausl.com](https://theausl.com), and the league may have changed details since.
- The NCAA statistic comes from the [NCAA](https://www.ncaa.org/sports/2024/4/15/softball-probability-of-competing-beyond-high-school.aspx).
- Survey figures are self-reported and the samples are small.
- The prototype was built with help from Claude, an AI assistant from Anthropic.
