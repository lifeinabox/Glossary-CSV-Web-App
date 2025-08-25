# Glossary CSV Web App

Glossary CSV Web App is a lightweight, offline-friendly glossary viewer. It loads entries directly from a `glossary.csv` file and presents them in a clean card layout.

## Features

- **Instant Search:** Fast, fuzzy search across terms, definitions, and tags.
- **A–Z Navigation:** Quickly jump to terms by letter.
- **Tag Filtering:** Filter glossary entries by tags.
- **Light/Dark Theme Toggle:** Switch between light and dark modes.
- **No Dependencies:** Built with vanilla HTML, CSS, and JavaScript.
- **No Build Steps:** Just open the HTML file—no compilation or bundling required.
- **Offline-Friendly:** Works entirely in your browser; no server needed.

## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/glossary-csv-web-app.git
   cd glossary-csv-web-app
   ```
2. Place your `glossary.csv` file in the same directory as `index.htm`.
3. Start a local web server (required for CSV loading):
   ```sh
   python3 -m http.server 8000
   ```
4. Open your browser and go to [http://localhost:8000/index.htm](http://localhost:8000/index.htm).
5. Edit your CSV file and refresh the page to see updates.

## CSV Format

- The CSV file should have headers: `term,definition,tags`
- Tags are optional; separate multiple tags with `|` or commas.
- Lines starting with `#` are ignored.

## Example

```csv
term,definition,tags
Array,A data structure that holds an ordered list of values.,javascript|data
API,"A defined interface for interacting with a system; often via HTTP.",web,backend
```

## License

MIT License
