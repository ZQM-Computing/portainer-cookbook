# Portainer Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **Portainer cookbook** — container management with an API and UI. Queued in wave-11 (per-node adds). Patterns are planned from the design, not yet from fleet runs. It is intended for Engineers who manage Docker hosts and stacks without living in the CLI. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** Portainer patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Engineers who manage Docker hosts and stacks without living in the CLI.

## Prerequisites

- Portainer via Docker
- A Docker host to manage
- API credentials, kept out of repos

## Patterns (planned)

**Nothing below exists yet.**

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-stack` | Deploying a first stack from the UI and from Compose |
| 02 | `02-api-basics` | Managing containers and stacks through the API |
| 03 | `03-access-control` | Users, teams, and endpoint access |
| 04 | `04-geo-stack` | A geospatial stack: tile server, catalog, and database |

## Repository layout

```text
portainer-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [geoserver-cookbook](https://github.com/ZQM-Computing/geoserver-cookbook) — Publishing, styling, federation, and securing OGC services
- [minio-cookbook](https://github.com/ZQM-Computing/minio-cookbook) — S3-compatible object storage from a source build
- [grafana-cookbook](https://github.com/ZQM-Computing/grafana-cookbook) — Dashboards, datasources, and alerts for geospatial stacks
