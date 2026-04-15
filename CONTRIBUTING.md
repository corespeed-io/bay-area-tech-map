# Contributing to Bay Area Tech Map

Want to add a company to the map? Here's how.

## Option 1: Edit `companies.json` (for developers)

1. Fork this repository
2. Add your company to `companies.json`
3. Submit a Pull Request

### Data format

Each company entry looks like this:

```json
{
  "name": "Company Name",
  "category": "ai",
  "description": "One-line description of the company",
  "address": "123 Main St, San Francisco, CA 94105",
  "lat": 37.7900,
  "lng": -122.4000,
  "website": "https://example.com/",
  "logo": "https://logo.clearbit.com/example.com"
}
```

### Fields

| Field | Required | Description |
|-------|----------|-------------|
| `name` | Yes | Company name |
| `category` | Yes | One of: `fintech`, `saas`, `consumer`, `ai`, `dev-tools`, `logistics`, `hr`, `design`, `data`, `auto`, `health`, `security`, `commerce`, `education`, `real-estate`, `hardware` |
| `description` | Yes | Brief description (under 80 chars) |
| `address` | Yes | Real, verified physical address in the Bay Area |
| `lat` | Yes | Latitude (roughly 36.8 - 38.2) |
| `lng` | Yes | Longitude (roughly -123.0 - -121.0) |
| `website` | No | Company website URL |
| `logo` | No | Logo URL (we recommend `https://logo.clearbit.com/yourdomain.com`) |

### How to get lat/lng

1. Go to [Google Maps](https://maps.google.com)
2. Search the address
3. Right-click on the pin → the coordinates will be shown (lat, lng)

## Option 2: Open an Issue (for non-developers)

If you're not comfortable editing JSON, just [open an issue](../../issues/new?template=add-company.yml) and fill out the form. We'll add the company for you.

## Rules

- **Addresses must be real.** We verify all submissions. Virtual mailboxes, registered agent addresses, and PO boxes will be rejected.
- **Bay Area only.** The company must have a physical office in the San Francisco Bay Area.
- **No duplicates.** Please search the existing map before submitting.
- **Keep descriptions factual.** No marketing language.
