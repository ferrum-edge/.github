# Ferrum Edge

Ferrum Edge is an edge proxy written in Rust. One binary serves as a reverse proxy, API gateway,
AI gateway, and service mesh data plane. It supports HTTP/1.1, HTTP/2, HTTP/3, WebSocket, gRPC,
and raw TCP/UDP, and runs as a single node or as a control plane with data planes.

Website: [ferrumedge.com](https://ferrumedge.com) · [Install guides](https://ferrumedge.com/install) · [Release overview](https://ferrumedge.com/releases)

### Projects

| Project | What it is | Latest release | Edge pairing (per its release record) |
| --- | --- | --- | --- |
| [ferrum-edge](https://github.com/ferrum-edge/ferrum-edge) | The gateway: proxy, API gateway, AI gateway, and mesh. | [v0.9.21](https://github.com/ferrum-edge/ferrum-edge/releases/tag/v0.9.21) | — |
| [ferrum-contracts](https://github.com/ferrum-edge/ferrum-contracts) | Versioned cross-product wire contracts: schemas, vocabularies, and conformance fixtures. | [contracts-edge-0.9.21](https://github.com/ferrum-edge/ferrum-contracts/releases/tag/contracts-edge-0.9.21) | Matches Edge v0.9.21 |
| [ferrum-foundry](https://github.com/ferrum-edge/ferrum-foundry) | Management UI for a Ferrum Edge gateway. | [v0.5.6](https://github.com/ferrum-edge/ferrum-foundry/releases/tag/v0.5.6) | Qualified with Edge v0.9.20 and contracts-edge-0.9.20 |
| [ferrum-nexus](https://github.com/ferrum-edge/ferrum-nexus) | Portal for discovering, publishing, securing, and enabling APIs served through Ferrum Edge. | [v0.6.0](https://github.com/ferrum-edge/ferrum-nexus/releases/tag/v0.6.0) (source build; needs a new database, no upgrade from v0.5.2) | Tested only with Edge v0.9.20 |
| [ferrum-alloy](https://github.com/ferrum-edge/ferrum-alloy) | Toolkit for Rust API services on Axum, built to run behind Ferrum Edge. | [v0.1.0](https://github.com/ferrum-edge/ferrum-alloy/releases/tag/v0.1.0) (Git tag only; not on crates.io) | Supports Edge v0.9.20 and v0.9.19 |
| [ferrum-anvil](https://github.com/ferrum-edge/ferrum-anvil) | Desktop and command-line API testing client. | [0.1.9](https://github.com/ferrum-edge/ferrum-anvil/releases/tag/anvil-v0.1.9) security release; unsigned preview installers | — |
| [ferrum-edge-git-forge-ops](https://github.com/ferrum-edge/ferrum-edge-git-forge-ops) | GitOps workflow for managing Ferrum Edge configuration through pull requests. | No release yet; use from source | — |

The table distinguishes published release versions from documented Edge pairings.
Check each project's release notes before pairing it with a different gateway version.

### Get started

- **Gateway:** download a binary or pull `ferrumedge/ferrum-edge` from the
  [v0.9.21 release](https://github.com/ferrum-edge/ferrum-edge/releases/tag/v0.9.21) (checksums included), then follow the
  [ferrum-edge README](https://github.com/ferrum-edge/ferrum-edge/blob/main/README.md).
- **Foundry:** read [Upgrading](https://github.com/ferrum-edge/ferrum-foundry/blob/v0.5.6/docs/release-notes/v0.5.6.md#upgrading)
  and the [compatibility record](https://github.com/ferrum-edge/ferrum-foundry/blob/v0.5.6/docs/compatibility.json) before deploying.
- **Nexus:** the [getting-started walkthrough](https://github.com/ferrum-edge/ferrum-nexus/blob/v0.6.0/docs/getting-started.md).
- **Alloy:** the [getting-started guide](https://github.com/ferrum-edge/ferrum-alloy/blob/v0.1.0/docs/getting-started.md).
- **Anvil:** download from the [0.1.9 release](https://github.com/ferrum-edge/ferrum-anvil/releases/tag/anvil-v0.1.9) and verify with
  `SHA256SUMS` before running; see the [upgrade guide](https://github.com/ferrum-edge/ferrum-anvil/blob/anvil-v0.1.9/docs/upgrade-guide.md#019).

### License

These projects are copyright Ferrum Edge LLC and source-available under the
[PolyForm Noncommercial License 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0).
Commercial use requires a separate license from Ferrum Edge LLC; see each repository's license files.

### Contributing

Report bugs and request features in the relevant repository's issues. To contribute code, read
[CONTRIBUTING.md](https://github.com/ferrum-edge/ferrum-edge/blob/main/CONTRIBUTING.md) in
ferrum-edge first.
