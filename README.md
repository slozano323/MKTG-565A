# DDD Operational Locations Dashboard

This dashboard loads Diners, Drive-Ins and Dives city pages from
`dinersdriveinsdiveslocations.com` and organizes currently listed restaurants by city.

## Run locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Notes

- The app fetches content through `https://r.jina.ai/http://...` so browser requests can read source pages.
- "Operational" is interpreted as restaurants currently listed on city pages, excluding entries that contain `closed`.
