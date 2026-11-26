<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Chukotka Autonomous Okrug only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-26 05:23 UTC, Chukotka Autonomous Okrug: Official Internet Portal of Legal Information (region87): 9 addresses read; 8 added, 0 changed, 0 removed; changes found; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Chukotka Autonomous Okrug: Official Internet Portal of Legal Information (region87)](http://publication.pravo.gov.ru/documents/block/region87) | `zakony-<year>/` | daily | 2026-11-26 05:23 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-26 05:22](checks/2026-11.md#ru-pravo-chukotka-20261126t052224z) | pravo-chukotka | 9 | 8 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-chukotka-law/compare/8b610a193cd4...7c8c4f674992) |
| [2026-11-25 05:21](checks/2026-11.md#ru-pravo-chukotka-20261125t052157z) | pravo-chukotka | 9 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 13:25](checks/2026-11.md#ru-pravo-chukotka-20261124t132515z) | pravo-chukotka | 12 | 1 | 0 | 0 | 0 (0) | changes found | [2](https://github.com/lexifina/russia-chukotka-law/compare/45071c8ade24...635e932e04b0) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
