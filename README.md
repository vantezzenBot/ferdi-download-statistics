> Inactive: The bot running behind this repo is no longer running and will not be updating the carts.
> Please refer to https://tooomm.github.io/github-release-stats/?username=getferdi&repository=ferdi for up-to-date download stats

# Ferdi Download Statistics

This repository hosts download statistics for [Ferdi](http://getferdi.com/). The statistics will be automatically updated every hour.

## Usage

You can fetch the current statistics from <https://cdn.jsdelivr.net/gh/vantezzen/ferdi-download-statistics/statistics.csv>.

The statistics are saved in a [CSV Table](https://en.wikipedia.org/wiki/Comma-separated_values) with the first line being the column declaration.

Columns:
- version = The script saves statistics for the last 3 versions of Ferdi. The version will be a string with the semver-compatible version number.
- timestamp = UNIX Timestamp. These will be sorted ascendingly
- windows, mac, linux = Download numbers for Windows, MacOS and Linux respectively

## License

This repository is licensed under the MIT License
