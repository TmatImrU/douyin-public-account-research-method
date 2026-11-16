# Collection scripts and plugins

## Verified collection scripts

None are included. The workspace contained report-generation and formatting scripts, but no standalone script that was both used and verified for collecting Douyin account posts. Those report scripts contain account-specific material or are unrelated to collection and are intentionally excluded from this public repository.

## Collection method actually used

The documented workflow is browser-assisted, read-only observation of publicly visible profile grids, post pages, and topic pages. The observer records only the selected fields listed in the method document and labels unavailable or approximate metrics. This repository does not provide an automated collector.

## Plugins and runtime tools

- No third-party Douyin scraping plugin was used or is included.
- Browser inspection used the built-in computer-use interface where available. This is a host capability and cannot be redistributed as a plugin.
- The Playwright skill was consulted as workflow guidance; it was not used to collect account records for this package.

## Why no scraper is bundled

Publishing an unverified scraper would misrepresent its reliability and could expose account identifiers, session data, or unsupported access behavior. A future collector should be added only after it is implemented, tested against authorized public pages, checked against platform terms, and reviewed to ensure it does not contain credentials or personal browser state.
