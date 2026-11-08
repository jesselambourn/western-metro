# Western Metro Maps

Doorknock maps for all 11 Western Metropolitan Region districts, served with GitHub Pages.

- `index.html`: home page
- `progress.html`: Region Progress (share knocked, share answered, volunteer-adjusted support)
- `projections.html`: Map Projections (expected support for unknocked homes, ranked within each district or across the region)
- `timeline.html`: Campaign Timeline (doors knocked each week and in total, with projections)
- `voting-centres.html`: Voting Centres priority map (EVCs and booths ranked by votes x support squared; built separately from analysis/priority_site/gh.py, not by this script)

Every map shows the 2026 early voting centres and election-day voting centres. Each page is self-contained and uses Leaflet with OpenStreetMap tiles. The pages hold per-map totals only, with no names or addresses.
