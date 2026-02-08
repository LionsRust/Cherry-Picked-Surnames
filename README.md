# Cherry-Picked Surnames

Simple web app to browse and filter surnames (allowed endings: -o, -e, -a, -en, -on; excludes -eva and other suffixes). Data is ranked by popularity from US Census and Russian surname lists.

## Run locally

Serve the folder over HTTP (required for loading the JSON):

```bash
python3 -m http.server 8000
```

Then open **http://localhost:8000** and click **index.html**.

## Filters

- **Search** — filter by substring
- **Russian** — All / Russian only / Not Russian (Russian = from Russian surname list; Russian-only view is sorted by Russian popularity)
