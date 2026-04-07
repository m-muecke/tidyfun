## R CMD check results

0 errors | 0 warnings | 1 note

The NOTE is the standard "New submission" note plus:

- "geoms" flagged as possibly misspelled (established ggplot2 term, see below)

## Test environments

* local: Linux Mint 22.1, R 4.5.2
* GitHub Actions: ubuntu-latest (R-devel, release), macOS-latest (release),
  windows-latest (release)

## Resubmission

Changes from previous submission (0.1.1, 2026-04-01):

- Fixed URL for Kneip & Gasser (1992) reference: the DOI resolver
  (`doi.org/10.1214/aos/1176348794`) returns 404 and the Project Euclid
  HTML page is behind a bot wall, so we link directly to the PDF on
  Project Euclid.
- Reduced vignette figure dimensions and excluded visual test snapshots
  to bring tarball size under 5 MB.

### URL notes

- `https://doi.org/10.1111/1467-9868.00129` (Wiley/JRSS-B): returns
  403 to automated requests but resolves correctly in browsers. This is
  Wiley's standard bot-blocking behavior.

## Reverse dependencies

No reverse dependencies (first submission).

## DESCRIPTION spelling

"geoms" is an established term in the ggplot2 ecosystem (short for
"geometric objects") and is used intentionally.
