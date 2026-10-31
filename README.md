# US federal open bids by state

Daily count of open federal contract opportunities on SAM.gov for each US state and territory, with small-business set-asides, bids closing within 7 days, and contract awards over the last 12 months. One row per state per day, history from 2026-10-31.

**File:** [`open_bids_by_state.csv`](open_bids_by_state.csv), updated daily.

| column | meaning |
|---|---|
| date | day of the count (UTC) |
| state | two-letter place-of-performance state |
| open | open opportunities with this place of performance |
| set_aside | of those, set aside for small business |
| closing_7_days | of those, closing within 7 days |
| awards_12_months | contract awards in the last 12 months |
| award_dollars_12_months | their total value, US dollars |

Source: SAM.gov public opportunities data (US government work, public domain). This compilation is released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).

Browse the open bids for each state at [pushbuild.com/bids](https://pushbuild.com/bids/). The same data is available as an API at [pushbuild.com/apis](https://pushbuild.com/apis/).
