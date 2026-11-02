# ESP32TV — Topic Roadmap

The public topic backlog of ESP32TV, the only ESP32-only media platform. The roadmap lives in this repository's
**Discussions**: every topic we make starts there as a suggestion people can upvote, and the issue tracker holds only work
that has been committed to production.

**Suggest a topic → [Discussions › Ideas](../../discussions/categories/ideas)** · **See what is next →
[Up Next](../../discussions/categories/up-next)** · **See what shipped →
[Published](../../discussions/categories/published)**

## How to suggest a topic

1. **Search first** — look through Ideas, Up Next and Published, and through the comments on the pinned roadmap thread. If
   your topic is already there, upvote it or add your angle in its thread. A duplicate is answered once, pointing at the
   original.
2. **One topic per discussion, in Ideas.** The title is the topic, and one specific line beats a category — "ESP32
   Bluetooth Mesh in practice" clears the bar, "networking stuff" does not.
3. **Upvote what you want made.** The 👍 count on a suggestion is what we read when ordering the roadmap. `+1` comments
   do not count and are removed, so vote rather than comment.
4. **Say what the episode should cover** — two to six concrete points. If the topic is accepted, this becomes the episode
   outline.
   - For a **Learning** topic, also say **where it sits in the stack** — pick the one layer that fits best from the table
     below. It is how the topic is routed and counted, not how it is filed; the library index uses its own subject tags,
     assigned by the team, and one topic can carry several.
   - For **another show** — Insider, Tech Review, Project Review, ESP32 Youth or News — say **which show**, **what it is
     about** (the project and its repository, the partner and product, the chip or feature, the event or release, with a
     link where one exists), and **why now** — a release, a change, a gap, or for a news item what happened and when.
5. **References are welcome and are checked.** Links to docs, repos or articles support the topic; a broken link may be
   edited or the topic declined.

There is no form to fill in: GitHub Discussions has no required fields, so the five points above are the bar we hold
suggestions to rather than boxes you cannot pass. A suggestion that leaves out the outline or the layer is answered with
the question, not declined for it.

## What happens to a topic

| Where it is | What it means |
|---|---|
| **Ideas** | Suggested and open for votes. Anyone can add a new one; nothing here is scheduled |
| **Up Next** | Accepted and placed in rough order. The team moves it there after review |
| **Published** | Made and on the channel. The discussion links the episode |
| **Help & Feedback** | Everything else about the channel, the site or this roadmap |

A topic's place depends on demand (the votes), whether its references check out, whether its subject can be shown on
camera and checked against public material, and how it fits the series' shape. **A vote is not a promise.** A declined
topic is answered in its thread, naming the part of the policy it did not meet — declined is not a judgment of the idea;
the roadmap is curated to keep the show focused.

## Committed work lives in the issue tracker

The team opens an issue only when a topic is committed to production: that card is the unit of work, and it carries the
labels below. **Suggestions never enter the issue tracker**, so a topic reaching Up Next is the last stage before a card
exists — and an issue you cannot open is not missing work: the tracker holds committed work only.

| Label on a card | Meaning |
|---|---|
| `triage` | Committed, waiting for founder review of its shape |
| `approved` | Accepted — will be covered |
| `recorded` | Episode recorded |
| `published` | Episode published |
| `rejected` | Dropped after commitment — the card is closed with a comment explaining why |
| `duplicated` | Already requested — the card links to the original |

A Learning card also carries `series: learning`; for the other shows the team applies the matching `series:` label.
Subject tags are a Learning-only vocabulary — they feed the library's sidebar and its search — so a Project Review or a
News card is never given them.

## Topic policy

Topics are reviewed by the ESP32TV team. To be accepted, a suggestion should:

- **Be about ESP32 development** — platforms, toolchains, boards, sensors, protocols, and the ecosystem around them.
  Off-topic platforms (other MCUs, general tech etc) will be declined unless it relates to ESP32 development somehow.
- **Be specific enough to plan an episode around** — a clear angle beats a vague one-liner. "A guide to ESP32-C6 Matter
  support" is better than "something about Matter".
- **Have resolving references** (when provided) — links are checked; broken links may be edited or the topic declined.
- **Not be a duplicate** — search before submitting; duplicates are answered pointing at the original.
- **Be respectful and spam-free** — promotional or abusive submissions are removed immediately, and the account is
  blocked from the discussions.

Those bullets are written for Learning topic suggestions. A suggestion for another show is held to the same specificity,
references, duplication and conduct, with one difference: it does not have to teach a development skill, it has to be
about something that exists, can be shown on camera, and can be checked from public material.

### The stack layer, and how it relates to tags

The Learning suggestion asks where your topic sits in the stack. That answer is how a topic is routed and counted, not how
it is filed: the library index uses its own subject tags, assigned by the team at triage, and one topic can carry several
of them. Pick the layer that fits best — a topic that spans two is not a problem.

| Layer you pick | Tags it usually leads to |
|---|---|
| Toolchain and build | `#Toolchain` |
| Protocols and networking | `#Connectivity` |
| Firmware architecture and RTOS | `#Runtime` |
| Debugging and diagnosis | `#Debugging`, `#Diagnostics` |
| Configuration, storage and boot | `#Configuration`, `#Storage` |
| Peripherals and drivers | `#Hardware` |
| Low power, OTA and reliability | `#LowPower` |
| AI-assisted development | `#VibeCoding` |
| AI and edge inference | none yet — tagged by hand at triage |
| Security | none yet — tagged by hand at triage |
| Ecosystem and tooling around ESP32 | none yet — tagged by hand at triage |
| Other | triage's call |

Every one of the ten subject tags is reached from a layer, so a topic no longer has to arrive as `Other` to end up
under the right tag. Three layers lead to no tag yet — AI on the device, security, and the ecosystem around ESP32 —
and those are tagged by hand at triage; security has no tag in the vocabulary at all, which is a decision for the tag
list rather than for this page. Pick the layer that fits best: a topic that spans two is not a problem.

## License

The content of this repository is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). You are free to share and adapt it with attribution to ESP32TV.
