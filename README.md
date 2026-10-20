# ESP32TV — Topic Roadmap

The public topic backlog of ESP32TV, the only ESP32-only media platform. Every issue in this repo is a requested show topic. Browse it to see what's planned — open an issue to suggest what we should cover next.

## How to suggest a topic

1. **Search first** — check the open and closed issues. If your topic is already there, comment on it instead of opening a duplicate.
2. **Open a topic suggestion** — blank issues are disabled, so every issue starts from the form. The title is your topic; the form asks for:
   - **The topic as the title** — one specific line, e.g. "ESP32 Bluetooth Mesh in practice", not "networking stuff"
   - **What the episode should cover** (required) — two to six concrete points. If the topic is accepted, this becomes the episode outline
   - **Where it sits in the stack** (required) — toolchain, protocols, AI and edge inference, peripherals, low power, ecosystem, or other
   - **Why it matters** (optional) — who runs into the problem, and what existing material is missing or misleading
   - **References** (optional) — links to docs, repos, or articles that support the topic. They are checked

## Topic policy

Topics are reviewed by the ESP32TV team. To be accepted, a suggestion should:

- **Be about ESP32 development** — platforms, toolchains, boards, sensors, protocols, and the ecosystem around them. Off-topic platforms (other MCUs, general tech etc) will be declined unless it relates to ESP32 development somehow.
- **Be specific enough to plan an episode around** — a clear angle beats a vague one-liner. "A guide to ESP32-C6 Matter support" is better than "something about Matter".
- **Have resolving references** (when provided) — links are checked; broken links may be edited or the topic declined.
- **Not be a duplicate** — search before submitting; duplicates are closed pointing at the original.
- **Be respectful and spam-free** — promotional or abusive submissions are closed immediately.

## What happens to your issue

| Label | Meaning |
|---|---|
| `triage` | Received, waiting for founder review |
| `approved` | Accepted — will be covered |
| `recorded` | Episode recorded |
| `published` | Episode published |
| `rejected` | Declined — the issue is closed with a comment explaining why |
| `duplicated` | Already requested — the issue links to the original |

Rejected topics are **not** a judgment of your idea — the roadmap is curated to keep the show focused. The comment on the issue explains which part of the policy the suggestion didn't meet.

## License

The content of this repository is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). You are free to share and adapt it with attribution to ESP32TV.
