# Firefox Download

## Why

When downloading large files, a network problem can occur, leaving the
download stuck. `firefox-download` reads the list of downloads in progress
that Firefox keeps and hands them over to `wget` which will retry sooner and
more often.

## Usage

1. Start downloading a big file in Firefox
2. Pause it
3. (Repeat. Optional.)
4. run `firefox-download` to hand over to `wget`.

## Requirements

- Ruby
- wget
