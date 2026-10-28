# OpenFactory is now BeeverForge

OpenFactory 0.7 is the last OpenFactory release. The project continues as **BeeverForge**, an autonomous software factory: tickets in, reviewed pull requests out.

- **BeeverForge:** [beeverforge.com](https://beeverforge.com). Its code, issues and releases are at [BeeverForge/beeverforge-oss](https://github.com/BeeverForge/beeverforge-oss), and it installs as `beeverforge` on PyPI.
- **OpenFactory 0.7, the legacy line:** [BeeverForge/openfactory-core](https://github.com/BeeverForge/openfactory-core). It receives security fixes only, as 0.7.x patches, until BeeverForge 1.0 ships.
  - It still installs and upgrades with `curl -fsSL https://openfactory.digital/install.sh | sh`.
  - Its images stay at `ghcr.io/open-factory-digital`.
- **Moving a 0.7 deployment to BeeverForge:** BeeverForge 0.1.0 does not read OpenFactory's names yet, so install it fresh. The upgrade in place is planned for BeeverForge 0.2.0.

New issues and pull requests go to [BeeverForge/beeverforge-oss](https://github.com/BeeverForge/beeverforge-oss). Security reports follow its [SECURITY.md](https://github.com/BeeverForge/beeverforge-oss/blob/main/SECURITY.md).
