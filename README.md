# Unraid plugins

My Community Applications repository. The plugins themselves live in their own repos:

- [Docker Search](https://github.com/davidcoulson/unraid-docker-search): live search and quick filters for the Docker tab.
- [Storage Topology](https://github.com/davidcoulson/unraid-storage-topology): SAS and network hardware wiring and health.
- [LLDP for UNRAID](https://github.com/davidcoulson/LLDP-unRAID): lldpd service with switch-neighbour tables and a Dashboard tile (maintained fork of desertwitch's plugin).

This repo only holds the listings (`ca_profile.xml` and one XML per plugin under `plugins/`).
Each `<PluginURL>` must match the plugin's `.plg` `pluginURL` exactly.
