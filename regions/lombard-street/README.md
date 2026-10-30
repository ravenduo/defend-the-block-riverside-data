# Defend the Block: Lombard Street data feed

Public map data only. No app source, credentials, or player information.

Map data © OpenStreetMap contributors, ODbL 1.0:
https://www.openstreetmap.org/copyright
https://opendatacommons.org/licenses/odbl/1-0/

California extract: https://download.geofabrik.de/north-america/us/california.html

`manifest.json` identifies the current audited Lombard Street subset. `snapshots/<sha256>.json`
contains the complete derived database, including acquisition, license, source bounds,
and referenced source nodes. Snapshot filenames are immutable content hashes.

The app checks this manifest only on an explicit download or refresh. Source updates are
published by the maintainer after import, source geometry audit, and mission verification.
Deploy the manifest and new immutable snapshot together. Keep old snapshots available.
No Overpass API, paid service, worldwide coverage, 3D, or weather is involved.
