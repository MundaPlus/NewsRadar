# 📡 NewsRadar

> An AI-powered news monitoring platform that automatically collects, enriches, and aggregates news from multiple sources into a single unified dashboard.

![Status](https://img.shields.io/badge/status-active-brightgreen)

## Overview

NewsRadar is a complete news intelligence tool built for organisations that need to track coverage across countries, topics, and publishers — without relying on a third-party service. It runs on your own infrastructure, connects to any news source (RSS feeds, API-based news services, or direct website scraping), and uses a local AI model to summarise every article, classify its themes, score its sentiment, and assess its relevance to your target regions.

It is designed and developed by **Munda Plus d.o.o.**, a Slovenian one-person software company.

## Key Capabilities

- **Multi-source news collection** — Pulls articles from RSS/Atom feeds, news APIs, and scraped websites. Add any source you want and NewsRadar will fetch on your schedule.
- **AI-powered content enrichment** — Every article is automatically summarised, tagged with relevant themes, scored for sentiment (from negative to positive), and ranked by country relevance — all using a local AI model running on your own machine.
- **Automatic story grouping** — When multiple sources report on the same event, NewsRadar detects the overlap and merges them into a single story with a unified AI summary. You can switch between different providers' coverage of the same story with one click.
- **Full-text search & filtering** — Search across thousands of articles by keyword, country, topic, sentiment range, date range, bookmarks, or read status. Results update instantly.
- **Real-time monitoring dashboard** — A live dashboard shows article counts per country and theme, sentiment breakdowns, source health statistics, recent articles, and an activity log of fetch cycles — all updated automatically.
- **Adaptable reading experience** — Switch between card, list, and magazine layouts. Bookmark articles, track reading progress, and navigate with keyboard shortcuts.
- **Self-hosted and private** — Everything runs on your own infrastructure. No third-party data processing, no external dependencies beyond optional news API keys and a local AI model.

## Tech Highlights

| Layer | Technology |
|-------|------------|
| Backend | Python with async API framework |
| Frontend | Modern React with reactive state management |
| Database | SQLite (zero-config, no external database server required) |
| AI | Local LLM integration (Ollama — runs entirely on your hardware) |
| Scraping | RSS/Atom parsing, news API clients, and headless browser automation |
| Deployment | Systemd service with automated install script |

## Screenshots

> *Screenshots available on request or at a demo instance.*

*(Visuals to be added — the dashboard features a dark-themed UI with stat cards, article grids, theme bar charts, sentiment breakdowns, and source health panels.)*

## Status & Availability

NewsRadar is actively developed and deployed in production. All core features — multi-source scraping, AI enrichment, story grouping, search, and the full dashboard — are implemented and functional. Planned enhancements include user authentication, multi-user support, email digests, and additional AI model backends.

## Interested?

This is a proprietary project by **Munda Plus d.o.o.**
The full codebase is available for review upon request.

📧 marko@munda.si  
🌐 [munda.si](https://www.munda.si)
