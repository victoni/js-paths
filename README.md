# js-paths
Relative URL paths assembled from over 1 million javascript files from bug bounty targets. Parsed using [xnLinkFinder](https://github.com/xnl-h4ck3r/xnLinkFinder) and [gau](https://github.com/lc/gau) for unlinked js files.

The files are divided in api and sensitive info-related paths. For api:

`grep -iE api >> api.txt`

Intended to be used in URLs like `https://example.com/api/[wordlist entry]`. Of course, this can change and one can modify the entries as they please with the appropriate `sed`, `grep` etc. skills

For sensitive info:

`grep -iE "admin|panel|secret|password|dashboard|logs|chat|debug|auth|config|dev|prod|beta|test|backup" >> js-sensitive.txt`
