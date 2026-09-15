# Contributing to The Amazing Directory

Thanks for adding to the directory. Pull requests that follow these rules are reviewed and merged; ones that don't are asked for changes or closed.

## Listing format

```markdown
- **[Product name](https://example.com)** — One sentence on what it does and who it is for. `Tag` `Tag`
```

- Bold linked name, an em dash (`—`), one sentence ending with a period, then tags from the [tag table](README.md#tags).
- Keep the description under about 250 characters.
- Keep entries in each section in alphabetical order (case-insensitive).

## Acceptance criteria

- The product is live, publicly reachable and does what the listing says.
- One product per pull request. Pull requests adding several unrelated products are closed.
- No duplicates — search the README first.
- Link the product's own homepage over HTTPS. No shortened, tracking or affiliate links.
- Factual wording only: no superlatives, no pricing claims that are not on the product's own site, no emoji except a country flag tag.
- Categories: use an existing section when one fits. A new section needs a clear, general name (for example `## Project Management`) and a matching entry in the Contents list.
- Makers listing their own product are welcome; please mention it in the pull request description.

## Pull request checklist

- [ ] Title is `Add <Product name>`
- [ ] Exactly one entry added, in the right section, in alphabetical order
- [ ] Entry follows the format above
- [ ] Link works and has no tracking parameters

## Updating or removing a listing

Open a pull request titled `Update <Product name>` or `Remove <Product name>` with a short reason (renamed, moved domain, shut down, etc.).
