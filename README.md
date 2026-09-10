# The Pouch and the Bypass

[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-Active-teal.svg)](https://minerclass.github.io/ietl-pouch-and-bypass/)
[![Presented by](https://img.shields.io/badge/Presented_by-Micah_J._Miner-gold.svg)](https://micahminer.com)

**The Pouch and the Bypass** is a five-minute IETL presentation examining phone restrictions as one part of a broader screen ecology. It connects intentional device access, K–8 charging infrastructure, parent participation, and technology leadership.

🔗 **Deck:** [minerclass.github.io/ietl-pouch-and-bypass](https://minerclass.github.io/ietl-pouch-and-bypass/)
🎤 **Venue:** Illinois Educational Technology Leaders (IETL) Fall Workshop — five-minute overview

---

## The premise

The pouch is the restriction. The bypass is the same habit moving to the next available screen, often one the school issued. Removing one screen does not redesign the ecology.

The deck moves through five slides: the framing, the shift from screen time to screen ecology, device access designed by instructional purpose across K–5 and middle school, parents as policy partners, and the leadership challenge that follows from all four.

---

## Contents

| Path | What it is |
| :--- | :--- |
| [`/`](https://minerclass.github.io/ietl-pouch-and-bypass/) | The five-slide deck. Self-contained: no build step, no dependencies, no external assets |
| `.github/workflows/pages.yml` | Artifact-based Pages deploy, matching the rest of the ecosystem |

---

## Presenting

Open the Pages URL. The intended experience is a web slide deck, not a PowerPoint download.

| Control | Action |
| :--- | :--- |
| Right arrow, Page Down, Space | Next slide |
| Left arrow, Page Up | Previous slide |
| `N`, or the Notes button | Toggle speaker notes |
| `P` | Print / export to PDF |
| Escape | Close the notes panel |
| Swipe left or right | Change slides on a touch device |

Deep links work: `#slide-3` opens slide 3 directly, and browser back and forward stay in sync with the deck.

**Printing** produces a landscape handout with all five slides and the speaker notes beneath each one. The dark cards keep their backgrounds via `print-color-adjust`, so print from a browser rather than exporting through a converter.

---

## Editing

The CSS and JavaScript are deliberately unminified so the file stays reviewable in the repo. Do not re-minify, and do not run a formatter that would strip the print-color-adjust declarations, the `@page` rule, the keyboard-handler guards on `button` and `.notes`, or the `inert` and `aria-hidden` handling on inactive slides and the closed notes panel. Each of those exists to fix a defect that a previous revision shipped.

---

## Privacy note

This is a public presentation artifact. It contains no student data, no staff data, no network configuration, and no credentials. Do not add private research notes, participant material, or internal district documents to this repository.
