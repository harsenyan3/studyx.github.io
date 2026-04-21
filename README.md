# StudyX.ai Tech Report

Simple website for a Tech Report (Group 6) - CS 3803.

## File Structure

```text
.
|-- index.html
|-- data.html
|-- recommendations.html
`-- src
    |-- assets
    |   |-- data
    |   `-- images
    |-- scripts
    `-- styles
        `-- styles.css
```

## Pages

- `index.html` - Home page with title, authors, summary, and introduction.
- `data.html` - Methodology, findings, charts, quote table, and analysis.
- `recommendations.html` - Recommendations, before/after comparisons, Figma link, and conclusion.

## Run Locally

This is a plain static HTML/CSS website. No install step is required.

### Option 1: Open Directly

Open `index.html` in your browser.

### Option 2: Use a Local Server

From the project folder, run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

To stop the server, press `Ctrl + C` in the terminal.
