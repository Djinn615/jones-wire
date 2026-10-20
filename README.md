# The Jones County Wire

AI-assisted, human-approved local news for Jones County, Texas. Software drafts
every story from the public record (court agendas, meeting minutes, election
filings, weather alerts, official posts). A human reads every word, checks it
against the source, and approves each story before it publishes. Nothing
publishes without that approval.

- Site: https://djinn615.github.io/jones-wire (GitHub Pages, served from `docs/` on `main`)
- Generator: `build_site.py` (stdlib-only Python; reads `articles/`, renders to `docs/`)
- Build: `python3 build_site.py` or, when pushing binary images through an API
  that cannot store them, `WIRE_INLINE_IMAGES=1 python3 build_site.py`
- Canonical workspace: `~/workspace/jones-wire/` on the operator machine
  (articles, drafts, assets, pipeline scripts, ARTICLE-QA.md, brand-guide.md,
  SOURCE-MAP.md)
- Desks (sections, not people): Courts, City, Schools, Weather, Development,
  Elections, Water, Sports, Community
