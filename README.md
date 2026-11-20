# offline_html_collection

A collection of **offline-first web tools** — single-file HTML/JS apps that run entirely in your browser. No servers, no dependencies, no data sent anywhere. Everything works with a double-click, even on a plane.

## How to use

- **Browse the catalog:** open [the hosted index](https://gloryknight.github.io/offline_html_collection/html/index.html) — a searchable, filterable grid of all the tools.
- **Take it offline:** download any `.html` file and it keeps working with no internet.

## Adding a tool

1. Drop a new self-contained file into `html/` (e.g. `html/my-tool.html`).
2. Add one entry to the `TOOLS` array in `index.html`:

   ```js
   { id: 55, name: "My Tool", desc: "What it does.", category: "developer", slug: "my-tool" }
   ```

   - `slug` must match the filename (without `.html`).
   - `category` must be one of: `developer`, `visualization`, `creative`, `productivity`, `data`, `design`, `calculator`, `games`.
   - `id` just needs to be unique.

The total count and the category filter chips are computed from the array, so there's no counter to update by hand.

## License

[MIT](LICENSE)
