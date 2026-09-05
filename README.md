# Sean — Live Operations dashboard

Public, auto-refreshing dashboard for the Sean autonomous options agent
(Alpaca **paper** account). Served via GitHub Pages from `index.html`.

`index.html` is rebuilt from the private Sean-Trading repo's committed state by
`build_dashboard.py` and pushed here; GitHub Pages redeploys on every push.
Nothing sensitive is included — no keys, no order ids — only paper-account
analysis (regime, ranked board, positions, gate decisions).
