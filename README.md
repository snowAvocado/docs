# Documentation

The initial docs structure is detailed in [this comment](https://github.com/gatewayd-io/docs/issues/1#issuecomment-1442331491) and is as follows. This will be updated over time as the docs is written and shaped.

- Getting started
  - [x] [Welcome](pages/01-getting-started/01-welcome.md)
  - [x] [Installation](pages/01-getting-started/02-installation.md)
  - [x] [Running GatewayD](pages/01-getting-started/03-running-gatewayd.md)
  - [ ] [Resources](pages/01-getting-started/04-resources.md)
- Using GatewayD
  - [x] [Configuration](pages/02-using-gatewayd/01-configuration/index.md)
    - [x] [Global configuration](pages/02-using-gatewayd/01-configuration/index.md#global-configuration)
      - [x] [Loggers](pages/02-using-gatewayd/01-configuration/01-global-configuration/01-loggers.md)
      - [x] [Metrics](pages/02-using-gatewayd/01-configuration/01-global-configuration/02-metrics.md)
      - [x] [Clients](pages/02-using-gatewayd/01-configuration/01-global-configuration/03-clients.md)
      - [x] [Pools](pages/02-using-gatewayd/01-configuration/01-global-configuration/04-pools.md)
      - [x] [Proxies](pages/02-using-gatewayd/01-configuration/01-global-configuration/05-proxies.md)
      - [x] [Servers](pages/02-using-gatewayd/01-configuration/01-global-configuration/06-servers.md)
      - [x] [API](pages/02-using-gatewayd/01-configuration/01-global-configuration/07-api.md)
    - [x] [Plugins configuration](pages/02-using-gatewayd/01-configuration/index.md#plugins-configuration)
      - [x] [General configuration](pages/02-using-gatewayd/01-configuration/02-plugins-configuration/01-general-configurations.md)
      - [x] [Plugins configuration](pages/02-using-gatewayd/01-configuration/02-plugins-configuration/02-plugins-configuration.md)
    - [x] [Environment variables](pages/02-using-gatewayd/01-configuration/index.md#environment-variables)
    - [x] [Runtime configuration](pages/02-using-gatewayd/01-configuration/index.md#runtime-configuration)
  - [x] [CLI](pages/02-using-gatewayd/02-CLI.md)
  - [x] [Servers](pages/02-using-gatewayd/03-servers.md)
  - [x] [Clients](pages/02-using-gatewayd/04-clients.md)
  - [x] [Pools](pages/02-using-gatewayd/05-pools.md)
  - [x] [Proxies](pages/02-using-gatewayd/06-proxies.md)
  - [x] [Observability](pages/02-using-gatewayd/07-observability.md)
  - [x] [API](pages/02-using-gatewayd/08-API.md)
  - [x] [Connection lifecycle](pages/02-using-gatewayd/09-connection-lifecycle.md)
  - [x] [Protocols](pages/02-using-gatewayd/10-protocols.md)
- Using plugins
  - [x] [Plugins](pages/03-using-plugins/01-plugins.md)
  - [x] [Hooks](pages/03-using-plugins/02-hooks.md)
  - [x] [Plugin registry](pages/03-using-plugins/03-plugin-registry.md)
  - [x] [Hook registry](pages/03-using-plugins/04-hook-registry.md)
  - [x] [Plugin types](pages/03-using-plugins/05-plugin-types.md)
  - [x] [Proposals](pages/03-using-plugins/06-proposals.md)
- Developing plugins
  - [x] [Plugin lifecycle](pages/04-developing-plugins/01-plugin-lifecycle.md)
  - [ ] SDK reference
  - [ ] gRPC API reference
  - [ ] Template projects (Go and Python)
- GatewayD versus
  - [ ] MaxScale
  - [ ] ProxySQL
  - [ ] Acra
  - [ ] Stargate
  - [ ] Heimdall Data
  - [ ] Bytebase
  - [ ] Airbyte
  - [ ] Arana
  - [ ] Bouncers (PgBouncer, PgPool-II and pgcat)
- Community
  - [ ] Learning
  - [ ] Contributing
    - GatewayD public roadmap
    - Plugins public roadmap
    - Public proposals
  - [ ] Forum
  - [ ] Chat
  - [ ] Social accounts
  - [ ] Code of conduct
  - [ ] Test server
- Misc
  - [x] [Telemetry and usage report](pages/07-miscellaneous/telemetry-and-usage-report.md)
  - [ ] Error reporting
  - [ ] Release notes
  - [ ] [Glossary](pages/07-miscellaneous/glossary.md)
