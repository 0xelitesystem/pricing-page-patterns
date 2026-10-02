# pricing-page-patterns

Ten pricing page layouts with notes on when each one fits and what to watch out for. Browse rendered examples or copy the HTML.

**Live demo:** https://0xelitesystem.github.io/pricing-page-patterns/

## What's in here

Ten patterns:

1. Single tier
2. Two tier (free + paid)
3. Three tier with featured badge
4. Annual/monthly toggle
5. Per-seat with quantity input
6. Feature comparison table
7. Tiered + usage-based add-ons
8. Pay what you want
9. Enterprise: contact-only
10. Free + paid (no tiers)

Each one is rendered live, with a note on when it fits and what mistake to watch for. Click "View HTML" to see the markup.

## Use

1. Open the page and scroll through the ten rendered patterns.
2. Read the note under each one on when it fits and what to avoid.
3. Click "View HTML" on a pattern to show its markup, then copy it into your project.
4. Restyle it through the `--bg`, `--ink` and `--accent` CSS variables.

Open `index.html` in any browser, or visit the live demo at `https://0xelitesystem.github.io/pricing-page-patterns/` once Pages is enabled.

The HTML is unstyled enough to drop into any project. The classes use `--bg`, `--ink`, `--accent` etc. CSS variables so you can re-skin without rewriting the structure.

## Why this exists

Most "pricing page inspiration" galleries are screenshots of pretty pages. They show what but not why. This catalog tries to:

- Name what each layout is for (when it fits)
- Name the failure mode for each (what to avoid)
- Give you the markup to start from

It is one HTML file with no tracking and no dependencies, MIT licensed.

## Privacy

Everything runs in your browser. The page makes no network requests and sends nothing anywhere. The only thing it stores is your light or dark theme choice, saved in localStorage under the key `theme`.

## Run locally

```
git clone https://github.com/0xelitesystem/pricing-page-patterns
cd pricing-page-patterns
```

Open `index.html` in a browser, or serve the folder with `python -m http.server` and visit http://localhost:8000.

## Build

No build step. It is a single `index.html` file.

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## License

MIT for the HTML and the catalog text. Use it however you want.

## Related

- [landing-page-anti-patterns](https://github.com/0xelitesystem/landing-page-anti-patterns), 50 things that make pages worse
- [single-file-saas-template](https://github.com/0xelitesystem/single-file-saas-template), ship a SaaS in one HTML file
- [legal-pages-starter](https://github.com/0xelitesystem/legal-pages-starter), Terms / Privacy / Disclaimer fill-in-the-blanks
