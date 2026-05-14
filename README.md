[README.md](https://github.com/user-attachments/files/27752886/README.md)
# RealTimeWealth

RealTimeWealth is a lightweight single-file web app that presents the estimated net worth of well-known public figures in a clean, searchable dashboard.

It is built with plain HTML, CSS, and JavaScript, with no framework and no build step required. The current version includes 111 curated profiles across six categories: entrepreneurs, artists, football figures, celebrities, athletes, and actors.

## Overview

This project focuses on a polished browsing experience for wealth-related profile data. Users can filter by category, search by name or industry, scan summary stats, and open a modal to view a short biography, wealth breakdown, quick facts, and a notable quote for each person.

## Features

- Single-file front-end app with no dependencies to install
- 111 curated profiles across 6 categories
- Category tabs for fast browsing
- Search by name or industry tag
- Summary stats for total tracked wealth, people count, richest result, and average
- Detailed modal view for each profile
- Responsive layout for desktop and mobile
- Automatic Wikipedia thumbnail fetching with initials fallback
- Clean minimalist UI with subtle animation and live clock

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts (`Geist` and `Geist Mono`)
- Wikipedia REST API for profile thumbnails

## Getting Started

No package installation is required.

1. Clone this repository.
2. Start a local static server from the project root:

```bash
python3 -m http.server 8000
```

3. Open `http://localhost:8000` in your browser.

You can also deploy the project directly to static hosting platforms such as GitHub Pages, Vercel, or Netlify.

## Project Structure

```text
.
├── index.html   # Main app UI, styles, logic, and embedded dataset
└── README.md
```

## Data Notes

- Wealth figures are embedded directly in the front end as a curated static dataset.
- Each profile includes a visible source label such as Forbes, Bloomberg, or Celebrity Net Worth.
- Profile images are fetched at runtime from Wikipedia when available.
- Although the interface feels live, the wealth data itself is not connected to a real-time market feed.

## Use Cases

- Front-end portfolio project
- Static dashboard demo
- UI inspiration for searchable profile directories
- Lightweight prototype for a data-driven celebrity or finance-themed experience

## Limitations

- Net worth values are estimates and may change frequently.
- The dataset is manually maintained inside `index.html`.
- Image availability depends on Wikipedia responses.
- There is currently no backend, database, or automated data refresh pipeline.

## Possible Improvements

- Move the dataset into JSON or an API
- Add sorting and more advanced filters
- Track historical net worth changes over time
- Add charts or visual comparisons
- Add automated data validation
- Support multiple currencies and localization

## Disclaimer

This project is intended for educational, experimental, and presentation purposes only. Net worth figures are approximate and may vary across sources.
