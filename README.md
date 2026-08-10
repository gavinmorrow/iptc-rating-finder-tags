# IPTC Ratings <=> Finder Tags

This repo contains three tools: `iptc2tag`, `tag2iptc`, and `rstat`. `iptc2tag`
and `tag2iptc` convert to and from IPTC 5-star ratings (stored in EXIF metadata)
and Finder tags. `rstat` shows how many of each rating there are, along with
total and percentages.

See the comments at the top of each file for more information.

No AI was used in the creation of this project.

This repo is mirrored between
[Tangled](https://tangled.org/did:plc:36y7tf2inavnvxdms7wudfx2) and
[GitHub](https://github.com/gavinmorrow/iptc-rating-finder-tags).

## Dependencies

- [`fish`](https://fishshell.com/). Tested with v4.0.0.
- [`exiftool`](https://exiftool.org/). Tested with v13.55.
- [`tag`](https://github.com/jdberry/tag/). Tested with v0.10.0.

All of them are available via Homebrew.
