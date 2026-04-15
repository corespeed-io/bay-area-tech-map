# Bay Area Tech Map

An interactive map of 200+ tech companies in the San Francisco Bay Area, built with Leaflet.js and Stamen Watercolor tiles.

**[View Live Map](https://your-username.github.io/bay-area-tech-map/)** <!-- Replace with actual URL after deploying to GitHub Pages -->

![Bay Area Tech Map Screenshot](screenshot.png)

> *Translations: [中文](README_zh.md) | [日本語](README_ja.md)*

## Features

- **208 verified companies** — from YC startups to FAANG, all with real physical addresses
- **Watercolor map style** — beautiful hand-drawn aesthetic using Stamen tiles
- **Company logos** — well-known companies display their logo as the map marker
- **Search & filter** — find companies by name, description, or category
- **16 categories** — AI, Fintech, SaaS, Consumer, Dev Tools, Hardware, and more
- **Marker clustering** — clean view even in dense areas like SoMa

## Tech Stack

- [Leaflet.js](https://leafletjs.com/) — interactive map
- [Leaflet.markercluster](https://github.com/Leaflet/Leaflet.markercluster) — marker clustering
- [Stamen Watercolor](http://maps.stamen.com/watercolor/) — map tiles
- Vanilla HTML/CSS/JS — no build tools, no framework
- Company data stored in `companies.json`

## Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/bay-area-tech-map.git
cd bay-area-tech-map

# Serve locally (any static server works)
npx serve .
# or
python3 -m http.server 3000
```

Then open [http://localhost:3000](http://localhost:3000).

## Data Format

Company data lives in [`companies.json`](companies.json). Each entry:

```json
{
  "name": "Stripe",
  "category": "fintech",
  "description": "Payment infrastructure for the internet",
  "address": "354 Oyster Point Blvd, South San Francisco, CA 94080",
  "lat": 37.6515,
  "lng": -122.4002,
  "website": "https://stripe.com/",
  "logo": "https://logo.clearbit.com/stripe.com"
}
```

## Contributing

Want to add a company? See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

**Two ways to contribute:**
1. Edit `companies.json` and submit a PR
2. [Open an issue](../../issues/new?template=add-company.yml) with the company info

All addresses are verified — we don't accept virtual mailboxes or registered agent addresses.

## Categories

| Color | Category | Examples |
|-------|----------|----------|
| ![#c62828](https://via.placeholder.com/12/c62828/c62828.png) | Consumer | Airbnb, Reddit, Discord |
| ![#1565c0](https://via.placeholder.com/12/1565c0/1565c0.png) | Fintech | Stripe, Plaid, Robinhood |
| ![#6a1b9a](https://via.placeholder.com/12/6a1b9a/6a1b9a.png) | AI | OpenAI, Anthropic, Scale AI |
| ![#2e7d32](https://via.placeholder.com/12/2e7d32/2e7d32.png) | SaaS | Salesforce, Notion, Slack |
| ![#e65100](https://via.placeholder.com/12/e65100/e65100.png) | Dev Tools | GitHub, GitLab, Docker |
| ![#00695c](https://via.placeholder.com/12/00695c/00695c.png) | Logistics | Uber, DoorDash, Instacart |
| ![#455a64](https://via.placeholder.com/12/455a64/455a64.png) | Hardware | Apple, NVIDIA, Intel |
| ![#37474f](https://via.placeholder.com/12/37474f/37474f.png) | Security | Cloudflare, Okta, Palo Alto Networks |
| ![#1b5e20](https://via.placeholder.com/12/1b5e20/1b5e20.png) | Health | Genentech, 23andMe |
| ![#283593](https://via.placeholder.com/12/283593/283593.png) | Data | Databricks, Snowflake, Splunk |

## License

[MIT](LICENSE)
