## R CMD check results

0 errors | 0 warnings | 1 note

The NOTE is the standard "New submission" note plus:

- "geoms" flagged as possibly misspelled (see below)
- Tarball size ~9.2 MB (vignettes with figures account for most of the size)

## Test environments

* local: Linux Mint 22.1, R 4.5.2
* GitHub Actions: ubuntu-latest (R-devel, release), macOS-latest (release),
  windows-latest (release)

## Resubmission

Changes from previous submission (0.1.0):

- Uncommented example code in `tf_gather.Rd` (moved from comments to
  proper examples with tidyselect demonstrations).
- Saved and restored `par()` in `x06_Registration` vignette.
- Fixed broken URLs in vignettes (replaced projecteuclid.org 404s and
  PMC 403 with DOI links).
- Updated `NEWS.md` version to match `DESCRIPTION`.

## Reverse dependencies

No reverse dependencies (first submission).

## DESCRIPTION spelling

"geoms" is an established term in the ggplot2 ecosystem (short for
"geometric objects") and is used intentionally.
