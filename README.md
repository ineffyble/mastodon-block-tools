# mastodon-block-tools
An attempt to list as many different projects/tools/scripts related to Mastodon & fediverse block management as possible. 

## Active

[Official Mastodon instance-level domain blocks/allows import/export functionality](https://github.com/mastodon/mastodon/pull/20597) - as of yet unreleased

| Repo | Import/Sync from | Import via | Export from | Export to |
|---|---|---|---|---|
| **[irubnich/fediblock-importer](https://github.com/irubnich/fediblock-importer)** <br>![Language](https://img.shields.io/github/languages/top/irubnich/fediblock-importer?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/irubnich/fediblock-importer?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/irubnich/fediblock-importer?style=for-the-badge)<br><sub>CLI to import YAML-format block lists, plus a script to generate a YAML file from the joinfediverse.wiki list. </sub> |  Local YAML | Admin API | From wiki | Local YAML |
| **[netshepsky/FediBlock-Importer](https://github.com/netshepsky/FediBlock-Importer)** <br>![Language](https://img.shields.io/github/languages/top/netshepsky/FediBlock-Importer?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/netshepsky/FediBlock-Importer?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/netshepsky/FediBlock-Importer?style=for-the-badge)<br><sub>CLI to import CSV blocklists. </sub> |  Local CSV | Admin API |  |  |
| **[rapidblock-org/rapidblock](https://github.com/rapidblock-org/rapidblock)** <br>![Language](https://img.shields.io/github/languages/top/rapidblock-org/rapidblock?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/rapidblock-org/rapidblock?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/rapidblock-org/rapidblock?style=for-the-badge)<br><sub>apt package for Debian/Ubuntu that will run regularly and sync from the [RapidBlock Project](https://rapidblock.org/) list. </sub> |  RapidBlock list | SQL |  |  |
| **[freesbie/mastodon_blocklister](https://github.com/freesbie/mastodon_blocklister)** <br>![Language](https://img.shields.io/github/languages/top/freesbie/mastodon_blocklister?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/freesbie/mastodon_blocklister?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/freesbie/mastodon_blocklister?style=for-the-badge)<br><sub>Python script that pulls the list of blocks from an instance's (admin) API and syncs it with a CSV file in a git repo. </sub> |   |  | Admin API | CSV in git |
| **[goosefans/mastodon-json-blocklist](https://github.com/goosefans/mastodon-json-blocklist)** <br>![Language](https://img.shields.io/github/languages/top/goosefans/mastodon-json-blocklist?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/goosefans/mastodon-json-blocklist?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/goosefans/mastodon-json-blocklist?style=for-the-badge)<br><sub>"A very simple service that synchronizes the Mastodon federation domain block list with a remote JSON file, e.g. a file inside a remote Git repository." </sub> |  Remote JSON | Admin API |  |  |
| **[warthog9/mastodon-block-importer](https://github.com/warthog9/mastodon-block-importer)** <br>![Language](https://img.shields.io/github/languages/top/warthog9/mastodon-block-importer?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/warthog9/mastodon-block-importer?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/warthog9/mastodon-block-importer?style=for-the-badge) <br><sub>Scrapes blocks from designated instances HTML about pages, then adds them to a local instance via direct database query. </sub> |  Remote instances (HTML pages) | SQL |  |  |
| **[selfagency/mastodont](https://github.com/selfagency/mastodont)** <br>![Language](https://img.shields.io/github/languages/top/selfagency/mastodont?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/selfagency/mastodont?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/selfagency/mastodont?style=for-the-badge) <br><sub>Simple Node.js CLI that imports a list of domains to block from a text file. </sub> |  Local TXT | Admin API |  |   |
| **[thegem-city/moderation](https://github.com/thegem-city/moderation)** <br>![Language](https://img.shields.io/github/languages/top/thegem-city/moderation?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/thegem-city/moderation?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/thegem-city/moderation?style=for-the-badge) <br><sub>Block any domains from a given domain source, which can either be an HTTPS resource or a local file. </sub> |  Local or remote TXT |  |  |  |
| **[Anthchirp/mastodon-defederate](https://github.com/Anthchirp/mastodon-defederate)** <br>![Language](https://img.shields.io/github/languages/top/Anthchirp/mastodon-defederate?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/Anthchirp/mastodon-defederate?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/Anthchirp/mastodon-defederate?style=for-the-badge) <br><sub>Pulls blocklists from instances using public API (if enabled) or Markdown-formatted files. </sub> |   |  | Remote instances (public API), Markdown files | CLI output |
| **[bram-dingelstad/mastodon-tools](https://github.com/bram-dingelstad/mastodon-tools)** <br>![Language](https://img.shields.io/github/languages/top/bram-dingelstad/mastodon-tools?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/bram-dingelstad/mastodon-tools?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/bram-dingelstad/mastodon-tools?style=for-the-badge) <br><sub>Source code behind a [hosted, web-based tool](https://mastodon-tools-bram-dingelstad.vercel.app/) for "massively blocking a list of instances in the form of a CSV".  </sub> |  Local CSV via browser | Admin API via session cookie  |  |  |
| **[chdorner/secretbearsociety](https://github.com/chdorner/secretbearsociety)** <br>![Language](https://img.shields.io/github/languages/top/chdorner/secretbearsociety?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/chdorner/secretbearsociety?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/chdorner/secretbearsociety?style=for-the-badge) <br><sub>Script that pulls blocks from [RapidBlock](https://rapidblock.org/) plus a list of designated "peer instances" (via public API) and imports them. </sub> |  RapidBlock, remote instances (public API) | Admin API |  |  |
| **[d3cline/fossilize](https://github.com/d3cline/fossilize)** <br>![Language](https://img.shields.io/github/languages/top/d3cline/fossilize?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/d3cline/fossilize?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/d3cline/fossilize?style=for-the-badge) <br><sub>"Dynamic mastodon domain blocker" designed to automate identifying instances to block </sub> |   |  | Machine learning? | ? |
| **[azcoigreach/mastodon-blocklist-manager](https://github.com/azcoigreach/mastodon-blocklist-manager)** <br>![Language](https://img.shields.io/github/languages/top/azcoigreach/mastodon-blocklist-manager?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/azcoigreach/mastodon-blocklist-manager?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/azcoigreach/mastodon-blocklist-manager?style=for-the-badge) <br><sub>"A CLI tool to manage your Mastodon blocklist." </sub> |  Local TXT | Admin API | Multiple local TXT | Local TXT |
| **[jrconlin/block-sync](https://github.com/jrconlin/block-sync)** <br>![Language](https://img.shields.io/github/languages/top/jrconlin/block-sync?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/jrconlin/block-sync?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/jrconlin/block-sync?style=for-the-badge) <br><sub>"A mastodon admin tool to sync block lists between instances." </sub> |  Remote instances (public API) | Admin API |  |  |
| **[eigenmagic/fediblockhole](https://github.com/eigenmagic/fediblockhole)** <br>![Language](https://img.shields.io/github/languages/top/eigenmagic/fediblockhole?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/eigenmagic/fediblockhole?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/eigenmagic/fediblockhole?style=for-the-badge) <br><sub>"A tool for keeping a Mastodon instance blocklist synchronised with remote lists" including remote instance blocklists (via admin API) & URLs/files. </sub> |  Remote instances (admin API, public API), remote CSV, local CSV | Admin API |  |  |
| **[ericdano/Mastodon](https://github.com/ericdano/Mastodon)** <br>![Language](https://img.shields.io/github/languages/top/ericdano/Mastodon?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/ericdano/Mastodon?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/ericdano/Mastodon?style=for-the-badge) <br><sub>"Scripts for making Mastodon more manageable." </sub> |  Local CSV | Admin API |  |  |
| **[rrgeorge/rapidblocker](https://github.com/rrgeorge/rapidblocker)** <br>![Language](https://img.shields.io/github/languages/top/rrgeorge/rapidblocker?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/rrgeorge/rapidblocker?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/rrgeorge/rapidblocker?style=for-the-badge) <br><sub>"script to load rapidblock blocklist and more" </sub> | [RapidBlock](https://rapidblock.org/) | Admin API |  |  |
| **[gled-rs/mastodon-follow_blocks](https://github.com/gled-rs/mastodon-follow_blocks)** <br>![Language](https://img.shields.io/github/languages/top/gled-rs/mastodon-follow_blocks?style=for-the-badge) ![Stars](https://img.shields.io/github/stars/gled-rs/mastodon-follow_blocks?style=for-the-badge) ![Last Commit](https://img.shields.io/github/last-commit/gled-rs/mastodon-follow_blocks?style=for-the-badge) <br><sub>"allow you to follow another instance domain block and replicate for yours" </sub> | Remote Mastodon & gotosocial instances (admin API) | Admin API |  |  |

## Unmaintained

* [kensanata/mastodon-blocker](https://github.com/kensanata/mastodon-blocker)
* [ChlorideCull/MastoAdmin](https://github.com/ChlorideCull/MastoAdmin)
* [rummik/blockchain-sync](https://github.com/rummik/blockchain-sync)
* [hachyderm/hack](https://github.com/hachyderm/hack)
