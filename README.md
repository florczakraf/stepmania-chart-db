# stepmania-chart-db
A database of charts generated with https://github.com/florczakraf/stepmania-chart-db-generator.
It's used in the instance of [BoogieStats](https://github.com/florczakraf/boogie-stats), a pass-through proxy
for [GrooveStats](https://groovestats.com), that I host for my personal use.

## Contributors (alphabetically)
- andr
- Lilly
- zlew

## Contributions
Feel free to submit a PR that extends the databse using the generator mentioned above.

## Known Issues
The library used for encoding jsons in lua has a bug related to proper encoding non-utf8 characters, so some of the files might not parse out of the box.
See [this issue](https://github.com/florczakraf/stepmania-chart-db-generator/issues/1) for more details.

## License
CC0 1.0 Universal (Full text: https://creativecommons.org/publicdomain/zero/1.0/legalcode)
