# Political Economy Research — Knowledge Base

A real-time political economy research wiki compiled from raw sources (articles, transcripts, reports) into structured Markdown notes using an LLM-assisted workflow. The vault is maintained in [Obsidian](https://obsidian.md), synced via Google Drive, and published here for reference.

---

## How It Works

```
raw/          ← source material: clipped articles, transcripts, reports
  ↓
wiki/         ← LLM-compiled knowledge base (this folder)
  ↓
output/       ← query results and generated reports
```

Raw files are compiled into wiki articles with key takeaways, cross-links between related concepts, and topic-level index files. Each article includes a **Key Takeaways** section and uses `[[wiki links]]` for internal cross-references (rendered as standard links on GitHub).

---

## Topics

| Topic | Description |
|-------|-------------|
| [Middle East Conflict 2026](middle-east-conflict-2026/_index.md) | The war, ceasefire negotiations, and diplomatic developments (Day 42+) |
| [Hormuz Strait Crisis](hormuz-strait-crisis/_index.md) | Iran's blockade of the strait, toll system, shipping collapse |
| [Energy Markets 2026](energy-markets-2026/_index.md) | Oil prices, LNG crisis, global supply disruption |
| [Asian Economic Crisis](asian-economic-crisis/_index.md) | Energy rationing, food/fertiliser crisis, country-by-country impacts across Asia |
| [US Markets and Economy](us-markets-and-economy/_index.md) | Equities, macro data, inflation, Fed expectations |
| [AI Industry](ai-industry/_index.md) | Anthropic Mitos release, Meta/OpenAI infrastructure investments, cybersecurity |
| [European Economy](european-economy/_index.md) | Stagflation risk, fiscal policy, Italy, Hungary elections (Orbán defeated) |
| [Global Finance and Crypto](global-finance-and-crypto/_index.md) | Underground banking (Hawala, Fei Qian), cryptocurrency critique, cyber-libertarianism |
| [AI Geopolitics and Risks](ai-geopolitics-and-risks/_index.md) | Transformative potential of powerful AI, civilisational risks, export controls, AI-enabled authoritarianism |

---

## Structure

Each topic folder contains:
- `_index.md` — lists all articles in that topic with one-line descriptions
- Individual article files (e.g., `oil-price-dynamics.md`) — concise bullet-point notes with a **Key Takeaways** section and cross-links to related articles

---

## Tech Stack

- **Obsidian** — vault editor and graph view for navigating cross-links
- **Plain Markdown** — all content is `.md`, no proprietary formats
- **Google Drive** — sync across devices
- **Claude (Anthropic)** — LLM used to compile raw sources into structured wiki articles
