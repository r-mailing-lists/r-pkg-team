# r-pkg-team

Debian R Packages Maintainers: automatic mail about uploads and bug reports

Automated mbox archive. Updated daily via GitHub Actions.

## Structure

- `raw/` - Monthly .mbox files downloaded from [https://alioth-lists.debian.net/pipermail/r-pkg-team/](https://alioth-lists.debian.net/pipermail/r-pkg-team/)
- `processed/` - Structured JSON output from rmail-parser
- `sources/` - Where present, each message's page at the source and the characters that page restores, one JSON file per period
- `attachments/` - Text Mailman scrubbed out of messages, fetched once from the source and put back by rmail-parser, one gzip-compressed JSON file per period
- `meta.json` - List statistics

## Viewer

This list is not shown on [archives.rstats.dev](https://archives.rstats.dev/): its mail is mostly automatic notices about uploads and bug reports rather than discussion. The archive here is kept up to date like any other.
