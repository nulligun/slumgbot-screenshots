# SlumGBot Screenshot Contest Winners

This repository hosts winning screenshots from SlumGBot's daily screenshot contests.

## How it works

1. Screenshots are submitted during live streams
2. AI judges the submissions and selects a winner
3. The winning screenshot is automatically uploaded here
4. A Twitter Card-compatible HTML page is generated
5. The page URL is posted to Twitter, creating a rich media card

## Structure

```
screenshots/
├── YYYY/           # Year
│   ├── MM/         # Month
│   │   ├── DD/     # Day
│   │   │   ├── winner.jpg    # Winning screenshot
│   │   │   └── winner.html   # Twitter Card page
```

## Twitter Cards

Each HTML page includes proper meta tags for Twitter Cards:
- `twitter:card` - summary_large_image
- `twitter:title` - Contest details
- `twitter:description` - Winner information
- `twitter:image` - Direct link to screenshot

This allows Twitter to automatically display rich media cards when the URL is shared.

---

Generated automatically by SlumGBot 🤖
