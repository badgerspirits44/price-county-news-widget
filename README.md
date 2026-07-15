# Free Price County News Widget

A free, embeddable news widget that displays the latest local news headlines for Price County, Wisconsin on any website. No signup, no API key, no maintenance required.

## What It Does

The widget pulls fresh headlines from [Price County Fun](https://pricecounty.fun) — a local news and information site covering Price County, WI. Stories auto-update every 2 hours, so your visitors always see current local news without you lifting a finger.

## Quick Start

Add this one line of JavaScript to any page:

```html
<script src="https://pricecounty.fun/wp-content/plugins/pc-local-news/embed.js"
        data-pcln-keyword="park falls"
        data-pcln-limit="5"
        data-pcln-title="Latest Park Falls News"></script>
```

That's it. The widget renders in place, styled to match your site.

## Configuration Options

| Parameter | Default | Description |
|-----------|---------|-------------|
| `data-pcln-keyword` | `price county` | Filter news by keyword (e.g. "park falls", "phillips", "county board") |
| `data-pcln-limit` | `5` | Number of headlines to display (1–10) |
| `data-pcln-title` | `Latest Price County News` | Widget heading text |
| `data-pcln-theme` | `light` | Color theme: `light` or `dark` |

## Example

```html
<!-- Park Falls news, 5 headlines, dark theme -->
<script src="https://pricecounty.fun/wp-content/plugins/pc-local-news/embed.js"
        data-pcln-keyword="park falls"
        data-pcln-limit="5"
        data-pcln-title="Latest Park Falls News"
        data-pcln-theme="dark"></script>
```

## Why Use This Widget?

- **Local content for local audiences** — Real headlines from a real local news source, not aggregated clickbait
- **Zero maintenance** — Auto-updates on its own, every 2 hours
- **No tracking, no ads** — The widget is completely ad-free and doesn't track your visitors
- **Customizable** — Filter by keyword to show only the news relevant to your audience
- **Responsive** — Works on mobile, tablet, and desktop
- **Free** — No cost, no signup, no API key required

## Data Source

All news content is sourced from [Price County Fun](https://pricecounty.fun), an independent local news site covering:

- County board meetings and government
- Municipal records and public notices
- Outdoor recreation and events
- Investigative reporting on local issues
- Business and economic development
- Community events across Price County

## REST API

If you prefer to build your own integration, there's also a REST API:

```
GET https://pricecounty.fun/wp-json/pc-news/v1/news?keyword=park+falls&limit=5
```

Returns JSON with `title`, `link`, `date`, and `excerpt` for each article.

## License

The widget code is free to use on any website. News headlines are sourced from Price County Fun and remain the property of their respective authors.

## Links

- **Widget page**: [pricecounty.fun/free-news-widget/](https://pricecounty.fun/free-news-widget/)
- **Full site**: [pricecounty.fun](https://pricecounty.fun)
- **Live demo**: [pricecounty.fun/free-news-widget/](https://pricecounty.fun/free-news-widget/) (scroll down for light + dark previews)

---

Made with care in the Northwoods 🦡
