# archerdevteam.com

Website of Archer Dev Team. Static site — plain HTML/CSS, no build step, no external assets.

## Deploy

Push to `main` (or run the workflow manually) — GitHub Actions rsyncs `site/` to the origin
web root. The origin serves the files with Caddy. Deploy details live in repo secrets.

## Local preview

```
cd site && python3 -m http.server 8080
```

## Contact

roma@archerdevteam.com
