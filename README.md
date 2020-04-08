# HackBar
Simple security audit / Penetration test tool
This toolbar will help you in testing sql injections, XSS holes and site security.

HackBar for Chrome.

Available on [Chrome Web Store](https://chrome.google.com/webstore/detail/hackbar/ginpbkfigcoaokgflihfhhmglmbchinc).

## Requested Permissions

* tabs
* webRequest
* webRequestBlocking

## Features

* Supported methods
  * GET
  * POST

* Auto Test
  * Common paths (Wordlist from [dirsearch](https://github.com/maurosoria/dirsearch/blob/master/db/dicc.txt) included)

* SQLi
  * Dump all database names (MySQL, PostgreSQL)
  * Dump tables from database (MySQL, PostgreSQL)
  * Dump columns from database (MySQL, PostgreSQL)
  * Union select statement (MySQL, PostgreSQL)
  * Error-based injection statement (MySQL, PostgreSQL)
  * Space to Inline comment

* XSS
  * Html encode/decode
  * String.fromCharCode encode/decode

* LFI
  * PHP wrapper - Base64

* SSTI
  * Flask RCE

* Encoding
  * URL encode/decode
  * Base64 encode/decode
  * Hexadecimal encode/decode
  * Unicode encode/decode

* Hashing
  * MD5
  * SHA1
  * SHA256
  * SHA512

Website: [vortex-team.org](https://vortex-team.org).
Telegram: [vortex_team_org](https://t.me/vortex_team_org).
