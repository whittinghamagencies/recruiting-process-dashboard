# Recruiting Process Dashboard

Public dashboard combining CLB Review and Final Interview Review runs for The Whittingham Agencies.
Powered by Whittingham Professional Training Services.

- `index.html`: the page (served by GitHub Pages)
- `data.json`: the numbers, rebuilt from the review logs at 7 AM, noon and 5 PM Central by a scheduled task
- `d3.min.js`: charting library (D3 v7.9.0), kept here so the page doesn't depend on outside sites

`data.json` holds only neutral flag summaries, never the review tools' raw wording or candidate details.
