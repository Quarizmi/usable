# Usable

> A user-controlled, semi-supervised campaign builder for Google Ads. It proposes — you approve — it builds.

Usable is an open-source campaign builder by [Quarizmi](https://quarizmi.com). It asks you a few questions, comes back with data-backed suggestions, and once you approve, creates the entire Google Ads stack — campaigns, ad groups, keywords, and ads. Automation does the heavy lifting; you stay in control of every decision.

---

## How it works

1. **Ask** — Usable asks you a series of questions about your business, goals, and audience.
2. **Suggest** — it analyzes your data and returns a proposed structure, including segmentation, targeting, and keywords.
3. **Approve** — you review, adjust, and approve.
4. **Build** — Usable creates the full stack live in Google Ads.

```
 Questions ──► Suggestions ──► User review & approval ──► Build full stack in Google Ads
```

Nothing goes live without your approval. That's the "semi-supervised" part.

## Features

- **Guided setup** — a question-driven flow instead of a blank campaign editor.
- **Data-backed suggestions** — segmentation, targeting, and keyword proposals grounded in real data.
- **Full-stack creation** — campaigns, ad groups, keywords, and ads, built in one pass.
- **Human in the loop** — every proposal is reviewed and approved before anything is created.

## Data sources

| Source | What Usable uses it for |
|---|---|
| Client historical data | Suggesting segmentation and targeting |
| Google Keyword Planner | Keyword ideas and volume estimates |
| Google Search Console | Keywords already ranking organically |
| Google Analytics | Performance beyond the ad platform |
| Google Ads API | Reading account data and creating the campaign stack |

## Getting started

> **Note:** The implementation language and setup steps are still being finalized. This section will be updated.

### Prerequisites

- Google Ads API access (developer token + OAuth credentials)
- Google Search Console API access
- Google Analytics API access
- _TBD: runtime and dependencies_

### Installation

```bash
git clone https://github.com/<org>/usable.git
cd usable
# TBD: install dependencies
```

### Configuration

```bash
# TBD: environment variables / config file for API credentials
```

### Running

```bash
# TBD: run command
```

## Part of the Quarizmi suite

Usable works on its own, but it's also part of Quarizmi's end-to-end paid-search system:

- **[EKEP](https://github.com/Quarizmi/ekep)** — discovers long-tail keywords
- **[Bidbot](https://github.com/Quarizmi/bidbot)** — decides bids and which keywords to turn on or off
- **Usable** — builds full campaigns with the user in the loop _(you are here)_
- **[Magneto](https://github.com/Quarizmi/magneto)** — writes high-relevance ads for every keyword
- **[Health Checker](https://github.com/Quarizmi/healthchecker)** — grades an existing Google Ads account (standalone)

## Use it yourself, or work with us

Usable is free and open source — use it, fork it, adapt it. If you'd rather have Quarizmi build and run your campaigns, get in touch at **[quarizmi.com](https://quarizmi.com)**.

## Contributing

Contributions are welcome. Please open an issue to discuss a change before submitting a pull request.

## License

Released under the [MIT License](LICENSE). © 2026 Quarizmi AdTech.
