Resource Planning & Tracking Model

A self-initiated Excel model for planning and tracking resources across a
fictional 12-month, 5-team project (17 work packages).

**All data is fictional.** Work packages are loosely themed on public Future
Circular Collider study areas for illustration only. This is not CERN data and
is not affiliated with CERN.

## What it does
- Spreads each task's effort across its months by team (SUMIFS)
- Calculates utilisation vs. team capacity and highlights over-allocation
  (red > 100%, amber 85-100%, green < 85%)
- Runs six data-quality checks (missing owner, End before Start, duplicate IDs,
  months out of range, unknown team, missing effort)
- Summarises peak utilisation by team in a chart

## Tabs
README | Summary | Capacity | Tasks | Allocation | Checks

## Tools
Excel / Google Sheets: SUMIFS, COUNTIFS, SUMPRODUCT, INDEX/MATCH,
conditional formatting, data validation, charts
