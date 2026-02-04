# Doclytics Website

Marketing website for [Doclytics](https://doclytics.ai) — AI-powered healthcare document intelligence.

## Development

Install dependencies:

```
npm install
```

Start the Tailwind watcher to rebuild CSS on changes:

```
npm run dev
```

Then open `index.html` in a browser.

## Production Build

Generate minified CSS:

```
npm run build
```

The built CSS (`dist/output.css`) is committed to the repo, so the site works without a build step. Remember to run `npm run build` before committing if you've changed the HTML.
