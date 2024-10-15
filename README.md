# stepmania-chart-db V2
A database of charts generated with https://github.com/florczakraf/stepmania-chart-db-generator.
It's used in the instance of [BoogieStats](https://github.com/florczakraf/boogie-stats), a pass-through proxy
for [GrooveStats](https://groovestats.com), that I host for my personal use.

## Contributors (alphabetically)
- andr
- Lilly
- Piols
- zlew

## Changes between V1 and V2 structure
- previous `db` is now `db_v2/charts`, still a two-level hash_v3-based nested
- dropped `bpms` field, added `packs` and `diffs` fields
- added `db_v2/metadata.json` that stores info about number of tracked charts and packs as well as the last update date
- added `db_v2/packs` directory that stores `pack name.json`s which contain lists of chart hashes

## Contributions
Feel free to submit a PR that extends the databse using the generator mentioned above.

## License
CC0 1.0 Universal (Full text: https://creativecommons.org/publicdomain/zero/1.0/legalcode)
