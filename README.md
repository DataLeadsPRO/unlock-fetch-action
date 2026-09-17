# DataLeads Unlock Fetch (GitHub Action)

Fetch any page - including protected pages - through DataLeads anti-bot rendering and return the raw HTML.

Calls the DataLeads API endpoint `POST /v1/fetch` and writes the JSON response to `dataleads-result.json` plus the `result` output.

## Usage

```yaml
steps:
  - uses: DataLeadsPRO/unlock-fetch-action@v1
    with:
      url: https://example.com
      api_key: ${{ secrets.DATALEADS_API_KEY }}
```

Get a client key at [data.dataleads.pro](https://data.dataleads.pro).

## License

MIT
