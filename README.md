# Shrinksearch

![Preview](preview.png)

A fast, keyboard-driven therapist directory for searching mental health providers in NYC, with better search and browsing experience than the Psychology Today website. Includes 6,341 therapists, roughly the full result set for NYC from Psychology Today as of April 2025.

View at https://zmh.github.io/shrinksearch

## Features

- **Search** - Full-text search across all therapist fields with support for exact phrase matching using quotes (e.g., `"cognitive behavioral"`)
- **Filtering** - Filter by whether therapists are accepting new clients
- **Favorites** - Star therapists to save them for later (persisted in localStorage)
- **Preview pane** - View detailed therapist information by hovering or selecting a row
- **Keyboard navigation** - Use arrow keys to navigate the list, press `s` to toggle favorites

## Usage

Open `index.html` in a browser. The app loads therapist data from `nyc_therapists.json`.

## Data Source

Therapist data was scraped from [Psychology Today](https://www.psychologytoday.com/). This project is not affiliated with, endorsed by, or connected to Psychology Today in any way. No claim is made to the copyright of the scraped data. This project is for research and educational purposes only.
