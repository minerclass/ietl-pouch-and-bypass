# The Pouch and the Bypass

[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-Active-teal.svg)](https://minerclass.github.io/ietl-pouch-and-bypass/)
[![Presented by](https://img.shields.io/badge/Presented_by-Micah_J._Miner-gold.svg)](https://micahminer.com)

**The Pouch and the Bypass** is a five-minute IETL presentation examining phone restrictions as one part of a broader screen ecology. It connects intentional device access, K–8 charging infrastructure, parent participation, and technology leadership.

🔗 **Deck:** [minerclass.github.io/ietl-pouch-and-bypass](https://minerclass.github.io/ietl-pouch-and-bypass/)
🎤 **Venue:** Illinois Educational Technology Leaders (IETL) Fall Workshop — five-minute overview

---

## The premise

The pouch is the restriction. The bypass is the same habit moving to the next available screen, often one the school issued. Removing one screen does not redesign the ecology.

Illinois Public Act 104-0657 makes that literal. It requires every district to adopt a bell-to-bell wireless communication device policy before the 2027–28 school year, and its definition excludes a device issued by the school or a teacher for educational purposes. The statute regulates one channel of the screen ecology and exempts the rest by definition.

The deck moves through seven slides: the framing, the shift from screen time to screen ecology, the three implementation models under consideration, what the policy reaches and what it exempts, the recording-glasses deliberation that broke the device frame, parents as policy partners, and the leadership challenge that follows.

The glasses slide is the argument's second proof. Weeks into drafting a phone policy, a staff member observed a parent at dismissal apparently wearing recording-capable glasses. The wearer was a visitor rather than a student, the governing law was the Illinois Eavesdropping Act rather than the device statute, and no remedy could ban a category of eyewear without banning accessibility with it. The interim position regulates conduct instead of hardware, which is the opposite posture from the phone policy written three weeks earlier.

## Sources on the slides

| Claim | Source |
| :--- | :--- |
| Bell-to-bell policy required before 2027–28 | Public Act 104-0657 (SB 2427), signed July 28, 2026 |
| "Wireless communication device" excludes school-issued devices | Public Act 104-0657, definition |
| Teachers estimate 1 in 3 students on laptops for nonacademic purposes | ISBE, *Model Cell Phone Policy*, reporting the Phones in Focus study with Harvard's Center for Education Policy Research |
| Three implementation models on slide 3 | Beach Park District 3 draft Policy 7:190-AP1, options under board consideration |
| Town hall design on slide 6 | Beach Park District 3 town hall action plan |
| Recording-glasses position on slide 5 | District leadership brief, August 2026, anchored to 720 ILCS 5/14-1 and 14-2, FERPA, ISSRA, CoSN, ISTE+ASCD, and the NIST Privacy Framework |
| Posted-notice strip on slide 5 | Beach Park District 3 recommended signage, layered by placement: brief at the roadway, complete at the door, compact inside |
| "A car line is not a classroom" | 720 ILCS 5/14-2 turns on a *private conversation* where privacy is reasonably expected; outdoor arrival and dismissal areas carry a lower expectation than classrooms |

ISBE's model policy toolkit is informational, not legal advice, and the recording-glasses position is interim guidance rather than adopted policy. The three implementation models are options under board consideration, not decisions. Verify current statutory language with district counsel before adopting policy.

---

## Contents

| Path | What it is |
| :--- | :--- |
| [`/`](https://minerclass.github.io/ietl-pouch-and-bypass/) | The seven-slide deck. Self-contained: no build step, no dependencies, no external assets |
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

**Presenting on a projector.** The slide box is `min(680px, 100vh - 7rem)`, so a 1280x720 display leaves it only 608px tall. A height-based media query below 860px scales type, padding, and card sizing so the dense slides fit rather than scroll. Verified clean at 1280x720, 1366x768, 1440x900, 1920x1080, and 1024x640. Below roughly 620px of viewport height two slides scroll inside their own box, which is the intended `overflow:auto` fallback.

**Printing** produces a landscape handout with all seven slides and the speaker notes beneath each one. The dark cards keep their backgrounds via `print-color-adjust`, so print from a browser rather than exporting through a converter.

---

## Editing

The CSS and JavaScript are deliberately unminified so the file stays reviewable in the repo. Do not re-minify, and do not run a formatter that would strip the print-color-adjust declarations, the `@page` rule, the keyboard-handler guards on `button` and `.notes`, or the `inert` and `aria-hidden` handling on inactive slides and the closed notes panel. Each of those exists to fix a defect that a previous revision shipped.

---

## Privacy note

This is a public presentation artifact. It contains no student data, no staff data, no network configuration, and no credentials. Do not add private research notes, participant material, or internal district documents to this repository.
