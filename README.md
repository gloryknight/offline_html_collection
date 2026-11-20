# offline_html_collection

A collection of **54 offline-first web tools** — single-file HTML/JS apps that run entirely in your browser. No servers, no dependencies, no data sent anywhere. Everything works with a double-click, even on a plane.

## How to use

- **Browse the catalog:** open [the hosted index](https://gloryknight.github.io/offline_html_collection/html/index.html) — a searchable, filterable grid of all 54 tools.
- **Take it offline:** download any `.html` file and it keeps working with no internet.

## Adding a tool

1. Drop a new self-contained file into `html/` (e.g. `html/my-tool.html`).
2. Add one entry to the `index.html`:

   ```json
   { "id": 55, "name": "My Tool", "desc": "What it does.", "category": "developer", "slug": "my-tool" }
   ```

## License

[MIT](LICENSE)
