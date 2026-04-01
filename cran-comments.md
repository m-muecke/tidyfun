## R CMD check results

0 errors | 0 warnings | 1 note

The NOTE is the standard "New submission" note plus:

- "geoms" flagged as possibly misspelled (see below)
- Tarball size ~8.8 MB (vignettes with figures account for most of the size)

## Test environments

* local: Linux Mint 22.1, R 4.5.2
* local nosuggests: 0 errors, 0 warnings, 0 notes
* GitHub Actions (rhub): linux, macos-arm64, windows, nosuggests

## Resubmission

Changes from previous submission:

- Wrapped lengthy examples in `tf_gather.Rd` in `\donttest{}`.
- Uncommented example code in `tf_gather.Rd` (moved from comments to
  proper `\donttest{}` examples).
- Saved and restored `par()` in `x06_Registration` vignette.

## Reverse dependencies

No reverse dependencies (first submission).

## DESCRIPTION spelling

"geoms" is an established term in the ggplot2 ecosystem (short for
"geometric objects") and is used intentionally.
