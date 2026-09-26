# Equipment Module — Interactive Preview

🔗 **Live preview:** https://carlosmertens.github.io/equipment-module-interactive/

## What this is

This repo hosts a **static, self-contained HTML page** used to preview and test UI/UX
ideas for the Equipment Management Module of the project, outside of the main
application codebase.

It is **not** a production build or a connected app — there's no backend, database, or
real API calls. All data shown (vehicles, tools, heavy equipment, statuses, etc.) is
mocked directly in the page, purely so the layout, flows, and interactions can be
clicked through and reviewed.

## Why it exists

- Share a quick, no-install link with teammates/stakeholders to gather feedback on a
  proposed screen or flow before building it for real.
- Try out different views (Dashboard, Vehicles, Small Tools, Heavy Equipment, etc.) and
  interaction patterns in isolation.
- Iterate fast: edit the HTML, push, and the public URL updates automatically via
  GitHub Pages — no deployment pipeline needed.

## How it's published

The page is served with [GitHub Pages](https://pages.github.com/) directly from the
`main` branch:

- `index.html` — the entire testing page (markup, styles, and behavior all in one file)

Any push to `main` that changes `index.html` will automatically update the live URL
above within a minute or two.

## Updating the preview

```bash
# edit index.html, then:
git add index.html
git commit -m "Update preview"
git push
```

## Status

⚠️ Work-in-progress / for review purposes only. Content and design are subject to
change and should not be treated as final.
