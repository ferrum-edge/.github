# Ferrum Edge

Ferrum Edge is an edge proxy written in Rust. One binary serves as a reverse proxy, API gateway,
AI gateway, and service mesh data plane. It supports HTTP/1.1, HTTP/2, HTTP/3, WebSocket, gRPC,
and raw TCP/UDP, and runs as a single node or as a control plane with data planes.

Website: [ferrumedge.com](https://ferrumedge.com)

### Projects

| Project | What it is | Status |
| --- | --- | --- |
| [ferrum-edge](https://github.com/ferrum-edge/ferrum-edge) | The gateway: proxy, API gateway, AI gateway, and mesh. | [Released](https://github.com/ferrum-edge/ferrum-edge/releases) |
| [ferrum-foundry](https://github.com/ferrum-edge/ferrum-foundry) | Admin UI for managing and observing a Ferrum Edge gateway. | [Released](https://github.com/ferrum-edge/ferrum-foundry/releases) |
| [ferrum-nexus](https://github.com/ferrum-edge/ferrum-nexus) | Multi-user developer portal in front of Ferrum Edge: API catalog, accounts, approvals, and audit history. | [Released](https://github.com/ferrum-edge/ferrum-nexus/releases) |
| [ferrum-edge-git-forge-ops](https://github.com/ferrum-edge/ferrum-edge-git-forge-ops) | GitOps template for managing gateway configuration through pull requests with GitHub Actions. | In development; no supported release yet |
| [ferrum-anvil](https://github.com/ferrum-edge/ferrum-anvil) | Desktop and command-line API client for requests, tests, and load tests. | Pre-release; not yet available |
| [ferrum-alloy](https://github.com/ferrum-edge/ferrum-alloy) | Rust toolkit for production Axum services, with Ferrum Edge tracing integration. | Pre-release; not published to crates.io |

### License

These projects are copyright Ferrum Edge LLC and source-available under the
[PolyForm Noncommercial License 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0).
Commercial use requires a separate license from Ferrum Edge LLC; see each repository's license files.

### Contributing

Report bugs and request features in the relevant repository's issues. To contribute code, read
[CONTRIBUTING.md](https://github.com/ferrum-edge/ferrum-edge/blob/main/CONTRIBUTING.md) in
ferrum-edge first.
