# OrangeSoom releases

This repository holds only signed release files for OrangeSoom: `OrangeSoom.exe`, `update.json`, `update.json.sig`.
No source code, settings or customer data are stored here.

The program checks `releases/latest/download/update.json` once at start and installs a new version only when
`update.json.sig` verifies against the public keys built into the program.
