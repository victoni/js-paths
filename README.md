# js-paths
Web application endpoints assembled from over 1 million JavaScript files from bug bounty targets. File discovery using [hakrawler](https://github.com/hakluke/hakrawler) (and [gau](https://github.com/lc/gau) for unlinked js files) and parsed using [xnLinkFinder](https://github.com/xnl-h4ck3r/xnLinkFinder).

The files are divided into API and sensitive info-related paths.

For the API, it is intended to be used in URLs like `https://example.com/api/[wordlist entry]`.
